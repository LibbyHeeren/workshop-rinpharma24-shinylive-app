# Starter shinylive app for R/Pharma 2024

Steps to complete:

On personal machine, install pak and then:
* pak::pak("shinylive")
* shinylive::assets_ensure() # Will figure out if assets are installed and where
* shinylive::assets_info()

* Clone this repo to your personal GitHub
* Enable publishing of website through GitHub Actions
  * Settings > Pages > Build and Deployment > Source > GitHub Actions
* Set up auto exporting of app
  * ```r
    usethis::use_github_action(
      url = "https://github.com/posit-dev/r-shinylive/blob/actions-v1/examples/deploy-app.yaml"
    )
    ```
* View website
* ...
* Profit!
