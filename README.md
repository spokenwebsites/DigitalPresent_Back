# Steps to install the strapi application

1. Install a default strapi project
yarn create strapi-app <Enter name for local file here Eg: movie-strapi>
  - choose PostgresSQL as the database
  [If yarn doesn't work, tr using npm - npx create-strapi-app@latest <Enter name for local file here Eg: movie-strapi>]
  
2. Clone the git repository and copy its contents into the strapi project that's just been created. (If there are any conflicts between a default file and a file in the git repo, choose the file in the git repo)
  
3. cd into the project repository
  
4. Enter the command to run strapi
  npm run develop
  
5. The admin panel should open up. Create/Enter any username and password. (I haven't enabled any security yet)
  
# Steps to migrate data into the postgresSQL database - [Subject to change soon]
  
1. In the root folder, there should be a folder named .tmp, cd into it
  
2. There should be a database file (.db) with the postgresSQL database information stored in it. This is where strapi is going to pull information from. If we wish to change the information stored in strapi (and thus displayed on the dashboard on the frontend), this is the file that needs to be changed
  
3. To update the .db file with the latest information from SWALLOW, download the latest SWALLOW .json file and open it in the PostgresSQL application. 

4. Download the data from postgres in a .db format and put it in the .tmp folder 
  
Additional Documentation:
1. Strapi - https://docs.strapi.io/developer-docs/latest/setup-deployment-guides/installation/cli.html#creating-a-strapi-project
2. PostgresSQL - https://www.postgresql.org/download/
  
 
