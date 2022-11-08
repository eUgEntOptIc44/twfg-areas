# TWFG-Areas

A java script to create the [`areas.txt`](https://eugentoptic44.github.io/twfg-areas/areas.txt) file for [`Tiny Weather Forecast Germany`](https://codeberg.org/Starfish/TinyWeatherForecastGermany) using GeoJSON files provided by Deutscher Wetterdienst (DWD).

## areas.txt

The file contains the ['Warngebiete'](https://www.dwd.de/DE/wetter/warnungen/warnWetter_node.html) (warning areas/cells) used by the DWD when issuing weather warnings. Please see [https://tinyweatherforecastgermanygroup.gitlab.io/index/**areas.html**](https://tinyweatherforecastgermanygroup.gitlab.io/index/areas.html) for a searchable table of the contents.

**format:**

```
Geodata version: VERSION_NUMBER, DD.MM.YYYY
WARNCELL_ID@WARNCENTER@type@"NAME"@COORDINATES
...
```

## Copyright

The source code is based on the [Area-Generator](https://codeberg.org/Starfish/Area-Generator) (Apache 2.0 License) created by @Starfish (Pawel Dube).

**License**: please see `LICENSE` files

This project is **not affialited** with or officially approved by any of the following organizations: Alphabet, Codeberg, the DWD, Google, GitLab or GitHub or related individuals in any way. Named trademarks, brands and icons belong to their owners.

## Disclaimer

Only use the source code in this repository on your **own risk**. The source code published here is by no means production-ready and not intended to be used in critical or commercial environments. Your mileage might vary.

## Contributing

* All contributions to **Tiny Weather Forecast Germany** are managed at the ['main'](https://codeberg.org/Starfish/TinyWeatherForecastGermany) code repository at [codeberg.org](https://codeberg.org/Starfish/TinyWeatherForecastGermany)
* [**Translations**](https://translate.codeberg.org/engage/tiny-weather-forecast-germany/) are managed on the [**weblate** server](https://translate.codeberg.org/projects/tiny-weather-forecast-germany/) provided by Codeberg e.V.
* Feel free to contribute to this script by opening issues and/or merge requests.
* Please also see the automatically generated *javadoc* **code documentation** of Tiny Weather Forecast Germany [at GitLab](https://gitlab.com/tinyweatherforecastgermanygroup/twfg-javadoc).
* For cybersec, privacy and/or copyright related issues regarding this repository please directly contact the maintainer [**Jean-Luc Tibaux**](https://codeberg.org/eUgEntOptIc44).
