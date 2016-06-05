# Planet facts

Some facts about the planets in our solar system.

## Installation

```sh
npm install --save planet-facts
```

## Usage

```js
const planets = require('planet-facts')

console.log(`The volume of the Earth is ${planets.earth.volume}m³`)
```

## API

The following properties are exposed.

Property | Planet name
----- | -----
`mercury` | Mercury
`venus` | Venus
`earth` | Earth
`mars` | Mars
`jupiter` | Jupiter
`saturn` | Saturn
`uranus` | Uranus
`neptune` | Neptune
`pluto` | Pluto (included for historical reasons)

Each planet has the following properties.

Property | Unit | Description
----- | ----- | -----
`density` | kg/m³ | Density of the planet
`radius` | m | Equatorial radius of the planet
`volume` | m³ | Volume of the planet
`mass` | kg | Mass of the planet
