tuxotron xvwa docker image
=================

This is an image to run xvwa in a docker container.
xvwa is a (intentionally) (Xtreme Vulnerable Web Application)[https://github.com/s4n7h0/xvwa].


Running the image
------------------------------

Start your image binding the external port 80:

	sudo docker --name xvwa run -d -p 80:80 tuxotron/xvwa

Open your browser and go to:

	curl http://localhost/xvwa


The first thing you need to do is to go to Setup / Reset menu and click on Submit / Reset button. This will prepare the database.

To stop the container:

	sudo docker stop xvwa

And to restart the same container:

	sudo docker start xvwa

Enjoy!
