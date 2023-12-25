# Overview

Sample HTTP Hello World project with automatic image build and push to GitHub repository. 

# Run this sample

1. In the root directory run this command in the command line
```shell
docker run --rm -p 8888:80 $(docker build -q .)
```
2. Open browser with url http://localhost:8888
3. CTRL+C to exit
