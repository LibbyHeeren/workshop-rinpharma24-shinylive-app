# Starter app for R/Pharma 2024

Steps to complete:
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
