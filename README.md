# Saratoga weather forecast icons

These picture-style icons are based on the NOAA/NWS weather icons used by https://www.weather.gov/

They are used with the NWS-forecast (advforecast2.php), Wunderground-forecast (WC-forecast.php), and the WXSIM-forecast (plaintext-parser.php) scripts and should be installed in the ./forecast/images directory for use with the scripts on your site.  Doing an unzip and preserving directory structure in the document root of your site will place them in the correct locations for use.

The correct directory structure is:

```
./forecast
./forecast/images
./forecast/icon-templates
```
The [saratoga-icons2.zip](./saratoga-icons2.zip) set are 55x55px .jpg images.

The [saratoga-icons2-png-86x86.zip](saratoga-icons2-png-86x86.zip) are 86x86px .png images

The sets include base images, and selected images with PoP (probability of precipitation) numbers from 10% to 100% in increments of 10.   The ./forecast/icon-templates images are used (only) with the NWS-forecast script advforecast2.php and the associated DualImage.php script to dynamically create 6hr forecast conditions display on one 12hr icon.
