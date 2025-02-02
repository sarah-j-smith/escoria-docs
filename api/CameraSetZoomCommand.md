<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# CameraSetZoomCommand

**Extends:** [ESCBaseCommand](../ESCBaseCommand) < [Node](../Node)

## Description

`camera_set_zoom magnitude [time]`

Zooms the camera in/out to the desired `magnitude`. Values larger than 1 zoom
the camera out while smaller values zoom in, relative to the default value
of 1.

**Parameters**

- *magnitude*: Magnitude of zoom
- *time*: Number of seconds the transition should take, with a value of `0`
  meaning the zoom should happen instantly (default: `0`)

For more details see: https://docs.escoria-framework.org/camera

@ESC

## Method Descriptions

### configure

```gdscript
func configure() -> ESCCommandArgumentDescriptor
```

Return the descriptor of the arguments of this command

### run

```gdscript
func run(command_params: Array) -> int
```

Run the command