### simpleCMSIS  
***  
Проект для [статьи](https://habr.com/ru/post/481478/)

Простой проект мигания светодиодом с использованием библиотеки CMSIS.  
Отладочная плата STM32F072B-DISCO с микроконтролером STM32F072RBT6.  
Тактирование от внутреннего генератора HSI48, частота 48 МГц.  
Источник функции задержки - прерывание таймера SysTick, настроенное на период 1 мс.  
Светодиод подключен к выводу 6 порта С, настроенного как push-pull выход.  
***  
***  
Project for [article](https://habr.com/ru/post/481478/)  

Simple LED flashing project using CMSIS library.  
Debug board STM32F072B-DISCO with STM32F072RBT6 MCU.  
Clock from HSI48 Internal Generator, 48 MHz.  
Delay function source - SysTick timer interrupt set for 1 ms.  
The LED is connected to pin 6 of port C configured as push-pull output.  
