docker build -t demoapp .
docker run --rm -d -p 4200:4200 --name "Movies" demoapp
