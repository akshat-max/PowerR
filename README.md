# PowerR
**R** package implementing a workflow for GitHub Actions using [r-lib/actions](https://github.com/r-lib/actions).


## Build and Installation


### Windows
```sh
Rscript.exe -e 'devtools::install_github("akshat-max/powerR")'
```

## GitHub Actions Workflow
- Checks for a successful build on Windows. </br>
  **Using:**
    - r-lib/actions/setup
    - r-lib/actions/setup-r-dependencies
- Checks for a errors in the R package. </br>
  **Using:**
    - r-lib/actions/check-r-package


Examples for this package can be located in the [example]() directory. 
