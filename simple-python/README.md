## Notes
All Commands are from the root directory of this project

### Building The Docker Image
The following will build the image defined in the dockerfile with t
The name "python" and the tag (version) "0.0.1"
The . at the end defines where to find the dockerfile
`docker image build -t python:0.0.1 .`

### Seeing All Images
`docker images`

### Run The Image
`docker run python:0.0.1`