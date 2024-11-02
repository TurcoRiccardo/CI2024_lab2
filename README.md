# CI2024_lab2

Lab 2 - Travelling salesman problem (TSP) (https://en.wikipedia.org/wiki/Travelling_salesman_problem)

- https://www.wolframcloud.com/obj/giovanni.squillero/Published/Lab2-tsp.nb

## Performances
- For he HC and the SA algorithm using insert_mutation have better result than using swap_mutation
- For the EA algorithm we are using an HYPERMODERN model with cycle_crossover, insert_mutation, a steady-state population model and for the parent selection we use tourment selection (tao = 2 number of selected parents)
    - POPULATION_SIZE = 50
    - OFFSPRING_SIZE = 10

### Vanuatu
| Algorithm | Steps/Generations |  Distance (km) |
|:---:|:---:|:---| 
|1GA|8|1475.53|
|HC|10000|1479.99|
|SA|1714|1345.54|
|EA|1000|1345.54|
|3GA|16|1420.31|

### Italy
| Algorithm | Steps |  Distance (km) |
|:---:|:---:|:---| 
|1GA|46|4436.03|
|HC|10000|5872.91|
|SA|3435|5641.64|
|EA|5000|4251.52|
|3GA|92|5448.26|

### Russia
| Algorithm | Steps/Generations |  Distance (km) |
|:---:|:---:|:---| 
|1GA|167|42334.16|
|HC|10000|78801.82|
|SA|17209|60034.26|
|EA|10000|49248.52|
|3GA|334|47913.71|

### US
| Algorithm | Steps/Generations |  Distance (km) |
|:---:|:---:|:---| 
|1GA|326|48050.03|
|HC|10000|157747.18|
|SA|17209|118350.84|
|EA|10000|90490.38|
|3GA|652|47727.19|

### China
| Algorithm | Steps/Generations |  Distance (km) |
|:---:|:---:|:---| 
|1GA|726|63962.92|
|HC|30000|249806.08|
|SA|34425|266883.26|
|EA|30000|154574.60|
|3GA|1452|64475.14|
