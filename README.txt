哈工大2022计算机体系结构最终附加实验mips基本指令集实验环境

文件夹结构如下:
├── doc_v0.01
│   ├── A01_第六届系统能力培养大赛团体赛技术方案.pdf
│   ├── A02_大赛设计报告模板_仅供参考_v1.00.docx
│   ├── A03_“系统能力培养大赛”MIPS指令系统规范_v1.01.pdf            ***所需完成的全部指令的中文文档说明
│   ├── A04_龙芯体系结构教学实验箱（Artix-7）介绍_v1.00.pdf
│   ├── A05_龙芯体系结构实验箱（Artix-7）-原理图与引脚列表_v1.00
│   ├── A06_vivado安装说明_v1.00.pdf
│   ├── A07_vivado使用说明_v1.00.pdf
│   ├── A08_交叉编译工具链安装_v1.00.pdf
│   ├── A09_CPU仿真调试说明_v1.00.pdf                               ***对仿真环境的介绍说明
│   ├── A10_FPGA在线调试说明_v1.00.pdf
│   ├── A11_Trace比对机制使用说明_v1.00.pdf
│   ├── A12_类SRAM接口
│   ├── AMBA总线协议
│   └── MIPS32手册
├── func_test_v0.01
│   ├── cpu132_gettrace
│   │   ├── golden_trace.txt
│   │   ├── rtl
│   │   │   ├── BRIDGE
│   │   │   ├── CONFREG
│   │   │   ├── cpu132
│   │   │   ├── soc_lite_top.v
│   │   │   └── xilinx_ip
│   │   ├── run_vivado
│   │   │   ├── cpu132_gettrace
│   │   │   └── soc_lite.xdc
│   │   └── testbench
│   │       └── tb_top.v
│   ├── README.txt
│   ├── soc_sram_func
│   │   ├── rtl
│   │   │   ├── BRIDGE
│   │   │   ├── CONFREG
│   │   │   ├── soc_lite_top.v
│   │   │   └── xilinx_ip
│   │   ├── run_vivado
│   │   │   ├── mycpu_prj1
│   │   │   └── soc_lite.xdc
│   │   └── testbench
│   │       └── mycpu_tb.v
│   ├── soft
│   │   ├── func
│   │   └── memory_game
│   └── 功能测试说明_v0.01.pdf                                      ***sram接口的说明和仿真使用方法
└── README.txt                                                      ***本文件，说明实验环境结构

33 directories, 41 files

其中***表示必读文件，含有重要的指导信息
doc文件夹存放大量的文档说明，包括Vivado和MIPS32手册
func_test_v0.01文件夹下为整个实验环境，具体说明参照A09_CPU仿真调试说明_v1文档
对实验的理解请按照如下顺序阅读,并结合实验指导说明一起理解
功能测试说明_v0.01  ->  A09_CPU仿真调试说明_v1  ->  A03_“系统能力培养大赛”MIPS指令系统规范_v1
