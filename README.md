This page contains the information to understand the Smart Air (GeoCENS) project/platform and how to get started with the platform.

Smart Air extends the existing GeoCENS platform to collect and analyze hyper-local and real-time air quality data across Canada. Smart Air will provide street-level air quality data with an unprecedented spatio-temporal resolution, leading to transformative new innovations with direct impacts to the health of Canadians.

### Download
Please see our [github repository](https://github.com/smart-air-geocens/) to download the source code.

### Factsheet
> What are you measuring?

We are measuring PM 2.5, a fine particulate matter that is very important to air quality and related health issues. Read more here. We are also measuring temperature and relative humidity.

> What kind of sensor are you using?

Each device has three sensors: tempertature, humidity, and PM 2.5. PM 2.5 sensors are the ones measuring air quality. They are small, laser-based sensors with an onboard fan that circulates air. Learn more from http://aqicn.org/sensor/pms5003-7003/.

> How is the project funded? The sensor devices and the cloud infrastructure, web applications, analytics, expertise, etc. must all cost a lot.

The project is funded 50% by GeoConnections (Natural Resources Canada), and 50% by partner communities or volunteers.

> How are the devices calibrated and who is responsible for that? How often is that done?

Devices are not calibrated as part of the pilot.

> Where are the devices manufactured and by whom?

The WiFi connectivity part of the device, the firmware, is created by SensorUp. The board on which the firmware run is custom-made for SensorUp.

> Since the devices will connect to the volunteer’s own WiFi can those devices be used to compromise the volunteers' home network or other networks?

The device is accessed via username and password, so it is as secure as any other device that is password protected. Any threat would actually come through a person's router, not through this device, and would be unrelated to having the device. That is, the same threat exists with or without the device.

> Are there any other data collected that is not being disclosed?

There is no data being collected that is not being disclosed.

> What kind of paperwork will volunteers be asked to sign (if any)?

Volunteers are asked to fill in the sign-up form. Note no payment is required for volunteers coming in through community partners. They'll also be asked to agree to alpha testing, in a standard alpha agreement.

> Because of how the sensors will be located at random based on volunteer participation, it seems that the data collected will not be representative of the various types of environments that exist within the community. As a result, would we be able to use the data for research purposes or for communicating about air quality?

Sensor data can be analyzed based on the land use or functional area zone they were in. SensorUp's backend is totally GIS compatible, so it would be quite possible to load live sensor data into a GIS that also housed functional zones, then compare sensor data based on functional areas, time of day, etc. Also, in some communities, volunteers are selected based on their location. These communities are confident they'll have sensors exactly where they want them.

> We have other air quality monitoring projects in our community. How does this fit in? Will in conflict with other monitoring? Will it confuse the publc?

SensorUp's citizen-based air quality monitoring complements other monitoring programs, air quality or otherwise. This is because SensorUp's open standard-based backend is designed to make the various monitoring programs, devices, and networks of smart cities compatible. The program also engages volunteers, on a air quality, and a 'techie' level, making it different to most programs.

> The provincial, or federal, government already has high-precision air quality monitoring stations here. Why would we need more?

SensorUp's network of sensors provide additional information at a much higher geographic and temporal resolution. It adds information as an additional, complementary network. It is not meant to replace, or otherwise substitute, for the existing network of air quality station.

> We already report on traffic related air pollutants. Why would we need this?

Enhanced geographic resolution is very useful in reporting how traffic affects air quality. This particular use case requires good geographic resolution, to understand effects on air quality near roads and intersections, and the decay function in PM2.5 readings as distance from roads increases (i.e. the improvement in air quality measures as you get farther from a road). In addition, the high temporal resolution is useful in understanding the effects of high-use times and congestion, such as rush hour or construction.

> We have device calibration/controls and data accuracy concerns.

Devices in this program are run as a distributed network that has data quality checks in the other devices in the network, as well as the provincial/federal high-precision stations. That's how we ran the program in the past -- as a complement to the existing network, not a replacement.

> Will there be difficulty relaying PM2.5 findings? Could there be inconsistent messaging?

Our messaging can be tailored to your needs. If you feel your community requires additional information to understand the nature and context of the readings and monitoring program, we are happy to add the language you need. In addition, we have not yet had concerns from the public in our already running communities about PM 2.5 reading interpretation.

### Licence
* Smart Air User Portal: [MIT](https://opensource.org/licenses/MIT)
* OGC SensorThings API: [OGC License](https://portal.opengeospatial.org/modules/admin/license_agreement.phpsuppressHeaders=0&access_license_id=3&target=)

### Provenance
New releases of the managed GeoCENS components are handled by SensorUp Inc. Before each release any tests for the component or service are run to verify integration. After release the services are monitored by a service. Each release will be accompanied by commits and changelog updates on the GeoCENS web site.

### ReleaseNotes
#### [1.0] - 2019-08-09
* First release of Smart Air User Portal
* First release of SensorThings Platform
* First release of QA/QC and re-gridding modules

### Support
SensorUp Inc. supports and maintains the project. Please open up an issue on our [github](https://github.com/smart-air-geocens/) if you found a bug or had a feature request.

### TryMe
* [Smart Air User Portal](https://geocens.sensorup.com/)



Supported by <img width="120px" src="https://www.canarie.ca/wp-content/uploads/CANARIE_h.png"/>