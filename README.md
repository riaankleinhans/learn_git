# Post-Quantum Cryptography Alliance Landscape

This repository contains the data files and images required to generate the [PQCA landscape](https://pqca.landscape2.io). The software that generates it can be found at the [cncf/landscape2](https://github.com/cncf/landscape2) repository. Please see its [README file](https://github.com/cncf/landscape2#landscape2) for more information about how it works.

## New entries

To add a new entry to the landscape, please open a pull request to add it in alphabetical order to the [landscape.yml](landscape.yml) file. The logo must be added to the `hosted_logos` directory (in SVG format) and referenced from the `logo` field.

> [!NOTE]
> At the moment the landscape is generated daily, so once your PR is merged your changes should be visible before 24 hours.

## Corrections

If you find an error in the landscape, please open a pull request with the suggested changes to the [landscape.yml](landscape.yml) file. Some information displayed in the landscape is obtained from Crunchbase or GitHub, so errors on it should be fixed in the corresponding source.

## License

The generated landscape contains data received from [Crunchbase](http://www.crunchbase.com). This data is not licensed pursuant to the Apache License. It is subject to Crunchbase’s Data Access Terms, available at [https://data.crunchbase.com/docs/terms](https://data.crunchbase.com/docs/terms), and is only permitted to be used with Linux Foundation landscape projects.

Everything else is under the Apache License, Version 2.0, except for projects and products logos, which are generally copyrighted by the company that created them, and are simply cached here for reliability. The generated landscape and the [landscape.yml](landscape.yml) file are alternatively available under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).
