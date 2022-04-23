# docker-swarm-apps
a collection of Dockerized apps adapted for Swarm

# I do not provide support for anyything in this repo.

It is simply a collection of my personal compose files that I have configured for use in Docker Swarm.

These files are provided as-is with a few assumptions:

 - You're already somewhat familiar with Docker/Swarm
 - You already have an appropriate setup for running multiple nodes
 - You already have shared or distributed storage in place across all nodes
 - You know that you should configure your own settings/.env files/etc prior to deployment
 - You're capable of doing your own troubleshooting

The last one is important - these files are all tailored towards my personal setup, but are basic enough that they should work "out of the box" for most people.
I will not be held liable or provide assistance for anything not working as expected - assume that you will need to do some tweaking and plan accordingly.

# Important Note

I manage all my Docker containers, Swarm stacks, and container networks with Portainer, and I highly recommend you do the same or find a preferable alternative as it will make your life much easier.


These configurations files are largely based on the "recipes" kindly provided by FunkyPenguin: [website](https://geek-cookbook.funkypenguin.co.nz/)  [GitHub](https://github.com/geek-cookbook)
