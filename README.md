# "building.map_1920"
Authors: [Ulrich Kral](https://orcid.org/0000-0002-2848-1673) and [Ferdinand Reimer](https://orcid.org/0000-0003-2515-4332)

**This GitHub repository refers** to the data repositories [Building age map, Vienna, around 1920](https://www.doi.org/10.5281/zenodo.3715200) and [Administrative boundaries, Vienna, various timestamps](https://doi.org/10.5281/zenodo.4323010). It is noted that the access to the data repositories is currently restricted, because a corresponding Data Descriptor is currently under review at [Nature Scientific Data](https://www.nature.com/sdata/). Once the Data Descriptor is published, there will be an open access and the following files can be used and re-used.

* **[Building age map, Vienna, around 1920](https://www.doi.org/10.5281/zenodo.3715200)**

1. Building stock map 1920 (BSM_1920.shp) and its attribute table (BSM_1920_attribute_table.csv)
2. Areas out of scope 1920 (AOOS_1920.shp)
3. Scope of analog building age map 1920 (SABAM_1920.shp)

* **[Administrative boundaries, Vienna, various timestamps](https://doi.org/10.5281/zenodo.4323010)**

1. City boundary 1920 (CB_1920.shp)
2. Urban district boundaries 1920 (UDB_1920.shp)
3. City boundary 2020 (CB_2020.shp)

**This GitHub repository provides** supplementary material as followed.

1. **Codebook**. The Codebook specifies the data format, the data fields and comments on the data fields of the datasets BSM_1920.shp and the attribute table BSM_1920_attribute_table.csv, CB_1920.shp and UDB_1920.shp. The Codebook also includes an interactive map with the location and geographical scope of the study area. The Codebook is available in a [readable online version](https://rpubs.com/ukral/699029) for end-users as well as [R Markdown file](Codebook.Rmd) for those who want to use and re-use the Codebook.

2. **Usage code**. The [R Markdown file](Usage_code.Rmd)  supplements the aforementioned Data Descriptor and enables the reproduction of figures and data.

3. **Background data**. The file [Background_data.xlsx](Background_data.xlsx) is a compilation of tables and datasets from various sources. The sheet "Content page" provides and overview, descriptions and references for the included data

**Instruction to execute the R Markdown files**

1. Download [R](https://www.r-project.org/) and install it on  your desktop.
2. Download [R-Studio](https://rstudio.com/) and install in on your desktop.
3. Download the data repositories [Building age map, Vienna, around 1920](https://www.doi.org/10.5281/zenodo.3715200) and [Administrative boundaries, Vienna, various timestamps](https://doi.org/10.5281/zenodo.4323010), unpack the sub-directories and save them to a local directory on your desktop (e.g. ../building.map_1920/02_Zenodo/).
4. Download the GitHub repository and save the files to a local directory on your desktop (e.g. ../building_map/01_Github/). Alternatively, you can connect R Studio to GitHub ([instructions](https://happygitwithr.com/rstudio-git-github.html)).
5. Open R-Studio and load the R project file "building.map_1920.Rproj" from from your local directory (e.g. ../building.map_1920/01_Github/).
6. Create a new directory to save the output files (e.g. ../building.map_1920/03_Output/)
7. Specify the path name of your local directory in the chunk "specify_inputs" of the R Markdown files "Codebook.Rmd" and "Usage_code.Rmd".
8. Execute the R Markdown files in R-Studio.
9. The R Markdown files can be fed to [bookdown](https://bookdown.org/) to generate a readable HTML file.
