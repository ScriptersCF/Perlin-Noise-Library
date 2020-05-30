# Perlin Noise

### Function:
``PerlinNoise.new({X,Y,Z,W}, amplitude, octaves, persistence)``

Coordinates are all 0 by default, amplitude is 10 by default, octaves are 1 by default and persistence is .5 by default.

#### Usage:
```lua
local PerlinNoise = require(game.ReplicatedStorage:WaitForChild("PerlinNoise"))

print(PerlinNoise.new({5.5,45,21,6.32}, 15, 3, 0.5))
```

` > 0.056077744190892`
