
Covid-19 Vaccination project
 =====
 
Introduction and preparation
----

For my project, I will analyze the Covid-19 vaccination data across different countries. Exploratory analysis including summary statistics characterization and data visualization will be performed on the data.
To analyze the data,you would need `Xcode` and `R` version later than 4.0  `R` package 'renv' is required for R package management. All required `R` packages are within the renv file.

** Clone the project to local**
```
git clone https://github.com/tingyhu45/info550_hw4.git
```

** Install the `renv` package**

```R
## open the R session

if(!require(renv)){
  install.packages("renv")
  require(renv)
}
```

**Load the R environment**
```R
## open the R session
renv::restore()
```

```R
## If the required R packages are already availble in your R, then you just need activate the R environment
renv::activate()
```

Execute the analysis
------

You can run the command below under the project directory

```
make report
```

This will create a fill named Vacc_report.html in the same folder that contain the results, which can be open with:
```
open report.html
```

