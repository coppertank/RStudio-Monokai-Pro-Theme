# RStudio-Monokai-Pro-Theme

RStudio Theme based on [Monokai Pro](https://monokai.pro/) color scheme for VScode

![Monokai Pro](https://github.com/coppertank/RStudio-Monokai-Pro-Theme/blob/main/img/Monokai-Pro-Preview.png)

### Dark style also across New Project Wizard (and other panels)

![New Project Wizard](https://github.com/coppertank/RStudio-Monokai-Pro-Theme/blob/main/img/New-project-wizard.png)

## Installation

Download the folder, unzip and open RStudio. Go to **Tools** \> **Global Options** \> **Appearance** \> **Add**, and then navigate to the `.rstheme` file path. Click apply.

Otherwise, you can copy the following into your console (requires [Devtools](https://cran.r-project.org/web/packages/devtools/index.html)):

``` r
rstudioapi::addTheme("https://raw.githubusercontent.com/coppertank/RStudio-Monokai-Pro-Theme/refs/heads/main/Monokai%20Pro.rstheme", apply = TRUE)
```

## Acknowledgements

-   This theme was heavily inspired by [RStudio Material Theme](https://github.com/lusignan/RStudio-Material-Theme)
-   Sample code comes from [Tidy Modeling with R](https://www.tmwr.org/)