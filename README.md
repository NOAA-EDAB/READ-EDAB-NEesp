<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![](https://img.shields.io/badge/devel%20version-0.1.1-blue.svg)](https://github.com/NEFSC/READ-EDAB-NEesp)
[![](https://img.shields.io/github/last-commit/NEFSC/READ-EDAB-NEesp.svg)](https://github.com/NEFSC/READ-EDAB-NEesp/commits/main)
[![](https://img.shields.io/badge/repo%20size-1.37%20GB-blue.svg)](https://github.com/NEFSC/READ-EDAB-NEesp)
[![](https://github.com/NEFSC/READ-EDAB-NEesp/workflows/gitleaks/badge.svg)](https://github.com/NEFSC/READ-EDAB-NEesp/actions/workflows/secretScan.yml)
<!-- badges: end -->

# Ecosystem and Socioeconomic Profiles <img src="https://raw.githubusercontent.com/NOAA-EDAB/esp_data_aggregation/abby/hexes/NEesp_hex.png" align="right" width="120" />

## View current data products

<https://nefsc.github.io/READ-EDAB-ESP_docs/docs>

## Introduction

Ecosystem and Socioeconomic Profiles (ESPs) are a scientific product to
support [Integrated Ecosystem
Assessment](https://www.integratedecosystemassessment.noaa.gov/) (IEA).
IEA seeks to improve understanding and management of fisheries through
incorporating natural, social, and economic data into fisheries analyses
and management plans. ESPs are a structured framework developed by the
Alaska Science Center to integrate ecosystem and socioeconomic
information into the stock assessment
process.<sup>[1](https://meetings.npfmc.org/CommentReview/DownloadFile?p=8f5233fb-3b62-4571-9b49-8bb7ce675916.pdf&fileName=ESP_Shotwell.pdf)</sup>

Here we adapt the ESP process for use in the management of Northeast
stocks. Our scientific roadmap consists of these steps:

1.  Gather existing data on ecology, biology, socioeconomics, and the
    human dimension of Northeast fisheries.

2.  Conduct a risk analysis of Northeast stocks to determine which
    stocks are most vulnerable.

3.  Create detailed reports for the most vulnerable stocks,
    incorporating data from the original risk assessment as well as
    detailed species-specific information.

## Using this package

The current preliminary report pulls data from many existing sources and
creates several data visualizations. Reports for all northeast stocks
have been compiled and can be viewed
[here](https://nefsc.github.io/READ-EDAB-ESP_docs/docs). Data,
functions, and report templates are aggregated in this R package,
[`NEesp`](https://github.com/NEFSC/READ-EDAB-NEesp). See
[here](https://nefsc.github.io/READ-EDAB-NEesp/articles/install-and-use-package.html)
for a brief demo of how to use this package.

These reports are a work in progress and should not be viewed as a final
or complete product at this time. We do not guarantee that these reports
are free from errors; please contact us if you notice any issues.

## The Northeast ESP suite

There are currently 4 github repos associated with the Northeast ESP
initiative.

1.  [`NOAA-EDAB/esp_data_aggregation`](https://github.com/NOAA-EDAB/esp_data_aggregation)
    is the original repo and currently houses development and
    exploratory work.

2.  [`NEFSC/READ-EDAB-NEesp`](https://github.com/NEFSC/READ-EDAB-NEesp)
    houses an R package that contains relevant data, functions for
    low-level data analysis and plotting, and report templates.

3.  [`NEFSC/READ-EDAB-NEespShiny`](https://github.com/NOAA-EDAB/NEespShiny)
    houses an R Shiny app (in the form of an R package) that provides a
    graphical user interface for creating reports with the `NEesp`
    package.

4.  [`NEFSC/READ-EDAB-ESP_docs`](https://github.com/NOAA-EDAB/ESP_docs)
    houses static reports on Northeast stocks and
    ecosystem/socioeconomic indicators.

## Next steps

We continue to synthesize existing data on Northeast stocks,
environment, and socioeconomics. We are currently refining our data
analyses and beginning the preliminary risk assessment process.

## Developers

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><a href="https://github.com/atyrell3">atyrell3</a></th>
<th><a href="https://github.com/stephanie-owen">stephanie-owen</a></th>
<th><a href="https://github.com/rtabandera">rtabandera</a></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://github.com/atyrell3"><img
src="https://avatars.githubusercontent.com/u/77738923?s=100&amp;u=92e54f60ca179f3e41c1a3610fb3ecdb9e233434&amp;v=4" /></a></td>
<td><a href="https://github.com/stephanie-owen"><img
src="https://avatars.githubusercontent.com/u/144704736?v=4" /></a></td>
<td><a href="https://github.com/rtabandera"><img
src="https://avatars.githubusercontent.com/u/64960823?s=100&amp;u=ea5abeca602e43d461e964fe8283f703aef63c61&amp;v=4" /></a></td>
</tr>
</tbody>
</table>

#### Legal disclaimer

*This repository is a scientific product and is not official
communication of the National Oceanic and Atmospheric Administration, or
the United States Department of Commerce. All NOAA GitHub project code
is provided on an ‘as is’ basis and the user assumes responsibility for
its use. Any claims against the Department of Commerce or Department of
Commerce bureaus stemming from the use of this GitHub project will be
governed by all applicable Federal law. Any reference to specific
commercial products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of Commerce.
The Department of Commerce seal and logo, or the seal and logo of a DOC
bureau, shall not be used in any manner to imply endorsement of any
commercial product or activity by DOC or the United States Government.*

#### Pkgdown site

The pkgdown site is being built from the `dev` branch.
