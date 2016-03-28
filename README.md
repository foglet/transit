#Transit

This repository contains transit routes from the world's cities. It is divided by system type: metro (i.e., subway or U-Bahn), tram and light rail (S-Bahn), cable car and funicular, trolley bus, monorail and maglev, and ferries. No systems are represented for North Korea (KP), outside of Pyongyang.

#### Data Source

Most files are from [OpenStreetMap](http://www.openstreetmap.org) (OSM) queried via [overpass-turbo.eu](http://overpass-turbo.eu/). Search parameters:

	route=ferry,
	route=funicular or railway=funicular,
	route=light_rail or railway=light_rail,
	route=tram or railway=tram,
	route=subway or railway=subway,
	route=monorail or railway=monorail,
	route=trolley_bus or trolley_wire=yes

#### Naming Convention

Files are generally labeled by two-letter country code, city/location, and by transit type. For example,

	ch-lausanne-lr.geojson		(Switzerland, Lausanne, lightrail)
	fi-helsinki-tram.geojson	(Finland, Helsinki, tram)
