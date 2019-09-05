# STM32_PWMInputCapture
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FSummerFalls%2FSTM32_PWMInputCapture.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FSummerFalls%2FSTM32_PWMInputCapture?ref=badge_shield)

 可直接编译后烧录到ST官方的NUCLEO_F302R8开发板上运行
 
 此为软件方式实现PWM输入捕获
 
 本工程使用TIM15定时器来捕获PWM，外部输入引脚为TIM15_CH2
 
 ## 开发环境
 - TrueStudio 9.3.0
 - STM32CubeMX 5.2.0

 ### 注意
 - 如果您使用其它IDE，例如Keil、IAR时，源文件只需参考main.c、usart.c即可，CubeMX的工程文件 '\*.ioc' 可通过另存为新的工程后，选择您使用的IDE进行工程的生成。
 


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FSummerFalls%2FSTM32_PWMInputCapture.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FSummerFalls%2FSTM32_PWMInputCapture?ref=badge_large)