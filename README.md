# Docker cheat sheet
1.[Docker Commands, Help & Tips](https://gist.github.com/markkizz/93479b833732bbaac96a2a5d2e48be6d)  
2.[Dockerfile cheat sheet](https://www.evernote.com/shard/s415/sh/b28b420e-29cf-42b9-9fed-11d855b229dc/47f6765befd53b7231b2525704c9a699)

## Step to build image
- Create Dockerfile and Add instruction 
- Build image `docker build -t <tagname>/<image_name> .`
- Run image to container `docker run -itd -p <req_port>:<inside_container_port> --name <name>  <image_name or image_id> 


## How do i access to container
`docker exec -it <container_name> bash`
