# Geo : Addresses format

Addresses format templat by country

```json
// ...
"FR": [
    "",
    "{house_number} {street_type} {street_name}",
    "{postcode:digit(5)} {city:uppercase}",
    "France"
]
// ...
```