# homelab-k8s

This is a dummy project, which is no longer active.
I created this repository as a side project when I was trying to run a homelab on my 12 year old VAIO laptop. With only 8Gb RAM and an HDD available, there was not much I could do with it.

I was always fascinated with homelabs and the ability to host nextcloud and similar setups on my own system.

Being familier with Kubernetes ( because of my profession ) by now, I decided to go with it.

I used Ubuntu Server 22 as the base OS on my oldie.
While setting up the server, it gave a very handy option of installing K8s but I did not wanted to set it up on my own.
After setting up microk8s on the system, I started setting up several systems needed for the project.

3 most important setups that were necessary were:
 - volume manager
 - ingress controller
 - frontend / reverse proxy outside the k8s cluster

Once this was also done, I started my first "Hello World" service. Added my favorite `snake` game as a hosted application. Then proceeded to setup nextcloud.
Some tweaks later, everything was up and running, thus concluding my experiment.

I had a lot to learn and this project gave me a lot to play around with too. 

This project that is uploaded here, is a sample of how I had things setup. After pushing the code to the repository, I had the whole device wiped out, reinstalled Ubuntu Server on it and redid the whole setup from scratch, this time with a media server, nextcloud and metrics server.

Hope you enjoy this and get some inspiration to start your own homelab.

Cheers!
