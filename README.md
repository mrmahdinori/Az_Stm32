![Logo](https://github.com/mrmahdinori/Az_Stm32/blob/main/Stm32.png)
# Az_Stm32

تمام فایل های مربوط به آزمایش های عملی کتاب در این قسمت (تست شده) به صورت فایل zip قرار گرفته است.


غالبا پروگرامر های موجود در بازار اورجینال نبوده و امکان عمل Debug در محیط Cube IDE در آن فراهم نیست، بنابراین لازم است از فایل Hex استفاده شود.

از داخل فولدر Debug هر پروژه فایل .hex برایتان در دسترس هست، با استفاده از نرم افزار STM32 ST-LINK Utility میتوانید آن را پروگرام کنید.

برای تولید فایل .HEX پروژه خود

روش اوم: در مسیر
Properties -> C/C++ Build -> Settings -> Tool Settings -> MCU Post build outputs
تیک گزینه Convert to Intel HEX file را فعال کنید.

روش دول : ابتدا پروژه خود را در محیط IDE انتخاب کرده و بر روی آن کلیک راست کنید از قسمت
 Properties -> C/C++ Build -> Settings -> Build Steps -> Post-build step
  کد زیر را وارد , در نهایت Apply را بزنید تا تغییرات ذخیره شود.
  arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex
از این پس هنگام کامپایل برنامه خود فایل Hex همراه آن تولید خواهد شد.
## دانلود نرم افزار ها


[Stm32 Cube IDE](https://www.st.com/en/development-tools/stm32cubeide.html)

[Stm32 Cube MX](https://www.st.com/en/development-tools/stm32cubemx.html)

[ST-LINK Utility](https://www.st.com/en/development-tools/stsw-link004.html)

## مستندات

[Stm32F10xxx Reference Manual ](https://www.st.com/resource/en/reference_manual/rm0008-stm32f101xx-stm32f102xx-stm32f103xx-stm32f105xx-and-stm32f107xx-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)

[Stm32F1 HAL & Lowayer Drivers User Manual](https://www.st.com/resource/en/user_manual/um1850-description-of-stm32f1-hal-and-lowlayer-drivers-stmicroelectronics.pdf)


 
## سازنده

- [@mrmahdinori](https://www.github.com/mrmahdinori)


