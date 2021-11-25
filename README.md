# labkey web-app with postgresql and pgadmin4

- Step 1: Pull the images: *shoaibb/labkey:21.7*  ,  *shoaibb/postgresql:12.8*  and *shoaibb/pgadmin4:5.6*
  - docker pull shoaibb/labkey:21.7
  - docker pull shoaibb/postgresql:12.8
  - docker pull shoaibb/pgadmin4:5.6
- Step 2: Save **docker-compose.yml** file from this repo.
- Step 3: Create the following 3 folders (in the same dir where **docker-compose.yml** is stored)
  - files_store
  - pgadmin_data
  - db_data
- Step 4: Run the command on the pgadmin_data dir:  **sudo chown -R 5050:5050 pgadmin_data**
- Step 5: Run **docker-compose up** command (inside the dir where **docker-compose.yml** is stored) 
  
