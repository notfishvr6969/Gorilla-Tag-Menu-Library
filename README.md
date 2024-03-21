i just fix it for new updates


# Menu Maker 3000

This is a simple but powerful mod menu creation tool for the VR game Gorilla Tag.

## Authors

- [@0xVidde#1337]()


## FAQ

#### Will this be updated?

***Absolutely yes***, I plan on adding support for so much more *than there already is*.

#### Will I get banned for using this?

***No***. This is just a tool for creating a interactable menu in game, not a hacking tool. Though I can't really stop you from doing what you want with it.

## Features

- Create your **own** custom menu is 5 minutes
- Page System
- Button System
- Input System; Handle your *all* controller input with just 1 line of code!
- Object Oriented!
- Built In Documentation!
- Open Source


## Usage/Examples

```c#
MenuTemplate menu = MenuTemplate.CreateMenu(
    "Hello World",     // Title
    new Vector3(0.1f, 1f, 1f),     // Size
    Color.black,            // Color
    GorillaLocomotion.Player.Instance.leftControllerTransform.gameObject  // Pivot Point
);
```

