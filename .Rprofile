# 1. Set default CRAN mirror (prevents interactive prompt errors in CI/CD)
options(repos = c(CRAN = "https://cloud.r-project.org"))

# 2. Activate renv automatically (if you are using renv for package management)
if (file.exists("renv/activate.R")) {
  source("renv/activate.R")
}

# 3. Custom message when opening the project locally
cat("Project loaded! cfbfastR workflow ready.\n")
