# grafana-github-explorer
This repository provides configuration files to set up a Grafana instance that leverages a GitHub data source

## Requirements
- Docker

### Setup:
- Create a .env file in the root directory (not tracked in Git) with the following environment variables:

  + **GRAFANA_USERNAME:** Username for Grafana access
  + **GRAFANA_PASSWORD:** Password for Grafana access
  + **DATASOURCES_GITHUB_TOKEN:** Your GitHub Personal Access Token

- Run the following command in your terminal:
docker-compose up -d 

### Access:

- URL: http://localhost:3000 (port mapping might vary)
- Credentials: Use the username and password from your .env file.

## Usage:
- Log in to Grafana.
- Navigate to Data Sources
- Select the GitHub Data Source: Click the 'GitHub-WannaTokenAbi' data source and click 'Test'.
- Import the GitHub Default Dashboard:
    + Go to the Dashboards tab (beside the Settings tab).
    + Click 'Import' button associated with 'GitHub Default'.
- Navigate to the main Dashboards menu.
    + Select 'GitHub Default' from the dashboard list.
- Configure the Dashboard:
    + Load your repository details, confirm the datasource and change the Organization to <your_github_username>.

+ _Enjoy :)_
    

### Contribution:
Feel free to fork this repository and contribute your own configurations or improvements.