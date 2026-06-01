# setup

Configure the PU Robot before starting a lesson or a movement routine.

```sig
robotPu.setWalkSpeedRange(2, 2)
```

## Blocks in this section

Use these blocks to calibrate the robot and limit how fast it can walk:

* `set servo trim`
* `set walk speed range`

## Example

This example keeps the robot at a moderate speed for classroom use.

```blocks
robotPu.setServoTrim(0, 0, 0, 0, 0, 0)
robotPu.setWalkSpeedRange(2, 2)
```

## See also

* [actions](./actions)
* [README](../README)

```package
pxt-robotpu=github:elecfreaks/pxt-PU-Robot
```
