
### A befunge interpreter written in r5rs scheme
```Scheme
(befunge "(befunge "64+\"!dlroW ,olleH\">:#,_@")"
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
- this implementation can be accept grids of almost any size
- Rows can have variable sizes but will all be maximized in the grid
- use escape characters for `"` and `\`