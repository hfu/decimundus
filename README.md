# decimundus
# NOT MAINTAINED: I currently use [duodecim](https://github.com/hfu/duodecim)
A way to divide the globe into 10 parts for equal amount of OSM data

![decimundus](decimundus.jpg)

# usage
```javascript
const decimundus = require('./decimundus.js')
for (const d of decimundus) {
  { minx: d[0], miny: d[1], maxx: d[2], maxy: d[3] }
}
```

# definitions
## #0
- 3/4/3 + 3/5/3

```
minx: 32
miny: 24
maxx: 47
maxy: 31
```

## #1
- 2/2/2 + 2/3/2

```
minx: 32
miny: 32
maxx: 63
maxy: 47
```

## #2
- 2/1/1

```
minx: 16
miny: 16
maxx: 31
maxy: 31
```

## #3
- 4/8/4 + 4/8/5

```
minx: 32
miny: 16
maxx: 35
maxy: 23
```

## #4
- 3/5/2 + 4/9/4 + 4/9/5

```
minx: 36
miny: 16
maxx: 47
maxy: 23
```

## #5
- 2/0/2 + 2/1/2

```
minx: 0
miny: 32
maxx: 31
maxy: 47
```

## #6
- 2/3/1

```
minx: 48
miny: 16
maxx: 63
maxy: 31
```

## #7
- 2/0/1

```
minx: 0
miny: 16
maxx: 15
maxy: 31
```

## #8
- 2/0/0 + 2/1/0 + 2/2/0 + 2/3/0

```
minx: 0
miny: 0
maxx: 63
maxy: 15
```

## #9
- 2/0/3 + 2/1/3 + 2/2/3 + 2/3/3

```
minx: 0
miny: 48
maxx: 63
maxy: 63
```
