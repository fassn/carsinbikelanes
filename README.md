CARS IN BIKE LANES
------------------

CIBL is a browsable geographic database for documenting crowdsourced traffic violation reports. Designed originally to publicly track illegal automotive encroachment into New York City bike lanes at carsinbikelanes.nyc, it has become apparent that this web app can be easily adapted for simple crowdsourced documentation of any geo-located event, particularly any sort of observable traffic violation.

In a LAMP environement CIBL will deploy itself out of the box via a simple setup wizard. The Mapbox map API is currently supported, while support for other map services in the near future is planned. CIBL records the time, date, cross streets, GPS coordinates, user description and image of each record. GPS coordinates and date/time are pulled from image exif data if available via the included exif.js library. Administrative credentials are protected with PHPass. CIBL's mobile view is designed for quick and easy capture and upload of records on the go. A submissions queue allows administrative users to accept or deny pending submissions.

CIBL was designed by a cyclist, inspired by the need for cycling advocacy in a city where law enforcement sentiment toward biking reads as apathetic, dismissive, and harmful. With enough public interest an active CIBL database has the potential to change hearts and minds, and expose endemic traffic and safety issues. Adapt it for your city however you'd like. Better yet, invite your local law enforcement agency to be involved!