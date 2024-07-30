docker ps -a See all containers that are made and there statuses

Docker images "See what images are on your system"

docker inspect "container to see detailed info of it"

docker pull "image of container'

docker run -it "interactive" --name="Name of container" mcr.microsoft.com/windows:ltsc2019 cmd "Open in CMD"

docker run -d "Detacthed" -p 8000:8000 "declare port to connect too"

docker run -it -v C:\Users\bburgess\:c:\host --name="servercore_ltsc2019" mcr.microsoft.com/windows/servercore:ltsc2019 cmd

-it "interactive"

-v C:\Users\bburgess\:c:\host "Share host file to C drive on container inside dirctory called host"

--name="Name of container"

mcr.microsoft.com/windows/servercore:ltsc2019 "image used"

cmd "Open in CMD"

docker build -t 