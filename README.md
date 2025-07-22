### **Datasheet: STM32G0B1CET6N**

#### **Descrição**

O STM32G0B1 é um microcontrolador da linha principal (*mainstream*) baseado no núcleo RISC de 32 bits Arm® Cortex®-M0+ de alto desempenho, operando em frequências de até 64 MHz.

#### **Arquitetura e Características Técnicas**

* **Núcleo:** Arm® 32-bit Cortex®-M0+ CPU com frequência de até 64 MHz.

* **Memórias:**
    * Até 512 Kbytes de memória Flash com proteção, área de segurança e suporte a leitura-durante-escrita.
    * 144 Kbytes de SRAM, dos quais 128 Kbytes possuem verificação de paridade por hardware.

* **Periféricos de Comunicação:**
    * Três interfaces I²C com suporte a Fast-mode Plus (1 Mbit/s).
    * Seis USARTs com capacidade de SPI síncrono mestre/escravo.
    * Duas LPUARTs (Low-Power Universal Asynchronous Receiver Transmitter).
    * Três SPIs operando a até 32 Mbit/s, com duas interfaces multiplexadas com I²S.
    * Dois controladores FDCAN.
    * Um controlador USB 2.0 Full-Speed (device e host) com capacidade de operação sem cristal (*crystal-less*).
    * Um controlador USB Type-C™ Power Delivery.

* **Periféricos Analógicos:**
    * Um conversor A/D de 12 bits e 0.4 µs com até 16 canais externos.
    * Dois conversores D/A de 12 bits com sample-and-hold de baixo consumo.
    * Três comparadores analógicos rápidos de baixo consumo.

* **Temporizadores:**
    * Um total de 15 timers: um de 16-bit para controle de motor avançado, um de 32-bit e seis de 16-bit de propósito geral, dois timers básicos, dois de baixo consumo, dois watchdogs e um SysTick timer.

* **Gerenciamento de Energia:**
    * Faixa de tensão de alimentação: 1.7 V a 3.6 V.
    * Modos de baixo consumo: Sleep, Stop, Standby e Shutdown.
    * Alimentação VBAT para o RTC e registros de backup.
