# COVID-19 research at home...

[Folding@Home](https://foldingathome.org/) is a distributed computing project where people donate their CPUs/GPUs to help simulate protein folding.

More info on what it is here:

https://foldingathome.org/about/

## Getting started

Have Docker installed on your computer... clone this repo and update the values in the docker-compose file (for example... you probably don't want to contribute to my user's tally... or maybe you do...).

If you have an NVIDIA GPU it's a good idea to turn that on (it's a lot faster...).

When done, run:

`docker-compose up -d`

This will bring up a web interface at `http://localhost:7396`.  To participate in COVID-19 research select "Any disease" at the top of the interface (COVID-19 is active there by default)