# Example project to run rust game loop on android
This is an example for an implementation of https://github.com/Kaiser1989/game-gl for Windows and Android, running the game loop and rendering a red window with lena.
Inputs (click, Keyboard & Touch) are logged, to give you some idea how to handle them.

Follow installation information from https://github.com/Kaiser1989/game-gl

Start Emulator or connect your phone and just run:
`cargo apk run --release`

## Example Input

```
11-17 20:37:48.455 30954 31109 I RustStdoutStderr: TouchEvent { state: Down, location: Location { x: 376.0, y: 1075.0 }, id: 0 }
11-17 20:37:48.476 30954 31109 I RustStdoutStderr: TouchEvent { state: Move, location: Location { x: 376.0, y: 1075.0 }, id: 0 }
11-17 20:37:48.572 30954 31109 I RustStdoutStderr: TouchEvent { state: Move, location: Location { x: 376.0, y: 1075.0 }, id: 0 }
11-17 20:37:48.605 30954 31109 I RustStdoutStderr: TouchEvent { state: Move, location: Location { x: 376.0, y: 1075.0 }, id: 0 }
11-17 20:37:48.639 30954 31109 I RustStdoutStderr: TouchEvent { state: Move, location: Location { x: 376.0, y: 1076.458 }, id: 0 }
11-17 20:37:48.655 30954 31109 I RustStdoutStderr: TouchEvent { state: Move, location: Location { x: 376.0, y: 1077.7513 }, id: 0 }
11-17 20:37:48.672 30954 31109 I RustStdoutStderr: TouchEvent { state: Move, location: Location { x: 376.0, y: 1078.0 }, id: 0 }
11-17 20:37:48.672 30954 31109 I RustStdoutStderr: TouchEvent { state: Up, location: Location { x: 376.0, y: 1078.0 }, id: 0 }
```
