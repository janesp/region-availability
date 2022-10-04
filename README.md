# Regional Availability Forecasts
## About our «Availability Initiative»
Welcome to our «regional availability forecast» initiative!

This initiative was triggered by the European energy crisis, caused by the Ukraine war. The idea is to inform energy consumers - both individual and commercial - in a timely manner about scheduled power unavailabilities (outages). Power can be mainly electricity and natural gas. Unavailabilities are forecasted by region. A region can be a municipality, but also any specific service area as defined by the energy provider.
## About this prototype
This forecasting prototype aims to visualize availability information on a map by region. Availabilities are predicted in periods from a given date and by region. Although the prototype was initially triggered by the energy crisis, it is implemented in a generic way where availabilities of any type can be visualized or otherwise made available by region.
* The prototype is implemented in Python (obviously)
* Visualization on maps is achieved through [geopandas](https://geopandas.org/), with regions represented by «shapes»
* For demonstration purposees, Swiss Kantons are used as regions, with region information from [view swissBOUNDARIES3D](https://www.swisstopo.admin.ch/en/geodata/landscape/boundaries3d.html) - but any region information can be used
* A (json) schema is defined for providers to report availability information in a standardized way
