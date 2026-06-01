# controller

Use a second micro:bit as a handheld radio controller for the PU Robot.

```sig
robotPu.setControllerRadioGroup(160)
```

## Blocks in this section

Use these blocks on the controller micro:bit:

* `set controller radio group`
* `read joystick value`
* `initialize controller buttons`
* `button pressed`
* `send value`
* `send text message`

## Example

This example sends turn and speed values over radio.

```blocks
robotPu.setControllerRadioGroup(160)
robotPu.sendControlValue(robotPu.SendControlType.Turn, robotPu.readJoystickValue(robotPu.JoystickAxis.Turn))
robotPu.sendControlValue(robotPu.SendControlType.Speed, robotPu.readJoystickValue(robotPu.JoystickAxis.Speed))
```

## See also

* [receiver](./receiver)
* [README](../README)

```package
pxt-robotpu=github:elecfreaks/pxt-PU-Robot
```
