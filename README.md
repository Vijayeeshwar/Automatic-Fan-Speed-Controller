# Automatic-Fan-Speed-Controller

## Description

This project reads temperature data from a DHT11 sensor and automatically controls a DC motor (fan) based on the temperature level. The LCD display shows the current temperature and fan status (speed level).

## Working

The DHT11 sensor reads the temperature every 2 seconds.

If temperature exceeds 29°C, the motor turns ON at low speed.

If temperature exceeds 32°C, the motor runs faster.

The LCD shows both the current temperature and fan speed status.