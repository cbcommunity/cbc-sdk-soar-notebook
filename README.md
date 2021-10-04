# CBC SDK SOAR Notebook

## Overview
This is a Jupyter iPython Notebook with a series of examples on how to use the [VMware Carbon Black CBC SDK](https://github.com/carbonblack/carbon-black-cloud-sdk-python) in SOAR workflows.

## Usage
This notebook can be imported into any Jupyter utility. It was written and developed using [Google's Colab](https://colab.research.google.com/) tool and has been tested in [Microsoft's VSCode IDE](https://code.visualstudio.com/docs/datascience/jupyter-notebooks). See those links for more information on how to run Jupyter Notebooks in the respective tools.

To use the Notebook in your tool of choice, download the [VMware_Carbon_Black_Cloud_SDK_with_SOAR.ipynb](https://github.com/cbcommunity/cbc-sdk-soar-notebook/blob/main/VMware_Carbon_Black_Cloud_SDK_with_SOAR.ipynb) file and import it into your tool. Execute (Shift+Enter) the first two cells to import the CBC SDK and define required variables.

Each section has a list of the Access Level (RBAC) required for the API endpoint and a link to that endpoints API documentation, as well as a link to the ReadTheDocs documentation for the SDK.

## Content
As mentioned above, the first two blocks are to install and initialize the CBC SDK. All blocks following these rely on these two blocks being run first.  
 
The main content in the Notebook is broken down into subcategories:  
- **SOAR Actions: Context** - These are examples of getting context from CBC
- **SOAR Actions: Remediation** - These are examples of taking remediation actions in CBC
- **SOAR Actions: Orchestration** - These are examples of actions that can be taken to orchestrate workflows

In addition there are 3 sample workflows at the bottom of the file
- **End-to-end: Watchlist Alert Triage** - An example showing how to use the CBC SDK to triage a Watchlist alert
- **End-to-end: Malware** - An example showing how to identify malware alerts and identify if the process is still running on the endpoint
- **End-to-end: Credential Scraping** - An example showing how to identify credentail scraping and how to use Audit & Remediation to identify who was logged in at the time

## Support
This is a community supported project. Please open an issue in this repo with any bugs or suggestions.
