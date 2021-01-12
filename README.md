# <div align="center">Flutter Text Kit</div>

<div align="center">A flutter package which contains a collection of some cool and awesome buttons.</div><br>  
<div align="center">
  <a href="https://flutter.dev">
    <img src="https://img.shields.io/badge/Platform-Flutter-02569B?logo=flutter"
      alt="Platform" />
  </a>
  <a href="https://pub.dartlang.org/packages/animated_text_kit">
    <img src="https://img.shields.io/pub/v/animated_text_kit.svg"
      alt="Pub Package" />
  </a>
  <br>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/github/license/aagarwal1012/flutter_button?color=red"
      alt="License: MIT" />
  </a>
</div><br>

# Table of contents

- [Installing](#installing)
- [Usage](#usage)
  - [New with Version 3](#new-with-version-3)
- [Animations](#animations)
  - [Rotate](#rotate)
  - [Fade](#fade)
  - [Typer](#typer)
  - [Typewriter](#typewriter)
  - [Scale](#scale)
  - [Colorize](#colorize)
  - [TextLiquidFill](#textliquidfill)
  - [Wavy](#wavy)
  - [Create your own Animations](#create-your-own-animations)
- [Bugs or Requests](#bugs-or-requests)
- [Donate](#donate)
- [Contributors](#contributors)

# Installing

### 1. 

Add this to your package's `pubspec.yaml` file:

```yaml
dependencies:
  animated_text_kit: ^3.1.0
```

You can install and import packages from the command line:

```
$ flutter pub get
```



# Buttons 
## Rotate

<img src="https://github.com/aagarwal1012/Animated-Text-Kit/blob/master/display/rotate.gif?raw=true" align = "right" height = "300px">

```dart
Row(
  mainAxisSize: MainAxisSize.min,
  children: <Widget>[
    SizedBox(width: 20.0, height: 100.0),
    Text(
      "Be",
      style: TextStyle(fontSize: 43.0),
    ),
    SizedBox(width: 20.0, height: 100.0),
    RotateAnimatedTextKit(
      onTap: () {
        print("Tap Event");
      },
      text: ["AWESOME", "OPTIMISTIC", "DIFFERENT"],
      textStyle: TextStyle(fontSize: 40.0, fontFamily: "Horizon"),
      textAlign: TextAlign.start
    ),
  ],
);
```

**Note:** You can override transition height by setting the value of parameter `transitionHeight` for RotateAnimatedTextKit class.


# How to Contribute this package?

See [Contributing.md](https://github.com/aagarwal1012/Animated-Text-Kit/blob/master/CONTRIBUTING.md).

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome! See [Contributing.md](https://github.com/aagarwal1012/Animated-Text-Kit/blob/master/CONTRIBUTING.md).
