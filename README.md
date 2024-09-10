# STM32_ADC_DMA

This application employs an Analog-to-Digital Converter (ADC) to periodically sample data from a potentiometer.
Also I am using direct memory access (DMA) controller to store data in memory without using CPU (Cortex M4).

## ADC configuration
![image](https://github.com/user-attachments/assets/b33f8061-e622-4b4c-b959-dc0133198405)

## DMA configuration
![image](https://github.com/user-attachments/assets/708fea6e-f3f2-4b6e-afd5-66b2982db524)

## Clock Configuration
We are using APB2 peripheral clock which is 84 MHZ 
![image](https://github.com/user-attachments/assets/357f2f08-876d-4c91-b19d-ac8d99c84ba0)

## Hardware connection set up
![image](https://github.com/user-attachments/assets/64962dea-a1b0-4177-bbe5-faf81dae8a69)

## Reading data from potentiometer in debug mode 
conversionFinished instance is used to check amount of task that has been done 
errorADC instance is used to check amount of errors 
 
![image](https://github.com/user-attachments/assets/86fc8c24-295b-4cbc-be65-b95779324cc8)


Microcontroller STM32F4VE

Course name: Mastering STM32 microcontrollers

Link: https://www.udemy.com/course/mastering-stm32f407-microcontrollers/
