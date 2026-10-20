# Requirements and acceptance criteria

| ID | User story / requirement | Acceptance criteria |
| --- | --- | --- |
| RQ-01 | Robot detects a possible flame direction. | Three-channel IR flame sensor reading is visible in firmware and produces a defined movement/stop response. |
| RQ-02 | Robot avoids a physical obstacle. | Ultrasonic reading is checked and a safe alternate/stop behaviour occurs below the chosen threshold. |
| RQ-03 | Robot checks heat. | Temperature sensor reading is read and a defined safe behaviour is documented. |
| RQ-04 | Robot moves under controller command. | L298N and motors perform forward, reverse, left, right, and stop as verified in a controlled test. |
| RQ-05 | Robot directs water at target. | Servo movement and water pump are controlled separately and then as part of a safe combined sequence. |
| RQ-06 | Build can be reproduced. | Original sketch, board model, exact pin map, BOM, wiring diagram, photos, and test log are published. **Pending asset upload.** |

## Safety acceptance rule
No behaviour is accepted through testing with a real uncontrolled fire, mains-powered pump, unattended robot, or people/valuables in the test path.