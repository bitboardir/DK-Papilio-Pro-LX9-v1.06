# DK-Papilio-Pro-LX9-v1.06
![Board Image](/papilio_pro.PNG)

Overview

This is a development board based on the Xilinx Spartan-6 XC6SLX9 FPGA chip. It is an excellent choice for implementing custom digital systems, designing soft-core processors, and teaching digital architecture.

Unlike the reference version (Papilio Pro LX9), which uses an on-board programmer for JTAG/Serial communication, this version provides a standard 2×7-pin JTAG connector, allowing connection to external programmers such as Digilent HS2 or isolated models.

A USB-to-Serial converter based on the CH340 chip is also included, enabling UART communication—especially useful when working with soft processors like ZPUino or MicroBlaze in the Arduino environment.
Technical Specifications

    FPGA: Xilinx Spartan-6 XC6SLX9-2TQG144C

    RAM: 256 Mbit SDRAM

    JTAG Connector: Standard 2×7-pin header for external programming

    Serial Communication: CH340 USB-to-UART converter

    Power Supply: Via USB or 7–15V DC adapter jack

    Arduino IDE Support: Compatible through soft-core processors like ZPUino

    I/O Ports: Expandable GPIO headers for shields or external modules

    Form Factor & Design: Compatible with breadboards and custom PCBs


HOW to Program Board in Arduino Based Enviroment DesignLab :


Download DesignLab and install:

![Download design lab and install](/pic/1_download_design_lab_and_install.PNG)

loade bit file zpuino-2.0-PapilioPro-S6LX9-RetroCade-1.3.bit

![loade bit file](/pic/2_loader.PNG)

select_example:

![select_example](/pic/3_select_example.png)

select_board:

![select_board](/pic/4-select_board.png)

select_port:

![select_port](/pic/5-select_port.png)

program_example_and_open_terminal:

![program_example_and_open_terminal](/pic/6_program_example_and_open_terminal.png)


