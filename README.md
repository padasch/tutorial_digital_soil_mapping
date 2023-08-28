# Tutorial: Digital Soil Mapping

This is tutorial is part of the course Applied Geodata Science II taught at the University of Bern.
The material has been provided by Madlene Nussbaum and turned into this tutorial by Pascal Schneider.

## Setup

- Clone this repository
- Get the raw data (`soildata` and `geodata` folders) and put them under `./data-raw/`
- Install {renv} and install all required R packages when opening the `digital_soil_mapping.Rproj`

To render book locally in RStudio, run these commands in the console:

```r
renv::status()
renv::load()
renv::restore()
install.packages("quarto")
quarto::quarto_render("book")
```

Then open the file: `book/_book/index.html`