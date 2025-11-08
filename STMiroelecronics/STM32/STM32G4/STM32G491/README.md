# STM32G491 Compute Module

## Preset IO:
| IO     | Use |
| ------ | --- |
| JTAG   | Debug trace and flashing |
| LPUART | Debug port serial console |
| USB    | Serial Console, Device Firmware Update (DFU), and external +5V power (not meant for system +3.3V power) |

## Hardware List:
| Part | Part # | Link | Use |
| ---- | ------ | ---- | --- |
| Microcontroller | STM32G491RET6 | https://estore.st.com/en/stm32g491ret6-cpn.html | Processor Core |
| 48 MHz Occilator | SG-8201CJ48.0000M-TDJSA0 | https://www.mouser.com/ProductDetail/Epson-Timing/SG-8201CJ-48.0000M-TDJSA0?qs=3vio67wFuYqIz383TCBBFQ%3D%3D | For HSE clock input (Main Clock) |
| 32.768 KHz Occilator | ECS-327ATQ2016MV-BS-TR | https://www.mouser.com/ProductDetail/ECS/ECS-327ATQ2016MV-BS-TR?qs=1Kr7Jg1SGW%2F4fwCwairowg%3D%3D | For LSE clock input (RTC) |