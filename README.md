# Second Screen Module 

A 5" 720x1280 IPS screen expansion module for the Hackxpansion console.

Key features:
* 5" display, 720 x 1280 pixels
* LT7683 display controller
* Arduino-shield-style FFC interface
* Module connector to Hackxpansion console 


## Schematic
![[Pasted image 20261001223714.png]]

## PCB

![[Pasted image 20261001223757.png]]
## 3D Case

![[Pasted image 20261001224142.png]]with 3d case for screen coming when I receive the screen!
## Bill of Materials (excluding console)

Also found in [bom.csv](./bom.csv).

| Item                                            | Price per unit | Nr of units | Total price | Link                                               |
| ----------------------------------------------- | -------------- | ----------- | ----------- | -------------------------------------------------- |
| 5" 720x1280 IPS TFT, LT7683, 4-wire SPI shield  | $50.15         | 1           | $50.15      | https://www.buydisplay.com/                        |
| 2x7 2.54mm pin header (J1)                      | ~$0.20-0.39    | 1           | ~$0.20-0.39 | https://www.aliexpress.com/item/4000186187780.html |
| 1x08 2.54mm pin header (display wire connector) | ~$0.10         | 1           | ~$0.10      | -                                                  |
| MD0/MD1 ID resistors, 0603                      |                | 2           | -           | -                                                  |
| PCB fab                                         |                | 1           | around 10 $ | https://jlcpcb.com/                                |
| **Total**                                       |                |             | ~$60        |                                                    |
## Credits

* Display : [`lt7683` Rust crate](https://docs.rs/lt7683)
* Driver: [`xpanse_api`](https://docs.rs/xpanse-api)
* Display panel: [BuyDisplay ER-TFT050-10](https://www.buydisplay.com/)
* Thanks to Hack Club and the Hackxpansion team for the console platform this module plugs into: https://github.com/hackclub/hackxpansion
