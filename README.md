# grafana-github-explorer
This repository provides configuration files to set up a Grafana instance that leverages a GitHub data source

## Requirements
- Docker

### Setup:
- Create .env file in the root directory with the following environment variables:

  + **GRAFANA_USERNAME:** Username for Grafana access
  + **GRAFANA_PASSWORD:** Password for Grafana access
  + **DATASOURCES_GITHUB_TOKEN:** Your GitHub Personal Access Token

- Run the following command in your terminal:
docker-compose up -d 

### Access:

- URL: http://localhost:3000
- Credentials: Use the username and password from your .env file.

## Usage:
- Log in to Grafana.
- Navigate to Data Sources menu.
- Select the 'GitHub-WannaTokenAbi' data source and click 'Test'.
- Import the GitHub Default Dashboard:
    + Go to the 'Dashboards' tab (beside the Settings tab).
    + Click 'Import' button associated with 'GitHub Default'.
- Navigate to the main Dashboards menu.
    + Select 'GitHub Default' from the dashboard list.
- Configure the Dashboard:
    + To load your repository details, confirm the datasource and change the Organization to <your_github_username>.

+ _Enjoy :)_
    

## Screenshot 
![Untitled](https://github.com/user-attachments/assets/c3f9f7d2-dd2c-423a-a35f-b1440810d8c2)


### Contribution:
Feel free to fork this repository and contribute your own configurations or improvements.
