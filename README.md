# "building.map_1920"
Authors: [Ulrich Kral](https://orcid.org/0000-0002-2848-1673) and [Ferdinand Reimer](https://orcid.org/0000-0003-2515-4332)


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3715200.svg)](https://doi.org/10.5281/zenodo.3715200)


**This GitHub repository refers** to the Zenodo repository [Map of Viennese building stock and its age in the 1920s](https://www.doi.org/10.5281/zenodo.3715200). It is noted that the access to the Zenodo repository is currently restricted, because a corresponding Data Descriptor is currently under review at [Nature Scientific Data](https://www.nature.com/sdata/). Once the Data Descriptor is published, there will be an open access and the following files can be used and re-used.

1. City boundary 1920 (CB_1920.shp)
2. Urban district boundaries 1920 (UDB_1920.shp)
3. Scope of analog building age map 1920 (SABAM_1920.shp)
4. Building stock and age 1920 (BSM_1920.shp) and its attribute tables (BSM_1920_attribute_table_final.csv and BSM_1920_attribute_table_temporary.csv)
5. City boundary 1920 (CB_2020.shp)
6. Areas out of scope 1920 (AOOS_1920.shp)

**This GitHub repository provides** supplementary material as followed.

1. **Codebook**. The Codebook specifies the data format of the aforementioned 4 files, the fields of the attribute tables and comments on the fields to facilitate data usage and interpretation. The Codebook also includes an interactive map with the location and geographical scope of the study area. The Codebook is available in a [readable online version](https://rpubs.com/ukral/699029) for end-users as well as [R-Code](Codebook.Rmd) for those who want to use and re-use the Codebook.

2. **Usage code**.The usage code supplements the aforementioned Data Descriptor and enables the reproduction of figures and data.

3. **Background data**. The file [Background_data.xlsx](Background_data.xlsx) is a compilation of tables and datasets from various sources. The sheet "Content page" provides and overview, descriptions and references for the included data

**Instruction to execute the R Markdown files**

1. Download [R](https://www.r-project.org/) and install it on  your desktop.
2. Download [R-Studio](https://rstudio.com/) and install in on your desktop.
3. Download the [Zenodo data repository](https://www.doi.org/10.5281/zenodo.3715200), unpack the files and save them to a local directory on your desktop (e.g. C:/building.map_1920/02_Zenodo/).
4. Download the GitHub repository and save the files to a local directory on your desktop (e.g. C:/building_map/Github/). Alternatively, you can connect R Studio to GitHub ([instructions](https://happygitwithr.com/rstudio-git-github.html)).
5. Open R-Studio and load the R project file "building.map_1920.Rproj" from from your local directory (e.g. C:/building.map_1920/01_Github/).
6. Create a new directory to cover the output files (e.g. C:/building.map_1920/03_Output/)
7. Specify the path name of your local directory in the chunk "specify_inputs" of the R Markdown files "Codebook.Rmd" and "Usage_code.Rmd".
8. Execute the R Markdown files in R-Studio.
9. The R Markdown files can be fed to [bookdown](https://bookdown.org/) to generate a readable HTML file.
