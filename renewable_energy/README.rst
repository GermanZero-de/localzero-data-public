Renewable Energy Data
=====================

This data originates in the "Marktstammdatenregister" (https://www.marktstammdatenregister.de/MaStR/Einheit/Einheiten/OeffentlicheEinheitenuebersicht). This list
contains all registered and installed renewable energy producers (single solar cells, wind turbines etc.) and provides information on the current status, the units
power in kilo Watts, the date of installation etc. It also provides the location or more precisely the name of the city/village/town and the "Postleitzahl", where the unit is located.
This allows us to sum over all units within one commune and calculate the locally installed renewable power grouped by 

- pv (power of local photo voltaic cells) [kW]
- wind_on (power of local onshore wind turbines) [kW]
- biomass (power of local biomas power plants) [kW]
- water (power of local water power plants) [kW]

This summation and bucketing to all ags keys was done with the importMarktStammDaten.py script in the generator-core repository.
