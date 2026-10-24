# Countries, states and cities data — licence

This folder contains an **adapted version** of the
[Countries States Cities Database](https://github.com/dr5hn/countries-states-cities-database)
by **dr5hn** (Darshan Gada), obtained through the npm package
[`@countrystatecity/countries`](https://github.com/dr5hn/countrystatecity-countries) 1.0.5.

Adaptations made for Go To Pray: names lower-cased; restructured into one JSON
file per country (`<country>.json`: `{ state: [cities] }`) plus `index.json`;
all other fields removed. This is the exact data shipped inside the Go To Pray webOS TV app.

This adapted database is made available under the
**Open Database License (ODbL) v1.0**: <http://opendatacommons.org/licenses/odbl/1.0/>.
Any rights in individual contents of the database are licensed under the
**Database Contents License (DbCL) v1.0**: <http://opendatacommons.org/licenses/dbcl/1.0/>.

Original notice: "ODbL-1.0 © dr5hn. This package and its data are licensed under
the Open Database License (ODbL) v1.0. The data is sourced from the Countries
States Cities Database which is also licensed under ODbL-1.0."
