# sensors

Read the PU Robot sensors and body state.

```sig
robotPu.ultrasonicDistance(robotPu.DistanceUnit.Centimeters)
```

## Blocks in this section

Use these blocks to read the robot state:

* `ultrasonic sensor distance`
* `body roll`
* `body pitch`
* `music tempo`
* `front distance array`

## Example

This example shows a warning when an obstacle is close.

```blocks
if (robotPu.ultrasonicDistance(robotPu.DistanceUnit.Centimeters) < 15) {
    robotPu.setEyesState(robotPu.EyeState.On, robotPu.EyeState.Off)
}
```

## Return value

Most blocks return a number. `front distance array` returns an array of five readings sampled across the front of the robot.

## See also

* [actions](./actions)
* [actuators](./actuators)

```package
pxt-robotpu=github:elecfreaks/pxt-PU-Robot
```
