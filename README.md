# hello-world
Just another repostory, doing it's thing.

Hi there private citizens (no robots please).

## Using the Jenkins file...
Simply follow the instructions here: https://jenkins.io/doc/book/blueocean/getting-started/ 

> To start a new Jenkins with Blue Ocean pre-installed:
> 1. Ensure Docker is installed.
> 2. Run docker run -p 8888:8080 jenkinsci/blueocean:latest
> 3. Browse to localhost:8888/blue

Once everything is set up, and you've got a nice Jenkins file in your repo, it may look like this:

![image](Jenkins%20BlueOcean%20pipeline%20example.PNG  "Jenkins BlueOcean pipeline example")

### Docker, Github, Jenkins BlueOcean, pipelines, etc.
So, if you've followed the instructions properly, even if your docker system crashes, since the pipeline is stored in Github (or whatever your repo is), getting things up and running is as trivial as re-creating the flow from the stored pipeline.

Very nice.
 
Having fun yet?
