# actions

Make the PU Robot walk, turn, pose, or move individual servos.

```sig
robotPu.executeAction(robotPu.Action.Greet)
```

## Blocks in this section

Use these blocks to make the robot move:

* `set mode`
* `stop action`
* `set robot move direction`
* `walk for steps at speed`
* `set servo to angle`
* `smooth move servo to angle`

## Example

This example makes the robot greet and then walk forward.

```blocks
robotPu.executeAction(robotPu.Action.Greet)
basic.pause(500)
robotPu.setWalkSpeed(robotPu.MoveDirection.Forward, 4, 6)
```

## See also

* [setup](./setup)
* [sensors](./sensors)

```package
pxt-robotpu=github:elecfreaks/pxt-PU-Robot
```
