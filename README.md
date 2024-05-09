# Datum Spreadsheets

Excel spreadsheets to assist with:
- transformation of spatial data between geodetic datums (e.g. GDA94 to GDA2020)
- conversion of coordinate systems (e.g. Geographic (lat, lon) to Cartesian),
- projection of data to a map grid
- common geodetic computations (e.g. azimuths, distances)

Detailed information about these spreadsheets and the geodetic operations they support is contained in the Geocentric Datum of Australia 2020 Technical Manual www.icsm.gov.au.
More general explanations of the concepts and terminology are available at the ICSM Fundamentals of mapping site  www.icsm.gov.au/mapping/index.html.

__________________________________

### Coordinate Transformations

- [Transformation_Conversion.xlsx](https://github.com/icsm-au/DatumSpreadsheets/raw/master/Transformation_Conversion.xlsx) - 7-parameter similarity transformation and coordinate conversion between Cartesian and Geographic coordinate systems.
  
__________________________________

### Coordinate Conversions

- [Krueger n-series.xlsx](https://github.com/icsm-au/DatumSpreadsheets/raw/master/Krueger%20n-series.xlsx): Geographic to Grid and Grid to Geographic (recommended for working outside beyond a single MGA / UTM zone).
- [Krueger lambda series.xlsx](https://github.com/icsm-au/DatumSpreadsheets/raw/master/Krueger%20lambda%20series.xlsx): also known as Redfearn's equations. Accurate within a single MGA / UTM zone.
- [Transformation_Conversion.xlsx](https://github.com/icsm-au/DatumSpreadsheets/raw/master/Transformation_Conversion.xlsx): 7-parameter similarity transformation and coordinate conversion between Cartesian and Geographic coordinate systems.

__________________________________

### Ellipsoid Computations 
- [Vincentys.xlsx](https://github.com/icsm-au/DatumSpreadsheets/raw/master/Vincentys.xlsx): Direct and Indirect methods to calculate accurate geodetic positions, azimuths and distances on the ellipsoid.
  
__________________________________

### Grid Calculations 

- [GridCalc_GDA2020_NSW.zip](https://github.com/icsm-au/DatumSpreadsheets/raw/master/GridCalc_GDA2020_NSW.zip): contains GridCalc_GDA2020_NSW.xlsm (macro enabled spreadsheet) and GridCalc_GDA2020_NSW_UG.pdf (user guide).

  GridCalc_GDA2020_NSW.xlsm provides output of various geodetic quantities between two points given input of the MGA2020 co-ordinates,
  AHD values and MGA zone of two points within New South Wales.
  
- [GridCalc_GDA94_NSW.zip](https://github.com/icsm-au/DatumSpreadsheets/raw/master/GridCalc_GDA94_NSW.zip): contains GridCalc_GDA94_NSW.xlsm (macro enabled spreadsheet) and GridCalc_GDA94_NSW_UG.pdf (user guide).

  GridCalc_GDA94_NSW.xlsm provides output of various geodetic quantities between two points given input of the MGA94 co-ordinates,
  AHD values and MGA zone of two points within New South Wales.
  
__________________________________
