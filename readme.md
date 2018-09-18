#k-convert

Start with

```sh
const kconvert = require("../k-convert");
```

And then, you are able to convert float numbers to the k-metric:

```sh
kconvert.convertTo(420500)
```

Returns "420.5k"

and convert strings using the k-metric to float numbers:

```sh
kconvert.convertFrom("23.2k");
```

Returns 23200
