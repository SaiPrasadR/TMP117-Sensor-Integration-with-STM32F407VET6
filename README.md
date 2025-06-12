# TMP117-Sensor-Integration-with-STM32F407VET6
Project reads live temperature from TMP117 sensor's 16-bit registers, converts it to °C, and sends via UART. High and Low temperature limits can be set via UART and written to TMP117 registers. An alert pin connected to EXTI triggers when temperature exceeds set limits, raising an alarm if live temperature crosses thresholds.
