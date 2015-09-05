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
    "radius": 10.0,
    "fuel": 0.5,
    "crashed": false
  },
  "horizon": [0, 1, 4, 6, 10, 11, 12, 12, 12, 11, 5, 0, 1, 2, 1, 0]
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
* **radius**: the bounding radius of the lander.
* **fuel**: percentage of the remaining fuel.
* **crashed**: if the lander is crashed.

### `horizon`
The `horizon` holds the height information for the horizon. It is an array with `height` above 'sea level'.

[moonlander]: https://en.wikipedia.org/wiki/Lunar_Lander_%281979_video_game%29
