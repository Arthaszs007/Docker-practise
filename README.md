Challenge 1:
Command used:
docker build -t challenge1: create the image on docker challenge1 is name
docker run -d -p 8080:80 challenge1: mapping the 8080 to 80 port, and run it and can visit 8080

Challenge 2:
Command used:
docker build -t challenge1: create the image on docker challenge1 is name
docker images: list the images info, get the image’s id 
docker run -d -p 8080:3000 4fe3c94bb139: mapping the 8080 to 3000 port and run the server, and can visit 8080, 4fe3c94bb139 is the image ID, I got info from “docker images”
