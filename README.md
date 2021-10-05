#Hello world docker

This action prints "Hello World" or "Hello"+ the name of person to greet

##Inputs

##'who-to-greet'
**Required** The name of the person to greet. Default '"World"'.

##Outputs

##'time'

The time we greeted you

## Example usage
user: actoin/hello-world-docker-actoin@v1
with:
    who-to-greet: 'Mona the Octocat'