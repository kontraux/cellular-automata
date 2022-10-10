# Cellular-Automata
Cellular automata in Lua

Example:

```

local grid = ca.new_grid(20, 20)
ca.new_noise(grid, 0.4, true)
grid = ca.simulation_step(grid, 5, 4)

for i, v in pairs(grid) do
    print(table.unpack(v))
end

--Output:

1       1       1       1       1       0       1       1       1       0       1       1       1       0       1       1       1       1       1       1
1       1       1       1       1       1       1       1       1       1       1       1       1       1       1       1       1       1       1       1
1       1       1       0       0       0       1       1       0       0       0       0       0       0       0       1       1       1       1       1
1       1       1       1       1       1       1       1       1       1       0       1       1       1       1       0       0       0       1       0
0       1       0       1       0       0       0       1       0       1       1       1       0       1       1       1       0       0       0       0
0       1       0       1       1       1       0       1       1       1       1       1       1       1       1       1       0       0       1       1
0       1       0       0       0       0       0       1       1       1       0       0       0       0       1       1       1       0       1       1
0       0       0       1       1       1       0       1       0       0       0       0       0       0       0       1       0       1       1       1
0       1       0       1       1       0       0       1       0       0       0       0       0       0       0       1       0       1       1       1
0       1       0       1       1       1       1       1       0       0       1       1       1       1       0       0       0       1       1       1
1       1       1       1       1       1       1       1       1       1       1       1       1       0       0       0       0       1       1       1
1       1       1       1       1       1       0       1       1       1       1       1       1       1       1       0       0       0       1       1
1       1       1       1       1       0       0       1       1       1       0       0       0       0       0       0       0       0       1       1
1       1       0       0       0       0       0       1       1       0       0       0       1       1       0       0       0       0       1       1
1       1       0       0       0       0       1       1       0       0       0       1       1       0       0       0       0       1       1       1
1       1       0       0       0       1       1       1       0       0       0       0       0       0       0       0       1       1       1       1
1       1       0       0       0       0       1       1       1       0       0       0       0       0       0       0       1       1       1       1
1       1       1       0       0       0       1       1       1       1       0       0       0       0       0       0       0       1       1       1
1       1       1       1       1       1       1       1       1       1       1       1       0       1       1       1       1       1       1       1
1       1       1       1       1       1       0       1       1       1       1       1       0       1       1       1       0       1       1       1

```
