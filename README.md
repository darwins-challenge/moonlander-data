# moonlander-data
Description of the Moonlander data

This document describes the data that will be used in describe the [moonlander][] world.

## Data

```json
{
  "lander": {
    "x": 37.0, "y": 51.1,
    "vx": 0.2, "vy": -4.3,
    "orientation": 0.3, "angular-velocity": 0.1,
    "fuel": 0.5
  }
}
```

### `lander`
The `lander` holds the information of the actual `lander`. We describe its properties below.

* **x**: horizontal position
* **y**: vertical position
* **vx**: the horizontal component of the velocity
* **vy**: the vertical component of the velocity
* **orientation**: the degrees from the vertical position in radians. Positive radians is in the clockwise direction, negative radians is in the counter-clockwise direction.
* **angular-velocity**: radians per seconds the orientation changes.
* **fuel**: percentage of the remaining fuel.

[moonlander]: https://en.wikipedia.org/wiki/Lunar_Lander_%281979_video_game%29
