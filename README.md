# dockerdemo

#Dockerfile

docker build -f Dockerfile -t testimage .
docker run testimage


#Dockerfile.cmd

docker build -f Dockerfile.cmd -t testimage .

docker run testimage
docker run testimage echo "Bye Bye everyone"

#Dockerfile.ep

docker build -f Dockerfile.ep -t testimage .
docker run testimage
docker run testimage vimal


