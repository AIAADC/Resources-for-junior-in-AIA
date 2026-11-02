# 微机原理

[大三课程总览](../README.md) · [独立课程仓](https://github.com/AIAADC/Principles-of-Microcomputers)

本次整理第 1–6 章课件、8086 指令参考、2026 实验指导书、实验模板与验收说明，以及星研软件和配套手册。共 24 个原始文件，其中 2 个大文件通过 Releases 下载。


## 资料下载

| 文件 | 大小 |
| --- | ---: |
| [8086指令(all).docx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/8086%E6%8C%87%E4%BB%A4%28all%29.docx) | 1.28 MiB |
| [微机原理资料包/微机原理资料包/《微机原理实验》实验报告模版.docx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E3%80%8A%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E5%AE%9E%E9%AA%8C%E3%80%8B%E5%AE%9E%E9%AA%8C%E6%8A%A5%E5%91%8A%E6%A8%A1%E7%89%88.docx) | 408.7 KiB |
| [微机原理资料包/微机原理资料包/实验疑问总结.doc](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%AE%9E%E9%AA%8C%E7%96%91%E9%97%AE%E6%80%BB%E7%BB%93.doc) | 611.5 KiB |
| [微机原理资料包/微机原理资料包/实验验收流程.docx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%AE%9E%E9%AA%8C%E9%AA%8C%E6%94%B6%E6%B5%81%E7%A8%8B.docx) | 10.9 KiB |
| [微机原理资料包/微机原理资料包/微机原理实验指导书（2026）.pdf](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E5%AE%9E%E9%AA%8C%E6%8C%87%E5%AF%BC%E4%B9%A6%EF%BC%882026%EF%BC%89.pdf) | 2.75 MiB |
| [微机原理资料包/微机原理资料包/星研/setup32.exe](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/setup32.exe) | 38.62 MiB |
| [微机原理资料包/微机原理资料包/星研/setup64.exe](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/setup64.exe) | 39.95 MiB |
| [微机原理资料包/微机原理资料包/星研/如何在KEIL UVISION2、UVISION3中使用STAR系列仿真器.DOC](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/%E5%A6%82%E4%BD%95%E5%9C%A8KEIL%20UVISION2%E3%80%81UVISION3%E4%B8%AD%E4%BD%BF%E7%94%A8STAR%E7%B3%BB%E5%88%97%E4%BB%BF%E7%9C%9F%E5%99%A8.DOC) | 117.5 KiB |
| [微机原理资料包/微机原理资料包/星研/如何在KEIL UVISION2、UVISION3中使用STAR系列仿真器.pdf](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/%E5%A6%82%E4%BD%95%E5%9C%A8KEIL%20UVISION2%E3%80%81UVISION3%E4%B8%AD%E4%BD%BF%E7%94%A8STAR%E7%B3%BB%E5%88%97%E4%BB%BF%E7%9C%9F%E5%99%A8.pdf) | 149.4 KiB |
| [微机原理资料包/微机原理资料包/星研/如何在KEIL UVISION2、UVISION3中使用STAR系列实验仪的仿真模块.DOC](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/%E5%A6%82%E4%BD%95%E5%9C%A8KEIL%20UVISION2%E3%80%81UVISION3%E4%B8%AD%E4%BD%BF%E7%94%A8STAR%E7%B3%BB%E5%88%97%E5%AE%9E%E9%AA%8C%E4%BB%AA%E7%9A%84%E4%BB%BF%E7%9C%9F%E6%A8%A1%E5%9D%97.DOC) | 70.0 KiB |
| [微机原理资料包/微机原理资料包/星研/如何在KEIL UVISION2、UVISION3中使用STAR系列实验仪的仿真模块.pdf](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/%E5%A6%82%E4%BD%95%E5%9C%A8KEIL%20UVISION2%E3%80%81UVISION3%E4%B8%AD%E4%BD%BF%E7%94%A8STAR%E7%B3%BB%E5%88%97%E5%AE%9E%E9%AA%8C%E4%BB%AA%E7%9A%84%E4%BB%BF%E7%9C%9F%E6%A8%A1%E5%9D%97.pdf) | 64.9 KiB |
| [微机原理资料包/微机原理资料包/星研/最新使用手册.doc](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/%E6%9C%80%E6%96%B0%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.doc) | 6.31 MiB |
| [微机原理资料包/微机原理资料包/星研/最新使用手册.pdf](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94/%E6%9C%80%E6%96%B0%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.pdf) | 3.26 MiB |
| [微机原理资料包/微机原理资料包/星研仪器相关问题记录.docx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E6%98%9F%E7%A0%94%E4%BB%AA%E5%99%A8%E7%9B%B8%E5%85%B3%E9%97%AE%E9%A2%98%E8%AE%B0%E5%BD%95.docx) | 11.3 KiB |
| [微机原理资料包/微机原理资料包/补丁/DirectX4.0.zip](https://github.com/AIAADC/Principles-of-Microcomputers/releases/download/course-materials-20261103/DirectX4.0.zip) | 185.55 MiB |
| [微机原理资料包/微机原理资料包/补丁/VC2018.zip](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E8%A1%A5%E4%B8%81/VC2018.zip) | 36.35 MiB |
| [微机原理资料包/微机原理资料包/补丁/vcredist.zip](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E5%BE%AE%E6%9C%BA%E5%8E%9F%E7%90%86%E8%B5%84%E6%96%99%E5%8C%85/%E8%A1%A5%E4%B8%81/vcredist.zip) | 13.69 MiB |
| [微机原理资料包.zip](https://github.com/AIAADC/Principles-of-Microcomputers/releases/download/course-materials-20261103/microcomputer-lab-materials.zip) | 319.84 MiB |
| [第2章_8086CPU.pptx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E7%AC%AC2%E7%AB%A0_8086CPU.pptx) | 911.6 KiB |
| [第3章_8086的寻址方式和指令系统.pptx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E7%AC%AC3%E7%AB%A0_8086%E7%9A%84%E5%AF%BB%E5%9D%80%E6%96%B9%E5%BC%8F%E5%92%8C%E6%8C%87%E4%BB%A4%E7%B3%BB%E7%BB%9F.pptx) | 1.42 MiB |
| [第4章汇编语言程序设计.pptx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E7%AC%AC4%E7%AB%A0%E6%B1%87%E7%BC%96%E8%AF%AD%E8%A8%80%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1.pptx) | 543.2 KiB |
| [第5章_存储器.pptx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E7%AC%AC5%E7%AB%A0_%E5%AD%98%E5%82%A8%E5%99%A8.pptx) | 2.93 MiB |
| [第6章_IO接口和并行接口芯片8255A.pptx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E7%AC%AC6%E7%AB%A0_IO%E6%8E%A5%E5%8F%A3%E5%92%8C%E5%B9%B6%E8%A1%8C%E6%8E%A5%E5%8F%A3%E8%8A%AF%E7%89%878255A.pptx) | 2.13 MiB |
| [绪论.pptx](https://github.com/AIAADC/Principles-of-Microcomputers/blob/main/%E7%BB%AA%E8%AE%BA.pptx) | 9.22 MiB |

## 复习建议

1. 先练数制、补码和分段寻址，再整理寄存器用途以及指令对标志位的影响。物理地址计算与默认段搭配要能独立完成。
2. 第 3 章按“寻址方式—操作数来源—有效地址—默认段”列表比较，结合指令参考逐条跟踪寄存器和内存变化。
3. 第 4 章用顺序、分支、循环和子程序串联汇编框架，区分机器指令、伪指令与 DOS/BIOS 功能调用。
4. 第 5–6 章结合地址译码、RAM/ROM 连接、I/O 传送方式与 8255A 控制字画图复习；把每根地址线和每个位的作用说清楚。
5. 实验先读 2026 指导书和验收流程，再查星研手册；先理解接口与程序的对应关系，再记录自己的操作和观测结果。

更详细的版本说明与使用建议见 [课程 README](https://github.com/AIAADC/Principles-of-Microcomputers#readme)。
