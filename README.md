# city-timezones

A light and fast method of looking up timezones given the name of city.

```bash
npm install city-timezones
```

```javascript
var cityTimezones = require('city-timezones');
```

### cityTimezones.lookupViaCity(city: string)

If a city is found, returns an **array** with city, state, lat, lng, timezone. Returns `[]` if city not found. Multiple cities can be found if they have the same name i.e. Springfield.

finding based on Chicago by name:
```javascript
[ { city: 'Chicago',
    city_ascii: 'Chicago',
    lat: 41.82999066,
    lng: -87.75005497,
    pop: 5915976,
    country: 'United States of America',
    iso2: 'US',
    iso3: 'USA',
    province: 'Illinois',
    exactCity: 'Chicago',
    exactProvince: 'IL',
    state_ansi: 'IL',
    timezone: 'America/Chicago' } ]
```