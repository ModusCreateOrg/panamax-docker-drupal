![No longer maintained](https://img.shields.io/badge/Maintenance-OFF-red.svg)
### [DEPRECATED] This repository is no longer maintained
> While this project is fully functional, the dependencies are no longer up to date. You are still welcome to explore, learn, and use the code provided here.
>
> Modus is dedicated to supporting the community with innovative ideas, best-practice patterns, and inspiring open source solutions. Check out the latest [Modus Labs](https://labs.moduscreate.com?utm_source=github&utm_medium=readme&utm_campaign=deprecated) projects.

[![Modus Labs](https://res.cloudinary.com/modus-labs/image/upload/h_80/v1531492623/labs/logo-black.png)](https://labs.moduscreate.com?utm_source=github&utm_medium=readme&utm_campaign=deprecated)

---
panamax-docker-drupal
=====================

Drupal docker image without a DB included in the image. This image is designed to be used with panamax/panamax-docker-mysql or similar stand-alone DB image in order to create a multi-container cluster. 

On docker run, browse to Port 80 on the container to complete initial setup. 
Example usage:

`$ docker run --rm --name DRUPAL --link DB:DB panamax/panamax-docker-drupal:7.28`

...where `DB:DB` matches the name and alias of your DB instance. Use the values from your linked DB image to complete GUI setup.

From [CenturyLink Labs](http://www.centurylinklabs.com)
