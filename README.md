# Raspberry Pi Environmental Sensor Logger

> Coursework edge component for an example environmental-monitoring system.

A Python logger for a Raspberry Pi that reads temperature and PIR motion-sensor data, then writes timestamped telemetry to a configured cloud database.

## What it demonstrates

- Raspberry Pi GPIO interaction for motion sensing
- Temperature capture with `W1ThermSensor`
- Environment-based database configuration
- Timestamped temperature and motion event writes

## Related repositories

- [Flask telemetry API](https://github.com/AxelDiazA2G/environmental-monitoring-api)
- [React dashboard](https://github.com/AxelDiazA2G/environmental-monitoring-dashboard)

## Required configuration

Set these environment variables on the target device:

```text
API_KEY
DATABASE_URL
DB_NAME
```

Never commit real values for these settings.

## Hardware and runtime boundary

This project is designed for a Raspberry Pi with a compatible temperature sensor and a PIR sensor on GPIO pin 23. It is a coursework example, not a claim of a maintained production IoT deployment.
