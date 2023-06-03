# Az_Stm32 ![Logo]([https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png](https://github.com/mrmahdinori/Az_Stm32/blob/main/STM32.png?raw=true))

## در این بخش تمام فایل های مربوط به آزمایش های عملی کتاب (تست شده) قرار گرفته است.
## از داخل فولدر Debug هر پروژه فایل .hex برایتان در دسترس هست، با استفاده از نرم افزار STM32 ST-LINK Utility میتوانید آن را پروگزام کنید.



برای تولید فایل .HEX پروژه خود ابتدا پروژه خود رو انتخاب و بر روی ان کلیک راست کنید از قسمت
 Properties -> C/C++ Build -> Settings -> Build Steps -> Post-build step
  کد زیر را وارد , در نهایت Apply را بزنید تا تغییرات ذخیره شود
  arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex



## دانلود نرم افزار ها


[Stm32 Cube IDE](https://www.st.com/en/development-tools/stm32cubeide.html)

[Stm32 Cube MX](https://www.st.com/en/development-tools/stm32cubemx.html)

[ST-LINK Utility](https://www.st.com/en/development-tools/stsw-link004.html)

## Documentation

[Stm32F10xxx Reference Manual ](https://www.st.com/resource/en/reference_manual/rm0008-stm32f101xx-stm32f102xx-stm32f103xx-stm32f105xx-and-stm32f107xx-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)

[Stm32F1 HAL & Lowayer Drivers User Manual](https://www.st.com/resource/en/user_manual/um1850-description-of-stm32f1-hal-and-lowlayer-drivers-stmicroelectronics.pdf)


 
## سازنده

- [mrmahdinori](https://www.github.com/mrmahdinori)


