# main-board
---
This is the repository for MOSAIC's Main Board.

For detailed documentation on the Main Board, check out its core documentation [here](https://www.mosaicsat.org/core_documentation/hardware/main_board/).

## Current Features
---
| Feature      | Description                          | Datasheet |
| :----------- | :------------------------------------ | :---------------------: |
| USB/Battery Voltage Regulator | Input: 2.2V-6V; Output: 1A max | [AP7361C](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8560079564241199104) |
| Qwiic Voltage Regulator | Input: 1.7-6V; Output: 500mA max, fixed 3.3V | [XC6503D331MR-G](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8590196445028003840) |
| Built-in Resettable PTC Fuse | Rated 5V/2A | [ASMD1210](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588899520989548544) |
| 2-Pin JST Connector | For connecting LiPo battery | [JST-PH 2-pin SMT](https://www.mouser.com/ProductDetail/485-1769) |
| Single Cell LiPo Charge Circuit | Charges attached single cell LiPo battery from USB power source | [MCP73831](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588884548142292992) |
| USB Type C Connector | For data connection with attached processor module and power transfer | [USB Type C Connector](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8590906928107372544) |
| 2x Qwiic Connectors | For data connection between other MOSAIC boards using the I^2^C protocol | [Qwiic Connector](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8590907288981364736) |
| SWD 2x5 Header | Serial Wire Debug header used for programming and debugging microcontrollers | N/A |
| Multiplexer for UART1  | For pin management between the two function board slots and the `Main Board` processor | [MAX4932ETD+T](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8589032502153789440) |
| Boot and Reset Buttons | For programming an attached `Main Board` processor | [Tactile Switch](https://jlcpcb.com/partdetail/11399-4_4_1_7_SurfaceMount/C10852) |
| 3x I/O switches | For pin management between the two function board slots and the `Main Board` processor | [Slide Switch](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8603117332785491968) |
