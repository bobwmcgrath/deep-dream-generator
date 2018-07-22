# deep-dream-generator docker



run the container with

	sudo docker run -d -p 443:8888 -e "PASSWORD=password" -v /home/user/docker:/src ryankennedyio/deepdream

This will link a folder /home/user/docker into a folder /src inside of the docker container.

Then head to https://127.0.0.1:443, enter 'password' and start playing. 

stop all dockers with

	sudo docker stop $(sudo docker ps -a -q)
