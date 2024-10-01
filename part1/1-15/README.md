This container is the appliction provided by the full-stack-open course, available here: 
https://fullstackopen.com/en/part11/introduction_to_ci_cd
https://github.com/fullstack-hy2020/full-stack-open-pokedex

When running, it provides an accessible database of the first pokemon cards released.

### To run:

The application runs on port 5000.

Simply pull the container, and 

'''
docker run -d -p 127.0.0.1:5000:5000 fullstack-pokedex
'''

To map your localhost:5000 to the application in the container, on port 5000.

Open localhost:5000 and you should see the pokemon images load.