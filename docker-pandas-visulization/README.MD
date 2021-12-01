# To build an Image and tag it
docker build -t alhaol/olympic . 

# Login to the docker hub
docker login 

# Push your images to the hub 
docker push alhaol/olympic

# Run a container to execute the app 
docker run alhaol/olympic



