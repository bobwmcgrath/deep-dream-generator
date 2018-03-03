# deep-dream-generator

####\#deepdream in a docker environment, to save you 8 hours of setup headaches.

To set up the container, you can build it yourself from here.

Once you have a container ready, run it with

	sudo docker run -d -p 443:8888 -e "PASSWORD=password" -v /home/user/docker:/src bobwmcgrath/deepdream


Then head to https://127.0.0.1:443, enter 'password' and start playing. 

stop all dockers with

	sudo docker stop $(sudo docker ps -q)
