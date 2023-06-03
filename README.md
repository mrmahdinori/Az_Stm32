# Az_Stm32
در این بخش تمام فایل های مربوط به آزمایش های عملی کتاب (تست شده) قرار گرفته است.
از داخل فولدر Debug هر پروژه فایل .hex برایتان در دسترس هست، با استفاده از نرم افزار STM32 ST-LINK Utility میتوانید آن را پروگزام کنید.



لینک دانلود رسمی نرم افزار های Stm32 Cube



برای تولید فایل .HEX پروژه خود ابتدا پروژه خود رو انتخاب و بر روی ان کلیک راست کنید از قسمت
 Properties > C/C++ Build > Settings > Build Steps -> Post-build step
  کد زیر را وارد کنید
  arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex
در نهایت Apply را بزنید تا تغییرات ذخیره شود
 


