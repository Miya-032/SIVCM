Suggestion for Installing the R Package:

To ensure all dependencies are automatically installed, we recommend using the “devtools” or “remotes”package to install “SIVCMTest”. 
These tools will handle dependency management for you.

You can install the package and its dependencies by running the following code in R:
'''
### Install devtools or remotes if not already installed
install.packages("devtools")  # or install.packages("remotes")

### Install our package and its dependencies
devtools::install_github("username/repository")  # Replace with the repository details
# or
remotes::install_github("username/repository")
'''
This approach will automatically install all required dependencies listed in the DESCRIPTION file.