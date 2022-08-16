## openEO: Open Science for Earth Observation Research

### Edzer Pebesma, Matthias Mohr

The open standards, open source geospatial and open science
communities still have a very limited answer to the question how
researchers active in applied domains such as agriculture, ecology,
hydrology, oceanography or land use planning can benefit from
the large amounts of open Earth Observation (EO) data currently
available. Solutions are very much tied to platforms operated and
controlled by big tech (Earth Engine, Planetary Computer), particular
programming languages, software stacks and/or file formats (xarray,
Pangeo, ODC, GeoPySpark/GeoTrellis). The openEO initiative provides
an API and a set of processes that separate the “what” from the
“how”: users specify what they want to compute, and back-end
processing engines decide how to do this. The openEO API is OpenAPI
compliant, and has client interfaces for Python, R, and JavaScript,
and in addition graphical user interfaces running in the browser
or in QGIS. The underlying data model is that of a data cube view:
image collections or vector data may be stored as they are, but are
analysed as if they were laid out as a raster or vector data cube,
e.g. for raster with dimensions x, y, band and time, or for vector
with dimensions geometry, band and time. Because openEO assumes that
imagery is described as STAC collections and the implementation is
composed of open source components, it is relatively easy to set it
up and compute on infrastructure where imagery is available through a
STAC interface. Having a single interface to carry out computations
on back-ends with different architecture makes it possible to
compare results across implementations, to verify that EO processing
is reproducible. So far, over 100 processes have been defined,
and user-defined functions written in Python or R extend this ad
infinitum. openEO was initially developed during a H2020 project
(2017-2020). It is currently continued with ESA funding that has
resulted in the “openEO Platform”, an implementation run by VITO
and EODC where the general public can use the openEO interface for
large scale computations. Several upcoming Horizon Europe projects
will further support continued development of the API and openEO
software ecosystem of clients and back-ends. Since the initiative
is designed to be an open science, all users and developers are
invited to engage. We will present the current state of the openEO
ecosystem and give an outlook to forthcoming developments.


