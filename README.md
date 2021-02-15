## Overview

A simple R script that fetches GPS coordinates of a given location using geocode.xyz and then reports the weather using data from Meteorologisk institutt in Norway (https://api.met.no/).

## Usage

The R package [jsonlite](https://cran.r-project.org/web/packages/jsonlite/) is required in order to parse JSON data. Other than that, just download the script and run it. For ease of use, bind it to an alias in your `.bashrc`, for instance `alias weather='Rscript ~/dotfiles/scripts/weather.R'` and then call it using `weather <City>` (e.g., `weather Stockholm`).

## Screenshots
