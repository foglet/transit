#Transit

This repository contains transit routes from the world's cities. It is divided by system type: metro (i.e., subway or U-Bahn), tram and light rail (S-Bahn), cable car and funicular, trolley bus, monorail and maglev, and ferries. No systems are represented for North Korea (KP), outside of Pyongyang.

#### Data Source

Most files are from OpenStreetMap (OSM) queried via overpass-turbo.eu. Search parameters:

	route=ferry (ferry, in filename) 
	route=funicular (funicular) or railway=funicular (railfun)
	route=light_rail or (lr) railway=light_rail (raillight)
	route=tram (tram) or railway=tram (railtram)
	route=subway (metro) or railway=subway
	route=monorail (monorail) or railway=monorail (railmono)
	route=trolley_bus (trolley) or trolley_wire=yes (trolleyes)

#### Naming Convention

Most files are labeled by two-letter country code, city/location, and the query parameter tag from above. For example,

	ch-lausanne-lr.geojson		(Switzerland, Lausanne, lightrail)
	fi-helsinki-tram.geojson	(Finland, Helsinki, tram)

