# Behaviour diagram

```text
Start / safe power-on
        |
        v
Read flame, distance, and temperature sensors
        |
        +--> Unsafe temperature / sensor fault? --> stop motors and pump; signal safe state
        |
        +--> Obstacle close? --> stop / turn / re-check
        |
        +--> Flame direction detected? --> orient robot; aim servo; operate pump only in controlled demonstration
        |
        +--> No target? --> stop or safe search behaviour defined by original firmware
        |
        v
Repeat with manual stop available
```

This conceptual diagram must be aligned with the original firmware once the sketch is uploaded.