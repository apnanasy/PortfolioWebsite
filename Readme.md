BUILDING and DEPLOYING

Use docker to build the dockerfile While in the directory containing the dockerfile run: $docker build -t {namewanted} .

then run $docker run --name {imagename} -p 80:80 -d {namewanted}
