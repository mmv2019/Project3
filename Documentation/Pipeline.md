
# Pipeline process :
## orbs : 
- ###  node
- ###  eb 
- ###  aws-eb-cli
- ###  aws-cli

## Jobs :
 ### We have to jobs building and then deploying.
 - ### Bulid : run scripts to install dependencies and build files to upload it for both api and frontend.
 - ### Deploy: run scripts to trigger a shell file which runs the deploy script.
 
## Workflows :
### Simply we make the doply process runs after the build is done.