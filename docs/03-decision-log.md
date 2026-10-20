# Decision log

| Decision | Choice | Rationale | Current limit |
| --- | --- | --- | --- |
| Platform | Arduino wheeled robot | Appropriate for a third-semester hands-on electronics project. | Exact board model needs confirmation. |
| Flame sensing | Three-channel IR flame module | Provides directional indication for a small prototype. | Sensor can be affected by ambient light and is not fire certification. |
| Obstacle avoidance | Ultrasonic sensor | Simple distance measurement for basic local avoidance. | Does not guarantee safe navigation around all surfaces/angles. |
| Heat check | Temperature sensor | Adds a separate environmental signal/protection check. | Does not replace flame detection or safety control. |
| Drive | L298N with DC motors | Common controllable motor-driver arrangement for a wheeled prototype. | Exact power limits and wiring must be verified. |
| Water direction | Servo-mounted nozzle plus pump | Makes the extinguishing direction adjustable. | Water and electronics require controlled testing only. |