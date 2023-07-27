# Tutorial: Digital Soil Mapping

This is tutorial is part of the course Applied Geodata Science II taught at the University of Bern.
The material has been provided by Madlene Nussbaum and written-up by Pascal Schneider.

## Setup

- Clone this repository
- Get the raw data (`soildata` and `geodata` folders) and put them under `./data-raw/`
- Install {renv} and install all required R packages when opening the `digital_soil_mapping.Rproj`


To render book locally in RStudio:

```r
quarto::quarto_render(input = "book")
```

To render book locally via terminal (requires quarto):

```bash
$ cd book
$ quarto render
```
