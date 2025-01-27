# STM32H5 USB DFU HID demo
This guide provides a comprehensive approach to build an application on STM32 that combines HID and DFU functionalities into a composite USB device. By following these steps, you can create a USB device capable of both user interaction and firmware update.

## Hardware & Software needed

Hardware:
- [NUCLEO-H563](https://www.st.com/en/evaluation-tools/nucleo-h563zi.html) (using STM32H5 MCUs)
- 2x USB Type C Cables

Software:
- [STM32CubeProgrammer](https://www.st.com/en/development-tools/stm32cubeprog.html) (V1.15.0, do not use version V2.16.0 due to a limitation)

## Materials Provided

- STM32H5 USB DFU HID Project

## Setup

1) The demo uses the **NUCLEO-H563** (using STM32H5 MCUs) and 2x USB Type C Cables.
Connect STLINK USB conenctor of the Nucleo board to the Host.
2) Using STM32CubeProg (with STLINK connection mode) do a full erase of the chip.
3) Connect user USB connector of the Nucleo board to the Host.
4) Reset the STM32H5 on the Nucleo board by pressing reset Button (black button).

Please check the [knowledge base article](https://community.st.com/t5/tkb/workflowpage/tkb-id/stm32-mcus-knowledge-base/article-id/1254?prePageCrumb=TkbUserContributedArticlesPage) for more details.

## Troubleshooting
Refer to the knowledge base article for better details.

**Caution** : Issues and the pull-requests are **not supported** to submit problems or suggestions related to the software delivered in this repository. The example is being delivered as-is, and not necessarily supported by ST.

**For any other question** related to the product, the hardware performance or characteristics, the tools, the environment, you can submit it to the **ST Community** on the STM32 MCUs related [page](https://community.st.com/s/topic/0TO0X000000BSqSWAW/stm32-mcus).