# deep-dream-generator docker



run the container with

	sudo docker run -d -p 443:8888 -e "PASSWORD=password" -v /home/user/docker:/src bobwmcgrath/deepdream


Then head to https://127.0.0.1:443, enter 'password' and start playing. 

stop all dockers with

	sudo docker stop $(sudo docker ps -q)
