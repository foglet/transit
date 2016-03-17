# transit

This repository contains transit routes from the world's cities. It is divided by system type: metro (i.e., subway or U-Bahn), tram and light rail (S-Bahn), cable car and funicular, trolley bus, monorail and maglev, and ferries.

Most files are labeled by two-letter country code, city/location, and how each was queried in Overpass-Turbo. E.g.,

	ch-lausanne-lr (Switzerland, Lausanne, search: route=light_rail)
	fi-helsinki-tram (Finland, Helsinki, search: route=tram)
	kz-oskemen-railtram (Kazakhstan, Oskemen, search: railway=tram)
	mx-mxc-raillight (Mexico, Mexico City, search: railway=light_rail)
	ir-listowel-monorail.geojson (Ireland, Listowel, route=monorail)
	uk-LHR-monorail.geojson (Ukraine, LHR (IATA airport code), route=monorail)
	ua2-donezVuhlehirsk-trolleybus.geojson (Ukraine/two cities, Donez/Vulehirsk, search: route=trolleybus)
	ru-smolensk-trolleywire (Russia, Smolensk, search: trolley_wire=yes)

Ferry routes are generally named the same however they often cover a widespread area and the city is not so specific. 

