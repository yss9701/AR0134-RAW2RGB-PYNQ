# AR0134-RAW2RGB-PYNQ
正点原子ZYNQ开发板  
vivado版本2018.3，AR0134全局曝光，最高720p/60fps  
FPGA摄像头DVP数据采集，raw转rgb（Xilinx Sensor Demosaic ip），两路vdma，一路lcd显示（800×480），一路ps处理（1280×720）  
pynq框架下摄像头sccb配置，采集图像，转Mat，OpenCV处理  
vivado hls 图像rgb顺序转换，resize  
注：摄像头帧率调整0x3030寄存器（PLL)  
0x301A寄存器最后配置（开启传输）
