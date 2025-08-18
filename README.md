# gdhy

<!-- badges: start -->
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
[![OSF DOI](https://img.shields.io/badge/OSF-10.17605/OSF.IO/TNFGU-1284C5.svg)](https://doi.org/10.17605/OSF.IO/TNFGU)
[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![License: CC0-1.0](https://img.shields.io/badge/license-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
<!-- badges: end -->

## Overview

This repository contains a reproducible pipeline for processing the *Global Dataset of Historical Yield* ([Iizumi, 2019](https://doi.pangaea.de/10.1594/PANGAEA.909132); [Iizumi & Sakai, 2020](https://doi.org/10.1038/s41597-020-0433-7)) in [R](https://www.r-project.org/).

You can access the pipeline [here](https://sustentarea.github.io/gdhy/).

## Data Availability

[![OSF DOI](https://img.shields.io/badge/OSF-10.17605/OSF.IO/TNFGU-1284C5.svg)](https://doi.org/10.17605/OSF.IO/TNFGU)

The processed data are available in the `rds` format via a dedicated repository on the Open Science Framework ([OSF](https://osf.io/)), accessible [here](https://doi.org/10.17605/OSF.IO/TNFGU). You can also access these files directly from R using the [`osfr`](https://docs.ropensci.org/osfr/) package.

## How to Use

The pipeline is fully reproducible. It was developed using the [Quarto](https://quarto.org/) publishing system and the [R programming language](https://www.r-project.org/). To ensure consistent results, the [`renv`](https://rstudio.github.io/renv/) package is used to manage and restore the R environment.

After installing the three dependencies mentioned above, follow these steps to reproduce the analyses:

1. **Clone** this repository to your local machine.
2. **Open** the project in your preferred IDE.
3. **Restore the R environment** by running [`renv::restore()`](https://rstudio.github.io/renv/reference/restore.html) in the R console. This will install all required software dependencies.
4. **Open** `index.qmd` and run the code as described in the report.

## How to Cite

> [!IMPORTANT]
> When using this data, you must also cite the original data sources.

To cite this work, please use the following format:

Vartanian, D., & Carvalho, A. M. (2025). *A reproducible pipeline for processing the Global Dataset of Historical Yields (1981–2016) by Iizumi et al.* \[Computer software\]. Sustentarea Research and Extension Group of the University of São Paulo. <https://sustentarea.github.io/gdhy>

A BibTeX entry for LaTeX users is

```
@misc{vartanian2025,
  title = {A reproducible pipeline for processing the Global Dataset of Historical Yields (1981–2016) by Iizumi et al.},
  author = {{Daniel Vartanian} and {Aline Martins de Carvalho}},
  year = {2025},
  address = {São Paulo},
  institution = {Sustentarea Research and Extension Group of the University of São Paulo},
  langid = {en},
  url = {https://sustentarea.github.io/gdhy}
}
```

## License

[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

> [!IMPORTANT]
> The original data sources may have their own license terms and conditions.

The code in this repository is licensed under the [GNU General Public License Version 3](https://www.gnu.org/licenses/gpl-3.0), while the report is available under the [Creative Commons CC0 License](https://creativecommons.org/public-domain/cc0/).

``` text
Copyright (C) 2025 Daniel Vartanian

The code in this repository is free software: you can redistribute it and/or
modify it under the terms of the GNU General Public License as published by the
Free Software Foundation, either version 3 of the License, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <https://www.gnu.org/licenses/>.
```

## Acknowledgments

<table>
  <tr>
    <td width="30%">
      <br/>
      <br/>
      <p align="center">
        <a href="https://www.fsp.usp.br/sustentarea/">
          <img src="images/sustentarea-logo.svg" width="125"/>
        </a>
      </p>
      <br/>
    </td>
    <td width="70%">
      <p>
        This work was developed with support from the
        <a href="https://www.fsp.usp.br/sustentarea/">Sustentarea</a>
         Research and Extension Center of the University of São Paulo (<a href="https://www5.usp.br/">USP</a>).
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="30%">
      <br/>
      <p align="center">
        <a href="https://www.gov.br/cnpq/">
          <img src="images/cnpq-logo.svg" width="150"/>
        </a>
      </p>
      <br/>
    </td>
    <td width="70%">
      <p>
        This work was supported by the Department of Science and
        Technology of the Secretariat of Science, Technology, and Innovation
        and of the Health Economic-Industrial Complex (<a href="https://www.gov.br/saude/pt-br/composicao/sectics/">SECTICS</a>)  of the <a href="https://www.gov.br/saude/pt-br/composicao/sectics/">Ministry of Health</a>
        of Brazil, and the National Council for Scientific and
        Technological Development (<a href="https://www.gov.br/cnpq/">CNPq</a>) (grant no. 444588/2023-0).
      </p>
    </td>
  </tr>
</table>
