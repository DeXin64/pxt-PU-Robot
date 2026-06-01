# actuators

Control the PU Robot LEDs and eye brightness.

```sig
robotPu.setAmbienceLight(robotPu.LightSelection.All, 255, 0, 0)
```

## Blocks in this section

Use these blocks to control lights:

* `set ambience light`
* `set left eye right eye`
* `set left eye brightness`
* `set right eye brightness`

## Example

This example turns all ambience lights blue and opens both eyes.

```blocks
robotPu.setAmbienceLight(robotPu.LightSelection.All, 0, 0, 255)
robotPu.setEyesState(robotPu.EyeState.On, robotPu.EyeState.On)
```

## See also

* [actions](./actions)
* [sensors](./sensors)

```package
pxt-robotpu=github:elecfreaks/pxt-PU-Robot
```
