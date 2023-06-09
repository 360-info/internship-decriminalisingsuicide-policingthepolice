# [ETC5543 - Business analytics creative activity - S1 2023]

[The first package, **'Decriminalizing Suicide'** focuses on various aspects covered by the authors, one of them is 'India's Mental Health Act 2017' and opposite results are observed due to different data sources, an increase and decrease after 2017, which is discussed in the report. The second package, **'Policing he Police'** takes a generic angle, covering topics of shootings around the world, the changing trust in police and much more. The project uses methods of data wrangling, exploration, pdf scraping, spatial analysis and basics of functions of tidyverse, in R language and uses 'themes360info' package for the theme.]

## Use + Remix rights

![[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0)](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)

These charts, as well as the analyses that underpin them, are available under a Creative Commons Attribution 4.0 licence. This includes commercial reuse and derivates.

<!-- Do any of the data sources fall under a different licence? If so, describe the licence and which parts of the data fall under it here! if most of it does, change the above and replace LICENCE.md too -->

Data in these charts comes from:

* [https://ourworldindata.org/suicide,
http://hdr.undp.org/en/composite/HDI,
http://hdr.undp.org/en/composite/HDI,
https://www.who.int/data/gho/data/themes/mental-health/suicide-rates,
https://data.gov.in/catalog/stateut-wise-distribution-suicides-causes,
http://www.diva-gis.org/datadown,
https://ncrb.gov.in/sites/default/files/adsi_reports_previous_year/Table%202.1.pdf),
https://dataunodc.un.org/dp-crime-corruption-offences,
https://www.washingtonpost.com/graphics/investigations/police-shootings-database/,
https://github.com/washingtonpost/data-police-shootings/tree/master/v1,
https://www2.census.gov/programs-surveys/popest/datasets/2010-2020/counties/totals,
https://www2.census.gov/programs-surveys/popest/datasets/2020-2022/counties/totals,
https://github.com/jasonong/List-of-US-States/blob/master/states.csv,
https://ncrb.gov.in/en/crime-in-india-table-addtional-table-and-chapter-contents?page=21,
https://ourworldindata.org/grapher/trust-in-others-vs-trust-in-police,
https://data.world/stabile-center/ph-drug-war#,
https://ourworldindata.org/corruption]

**Please attribute 360info and the data sources when you use and remix these visualisations.**

## Reproduce the analysis

### 💨 Quickstart: use the dev container

This project comes with a ready-to-use [dev container](https://code.visualstudio.com/docs/remote/containers) that includes everything you need to reproduce the analysis (or do a similar one of your own!), including [R](https://r-project.org) and [Quarto](https://quarto.org).

1. [Launch this project in GitHub Codespaces](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=[report_codespaces_id])
2. If you have Docker installed, you can build and run the container locally:
  - Download or clone the project
  - Open it in [Visual Studio Code](https://code.visualstudio.com)
  - Run the **Remote-Containers: Reopen in Container** command

Once the container has launched (it might take a few minutes to set up the first time), you can run the analysis scripts with:

```sh
quarto render
```

Or look for the `.qmd` files to modify the analysis.

### Manual setup

To setup a development environment manually, 

You'll need to:
- [Download and install Quarto](https://quarto.org/docs/get-started)
- [Download the install R](https://www.r-project.org)
- Satisfy the R package dependencies. In R:
  * Install the [`renv`](https://rstudio.github.io/renv) package with `install.packages("renv")`,
  * Then run `renv::restore()` to install the R package dependencies.
  * (For problems satisfying R package dependencies, refer to [Quarto's documentation on virtual environments](https://quarto.org/docs/projects/virtual-environments.html).)

Now, render the `.qmd` files to the `/out` directory with:

```sh
quarto render
```

## Help

If you find any problems with our analysis or charts, please feel free to [create an issue](https://github.com/360-info/[report repo name]/issues/new)!
