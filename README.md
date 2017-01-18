# QGIS-SCP-Workshop
Lab การวิเคราะห์ข้อมูลภาพจากดาวเทียมด้วย QGIS

# โปรแกรมที่ใช้งาน
1. QGIS version 2.6.1 (เพราะคลิกขวา properties เร็วดี)
2. ปลั๊กอิน Semi-Automatic Classification Plugin (SCP) https://plugins.qgis.org/plugins/SemiAutomaticClassificationPlugin/

# ข้อมูลที่ใช้งาน
1. ข้อมูลภาพ Landsat 8
2. etc.

## Landsat 8 Bands | Wavelength [micrometers] | Resolution [meters]
  - Band 1 | Coastal aerosol | 0.43 - 0.45	30
  - Band 2 | Blue | 0.45 - 0.51	30
  - Band 3 | Green | 0.53 - 0.59	30
  - Band 4 | Red	0.64 - 0.67	30
  - Band 5 | Near Infrared (NIR) | 0.85 - 0.88	30
  - Band 6 - SWIR 1	1.57 - 1.65	30
  - Band 7 - SWIR 2	2.11 - 2.29	30
  - Band 8 - Panchromatic	0.50 - 0.68	15
  - Band 9 - Cirrus	1.36 - 1.38	30
  - Band 10 - Thermal Infrared (TIRS) 1	10.60 - 11.19	100 (resampled to 30)
  - Band 11 - Thermal Infrared (TIRS) 2	11.50 - 12.51	100 (resampled to 30)
  - The resolutions of Landsat 8 sensor are reported in the following table (from http://landsat.usgs.gov/band_designations_landsat_satellites.php); also, Landsat temporal resolution is 16 days (NASA, 2013).
  
# References
  - https://plugins.qgis.org/plugins/SemiAutomaticClassificationPlugin/
  - https://fromgistors.blogspot.com/
