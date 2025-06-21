### Provider Summary
- `geography_type`: Type of geography across which broadband data are summarized.
    - Value is one of the following:
        - National
        - State
        - County
        - Congressional District
        - Census Place
        - Tribal CBSA (MSA)
- `geography_id`: Unique geographic identifier for the identified geography.
- `geography_desc`: Short description of the identified geography.
- `geography_desc_full`: Full description of the identified geography.
- `data_type`: Type of data summarized in the record.
    - Value is one of the following:
        - Fixed Broadband
        - Mobile Broadband
- `provider_id`: Unique identifier for the service provider.
- `res_st_pct`: Calculated percentage of units for broadband serviceable locations
  contained within the geography for which providers report residential fixed broadband
  service (for fixed broadband) or percentage of area within the geography for which
  providers report mobile broadband service in an outdoor stationary environment (for mobile broadband).
- `bus_iv_pct`: Calculated percentage of units for broadband serviceable locations contained within the
  geography for which providers report business fixed broadband service (for fixed broadband) or
  percentage of area within the geography for which providers report mobile broadband service in an in-
  vehicle mobile environment (for mobile broadband).
### Fixed Broadband
- `area_data_type`: Type of area across which broadband data are summarized.
    - Value is one of the following:
        - Nontribal
        - Rural
        - Total
        - Tribal
        - Urban
- `geography_type`: Type of geography across which broadband data are summarized.
    - Value is one of the following:
        - National
        - State
        - County
        - Congressional District
        - Census Place
        - Tribal CBSA (MSA)
- `geography_id`: Unique geographic identifier for the identified geography.
- `geography_desc`: Short description of the identified geography.
- `geography_desc_full`: Full description of the identified geography.
- `total_units`: The total number of units in the geography. This is a sum of the units in all of the
  broadband serviceable locations, taken from the Broadband Serviceable Location Fabric, in the geography.
- `biz_res`: Enumerated character identifying whether the service available at the location is offered only to
  business customers, only to residential customers, or to both business and residential customers.
    - Value is one of the following codes:
        - B – Business-only location
        - R – Residential-only location
        - X – Business and Residential location
- `technology`: Technology used for the deployed service.
    - Value is one of the following:
        - Cable
        - Copper
        - Fiber
        - Geostationary Satellite
        - Non-geostationary Satellite
        - Licensed Fixed Wireless
        - Unlicensed Fixed Wireless
        - Other
        - All Cable or Fiber
        - All Fixed Wireless
        - All Satellite
        - All Terrestrial
        - All Wired
        - All Wired and Licensed Fixed Wireless
        - All Technologies
- `speed_02_02`: Calculated percentage of units for broadband serviceable locations contained within the geography
for which providers report fixed broadband service with speeds of at least 0.2 / 0.2 Mbps.
- `speed_10_1`: Calculated percentage of units for broadband serviceable locations contained within the geography
for which providers report fixed broadband service with speeds of at least 10 / 1 Mbps.
- `speed_25_3`: Calculated percentage of units for broadband serviceable locations contained within the geography
for which providers report fixed broadband service with speeds of at least 25 / 3 Mbps.
- `speed_100_20`: Calculated percentage of units for broadband serviceable locations contained within the geography
for which providers report fixed broadband service with speeds of at least 100 / 20 Mbps.
- `speed_250_25`: Calculated percentage of units for broadband serviceable locations contained within the geography
for which providers report fixed broadband service with speeds of at least 250 / 25 Mbps.
- `speed_1000_100`: Calculated percentage of units for broadband serviceable locations contained within the geography
for which providers report fixed broadband service with speeds of at least 1000 / 100 Mbps.

### Mobile Broadband
- `area_data_type`: Type of area across which broadband data are summarized.
    - Value is one of the following:
        - Nontribal
        - Rural
        - Total
        - Tribal
        - Urban
- `geography_type`: Type of geography across which broadband data are summarized.
    - Value is one of the following:
        - National
        - State
        - County
        - Congressional District
        - Census Place
        - Tribal CBSA (MSA
- `geography_id`: Unique geographic identifier for the identified Census Place.
- `geography_desc`: Short description of the identified geography.
- `geography_desc_full`: Full description of the identified geography.
- `total_area`: Area, in square kilometers, of the identified Census Place.
- `mobilebb_3g_area_st_pct`: Calculated percentage of area within the Census Place for which providers report 3G mobile broadband service in an outdoor stationary environment.
- `mobilebb_3g_area_iv_pct`: Calculated percentage of area within the Census Place for which providers report 3G mobile broadband service in an in-vehicle mobile environment.
- `mobilebb_4g_area_st_pct`: Calculated percentage of area within the Census Place for which providers report 4G LTE mobile broadband service in an outdoor stationary environment.
- `mobilebb_4g_area_iv_pct`: Calculated percentage of area within the Census Place for which providers report 4G LTE mobile broadband service in an in-vehicle mobile environment.
- `mobilebb_5g_spd1_area_st_pct`: Calculated percentage of area within the Census Place for which providers report 5G-NR mobile broadband service with speeds of at least 7 / 1 Mbps in an outdoor
stationary environment.
- `mobilebb_5g_spd1_area_iv_pct`: Calculated percentage of area within the Census Place for which providers report 5G-NR mobile broadband service with speeds of at least 7 / 1 Mbps in an in-vehicle
mobile environment.
- `mobilebb_5g_spd2_area_st_pct`: Calculated percentage of area within the Census Place or which providers report 5G-NR mobile broadband service with speeds of at least 35 / 3 Mbps in an outdoor
stationary environment.
- `mobilebb_5g_spd2_area_iv_pct`: Calculated percentage of area within the Census Place for which providers report 5G-NR mobile broadband service with speeds of at least 35 / 3 Mbps in an in-
vehicle mobile environment.







