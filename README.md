# zcu102_public

Wellcom to Zynq ZCU102 
======================

cdma
----

Xilinx에서 제공되는 CDMA IP Core를 사용하여 Bram에 있는 데이터를 
CDMA를 통해 PS로 전달하는 드라이버를 구현하였다.

>**Note.**
> - 개인이 연습삼아 구현한 코드이고, xilinx의 코드를 모방하였기 때문에
어떤 버그가 있을지 모른다.

폴더 구성
--------

hw - 하드웨어 디자인 압축파일이 들어있다.
image - 이미지 압축 파일들이 있다.
sw/driver - 드라이버 파일 
sw/device-tree - 사용자가 생성한 디바이스트리 파일
sw/peekpoke - xilinx에서 제공한 어플리케이션 파일
