# Sopracciglio Template
KiCad V10.99 Project Template for Custom Arduino Sopracciglio Boards (Compatible with the 2026 Open Sauce Badge)

![Board Image](https://github.com/miekush/sopracciglio-template/blob/main/template_3d.png)

# Pinout
This template is designed to be compatible with the 2026 Open Sauce badge! See below pinout diagram with the interface to the badge.
![Pinout Diagram](https://github.com/miekush/sopracciglio-template/blob/main/pinout.png)

# Schematic Organization
The schematic page is organized with both a template area (top of the page) and the user application area (bottom of the page). Assuming you are designing a board to be compatible with the Open Sauce 2026 badge, you will only need to add your application circuit to the bottom of the page and connect it up to the global net labels defined in the template section!
![Schematic](https://github.com/miekush/sopracciglio-template/blob/main/schematic_layout.png)

# Badge BOM
If you are looking into designing a custom Sopracciglio, I am going to assume you didn't get a chance to pick up the rest of the badge BOM given out at the event. No worries! I prepared the below table with the parts you need.
| Component | Manufacturer | Part Number | Quantity | Link |
| :---: | :---: | :---: | :---: | :---: |
| Red 5mm LED | Kingbright | WP7113LID | 3 | [LINK](https://www.mouser.com/en/ProductDetail/Kingbright/WP7113LID?qs=58z0TXQGVSSHpg5ffhrd2A%3D%3D) |
| Electret Microphone | Adafruit | 1064 | 1 | [LINK](https://www.mouser.com/en/ProductDetail/Adafruit/1064?qs=GURawfaeGuCJB%2FnFnPensg%3D%3D&srsltid=AU7gw4UbQJqqEjNZ9j3UnxyGzBRpcP_HHrTYrMvaeZpJ46jDriWZPpl2) |
| 6mm Tactile Switch | C&K | PTS645SL50-2 | 1 | [LINK](https://www.mouser.com/en/ProductDetail/CK/PTS645SL50-2-LFS?qs=rqnA19JZHeTZYaJU%252B5olWA%3D%3D) |
| 2.54mm Pin Socket | - | - | 2 | [LINK](https://www.ebay.com/itm/185899066103) |
| CR2032 Holder | - | - | 1 | [LINK](https://www.ebay.com/itm/173791027293?_skw=cr2032+holder&itmmeta=01M404NKJYFY3N84Q4BEEECQ8Q&hash=item2876c0a05d:g:G8kAAOSwWnhcYxb9&itmprp=enc%3AAQALAAAA0GfYFPkwiKCW4ZNSs2u11xCTp4t7h5x6%2BLTZO1shhRb2yKPiok1i3Ns7PxYxYKZ1mL7aFbKOy%2FwALUbQWRP1k6fdwBux83v1IIbOXyzm65JOcJUaTh71e3IvfFmBnAeyCJgvSAcSuDTq%2B%2FirFVUTh3VaGpFWpJ6Tr1QahcvdHgPPrqCAsUuanrPhuWsATQf8N3vTCKG%2Fh8DhX03wM286PoCnbccFY1M%2F5V5z5At3tHhVmAQwQUYqIL0qPYclUxwMg2lVBeT1iKx2kCNxPIDRUEA%3D%7Ctkp%3ABk9SR9a51oSgaA) |

# Installation

1. Clone repo to a folder of your choice
2. Open the project in KiCad V10.99
3. "Save As" with the name of your project
4. Enjoy! :)

# License

miekush supports the open source hardware community by sharing hardware design files freely on GitHub!

Designed by Mike Kushnerik (miekush)

Licensed under [Creative Commons Attribution-ShareAlike CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

All text above must be included in any redistribution!
