# Go To Pray — data

Countries, states and cities used by **Go To Pray**, a free prayer-times app for
LG webOS TVs. Published here so the adapted database is openly available, as the
Open Database License requires.

## Contents

```
countries/index.json        [{ "name": "<country>", "file": "<file>.json" }, ...]
countries/<file>.json       { "<state>": ["<city>", ...], ... }
```

All names are lower-case. 250 countries.

## Source and licence

Adapted from the [Countries States Cities Database](https://github.com/dr5hn/countries-states-cities-database)
by dr5hn, via the npm package [`@countrystatecity/countries`](https://github.com/dr5hn/countrystatecity-countries) 1.0.5.

Licensed under the **Open Database License (ODbL) v1.0**; individual contents
under the **Database Contents License (DbCL) v1.0**. See [LICENSE.md](LICENSE.md).
