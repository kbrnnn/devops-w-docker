# Start from the alpine image
FROM alpine:3.19

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

RUN apk update && apk upgrade && apk add curl

# Copy the script.sh to the WORKDIR

COPY script.sh .

#When running Docker run the script.sh ./script.sh

CMD ./script.sh
