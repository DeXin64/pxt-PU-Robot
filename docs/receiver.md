# receiver

Receive radio control values on the robot micro:bit.

```sig
robotPu.enableRemoteControlWithGroup(160)
```

## Blocks in this section

Use these blocks on the robot micro:bit:

* `enable remote control on group`
* `disable remote control`
* `on value received`
* `current value`

## Example

This example updates the robot when a speed value is received.

```blocks
robotPu.enableRemoteControlWithGroup(160)
robotPu.onControlValueReceived(robotPu.ControlValueType.Speed, function (value) {
    if (value > 0.5) {
        robotPu.executeAction(robotPu.Action.Greet)
    }
})
```

## See also

* [controller](./controller)
* [actions](./actions)

```package
pxt-robotpu=github:elecfreaks/pxt-PU-Robot
```
