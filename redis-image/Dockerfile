#use an exitsitng doxker image as a base
FROM alpine 

#download and install a dependency
RUN apk add --update redis 

#tell the image waht to do when it starts
#as a container
CMD ["redis-server"]

