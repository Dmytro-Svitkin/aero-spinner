# aero-spinner
SVG *spinner* loading element for HTML inspired by Windows Vista (or Windows 7).

## Versions
There are currently 2 version: with white and cyan glow.

| White Glow Version | Cyan Glow Version | Revolution Time |
| --- | --- | --- |
| <img src="./assets/aero-spinner-animated-1s.svg"> | <img src="./assets/aero-spinner-2-animated-1s.svg"> | 1 second |
| <img src="./assets/aero-spinner-animated-0.75s.svg"> | <img src="./assets/aero-spinner-2-animated-0.75s.svg"> | 0.75 seconds |
| <img src="./assets/aero-spinner-animated-0.5s.svg"> | <img src="./assets/aero-spinner-animated-0.5s.svg"> | 0.5 seconds |

Both versions come in 3 revolution time settings: 1 second, 0.75 seconds and 0.5 seconds.<br>
However it is possible to acquire a custom revolution time setting by simply replacing the value of a `dur` field in any of the animated images.<br>
For example, it is possible to alter [<img src="./assets/aero-spinner-2-animated-0.75s.svg" width="10em">] by replacing:
```svg
    <animateTransform
       attributeName="transform"
       type="rotate"
       from="0 16 16"
       to="360 16 16"
       dur="0.75s"
       repeatCount="indefinite" />
```
With:
```svg
    <animateTransform
       attributeName="transform"
       type="rotate"
       from="0 16 16"
       to="360 16 16"
       dur="1.2s"
       repeatCount="indefinite" />
```
