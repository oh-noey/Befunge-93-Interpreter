### A befunge interpreter written in r5rs scheme
```Scheme
(befunge "64+\"!dlroW ,olleH\">:#,_@")
```
Prints `Hello, World!`

```Scheme
(befunge "v>>>>>v"
         " 12345"
         " ^?^"
         "> ? ?^"
         " v?v"
         " 6789"
         " >>>> v"
         "^    .<")
```
Prints an infinite stream of random numbers between 1 and 9
#### Notes:
- this implementation can accept grids of almost any size, which may break programs that use the fixed grid size
- Rows can have variable sizes but will all be maximized in the grid
- use escape characters for `"` and `\`
### Links:
- [The official Befunge documentation](http://www.nsl.com/papers/befunge93/befunge93.htm)
- [Befunge on Esolang](https://esolangs.org/wiki/Befunge) 

*There are slight differences between the specification on Esolang and the official ones. This implemntation uses the specifications described on Esolang.*
