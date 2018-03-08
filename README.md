tuxotron xvwa docker image
=================

This is an image to run xvwa in a docker container.
xvwa is a (intentionally) [Xtreme Vulnerable Web Application](https://github.com/s4n7h0/xvwa).


Running the image
------------------------------

Start your image binding the external port 80:

	sudo docker run --name xvwa -d -p 80:80 tuxotron/xvwa

Open your browser and go to:

	http://localhost/xvwa


The first thing you need to do is to go to Setup / Reset menu and click on Submit / Reset button. This will prepare the database.

To stop the container:

	 docker stop xvwa

And to restart the same container:

	 docker start xvwa

Enjoy!
