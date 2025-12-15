# nuke_pad 
Desktop macro pad for turning on/restarting the PC with blocking press using Emergency STOP Button. Fun project, looking good on the table.    
To make it even a little useful, it is equipped with EC11 encoders, for adjusting the volume of the system and applications.    
In addition, there are two programmable buttons controlled by the ZMK.

<img src="img/cad.png" alt="cad" width="500"/>

### Features
- 2 buttons connected directyly to PC motherboard and 2 programmable buttons (actually 3)
- Emergency stop button (satisfying to press and spin) to avoid accidental pressing of PC off button
- Programmable rotary encoder EC11 (with button)
- LED strip to hightlight buttons or current ZMK layer

<!-- <img src="img/irl.jpg" alt="irl" width="500"/> -->


### Components list
| Name                                                                                                                                                                                                 | Quantity | Price (USD) | Comment                                                                                                                              |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| [NRF52840 board](https://aliexpress.ru/item/1005009516681283.html?sku_id=12000049341617471&spm=a2g2w.productlist.search_results.0.32ea4dbeAhuni3)                                                    | 1        | 1.55        | or similar supported by zmk analogali                                                                                             |
| [Emergency STOP Push Button](https://aliexpress.ru/item/1005002613977827.html?sku_id=12000021401318038&spm=a2g2w.productlist.search_results.14.4b686efab8oemC)                                       | 1        | 3.88        | or similar, then it will be necessary to change the mounting place                                                                   |
| [Switches Outemu Silent Peach V2](https://aliexpress.ru/item/1005006363535460.html?sku_id=12000036901918043&spm=a2g2w.productlist.search_results.11.15c64f2dn3sZhQ)                                  | 4        | 1.14        | good outemu switches (maybe the one that is good), any MX will work                                                                  |
| [XDA Profile Keycaps](https://aliexpress.ru/item/1005004389755716.html?spm=a2g2w.orderdetail.0.0.689b4aa6Efb6wZ&sku_id=12000030860342463&_ga=2.157131771.1520881471.1765715163-988742981.1763378754) | 4        | 2.16        | expensive, but good quality, any MX will work                                                                                        |
| [WS2812B RGBW Led Strip 60](https://aliexpress.ru/item/1005009339270479.html?sku_id=12000048803269587&spm=a2g2w.productlist.search_results.3.4d4a2665wzzpOD)                                         | 4 pixels | -           | LED step is not important, the tape is cut and each pixel is attached separately                                                     |
| [Reset button](https://aliexpress.ru/item/1005009149131677.html?sku_id=12000048094409160&spm=a2g2w.productlist.search_results.1.641e709anyLKcK)                                                      | 1        | 0.17        | I use a button from the PC case (check link) to not lose it, if your case use other option you can buy by link and print button part |
| [5pin socket F+M](https://aliexpress.ru/item/32837212844.html?sku_id=65102449054&spm=a2g2w.productlist.search_results.1.509552b5VlDOdD)                                                              | 1        | 1.47        | I use unique sockets from my work, but think GX12 variant works fine there + 5x0.5 cable works fine there                            |
| [Rotary Encoder EC11](https://aliexpress.ru/item/1005006693443387.html?sku_id=12000048311239356&spm=a2g2w.productlist.search_results.2.16186932cDnAvk)                                               | 1        | 0.68        | or similar, then it will be necessary to change the mounting and update zmk spi settings
| [Heat Brass Insert Nut M2 and DIN7991 Screws](https://aliexpress.ru/item/1005006798286851.html?sku_id=12000038340344499&spm=a2g2w.productlist.search_results.1.762852bbJJbRJt)                                          | 4        | -           | or analog
| [3D printed parts](https://github.com/Fliegende-Rehe/nuke_pad/blob/main/3d)                                                                     | 8-9        | -           | 3mf for bambustudio and step model if you want to edit anything

<img src="img/assembly.png" alt="assembly" width="1250"/>

### Wiring and assembly
Something


<img src="img/wiring.jpg" alt="wiring" width="300"/>

### Installation
1) 


### TODO:
1) 
2)
3) 
4) think of more appropriate name 