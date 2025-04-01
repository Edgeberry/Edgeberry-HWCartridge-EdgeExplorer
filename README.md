![Edgeberry banner](https://raw.githubusercontent.com/Edgeberry/.github/main/brand/EdgeBerry_banner_cartridge.png)

<img src="documentation//Edgeberry_Explorer_Cartridge_rendering.png" align="right" width="50%"/>

The Edgeberry **Edge Explorer** Hardware Cartridge is made for quick experimentation — helping you explore ideas by easily connecting sensors, actuators, and other peripherals to your Edgeberry system. It features the 4-pin 2.0 mm pitch JST-PH connectors, compatible with modules and breakouts from popular ecosystems like Grove, Crowtail, and STEMMA.

#### Ports:
- **5x Digital in/out** (with PWM on D1)
- **2x Analog input** (0-5V)
- **1x UART**
- **2x I2C**

<br clear="right"/>

## Layout

| Port     | Connection             | Info |
|----------|------------------------|------|
| **D1**   | GPIO12 <br/>GPIO20     | PWM     |
| **D2**   | GPIO21 <br/>GPIO16     |      |
| **D3**   | GPIO13 <br/>GPIO24     |      |
| **D4**   | GPIO25 <br/>GPIO22     |      |
| **D5**   | GPIO23 <br/>GPIO27     |      |
| **A1**   | *ADC* CH0 <br/>*ADC* CH1  |      |
| **A2**   | *ADC* CH2 <br/>*ADC* CH3  |      |
| **I2C**  | I2C SDA <br/>I2C SDL   |      |
| **UART** | UART RX <br/>UART TX   |      |

>[!WARNING]
>The digital I/O lines on this Hardware Cartridge use a passive N-MOSFET level-shifting circuit designed for compatibility with standard open-drain and push-pull I/O configurations.

On the Hardware Cartridge board is an ADC chip (MCP3008) connected with the SPI interface.


## License & Collaboration
**Copyright© 2024 Sanne 'SpuQ' Santens**. This project is released under the **CERN OHL-W** license. The [Rules & Guidelines](https://github.com/Edgeberry/.github/blob/main/brand/Edgeberry_Trademark_Rules_and_Guidelines.md) apply to the usage of the Edgeberry™ brand.

### Collaboration

If you'd like to contribute to this project, please follow these guidelines:
1. Fork the repository and create your branch from `main`.
2. Make your changes and ensure they adhere to the project's design style and conventions.
3. Test your changes thoroughly.
4. Ensure your commits are descriptive and well-documented.
5. Open a pull request, describing the changes you've made and the problem or feature they address.
