# Dogecoin node for Docker

![wow](https://upload.wikimedia.org/wikipedia/en/d/d0/Dogecoin_Logo.png)

Run a Dogecoin fullnode in an isolated Docker container

**But why should I do that?!**

* To support the Dogecoin community.
* Just for the sake of doing it.
* Because it's fun.

## How to install

**Make sure that port 22556 is being forwarded on your router!**

It's not that hard, actually. There are two ways to get it up and running:

### A. Pull and run the image from the [Docker Store](https://hub.docker.com/r/iskrudo/dogenode)

You only need to run one command to get it up and running:

```bash

docker run -d -p 22556:22556 --name dogenode iskrudo/dogenode:latest

```

Just wait until the process completes and boom, your Dogecoin node is up and running!

**TO THE MOON!!!**
