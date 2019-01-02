<img src="https://tinypixel.io/app/uploads/2019/01/senzai.png" alt="Senzai" />

![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg) [![Gitter](https://img.shields.io/badge/chat-gitter-purple.svg)](https://gitter.im/Tiny-Pixel/senzai) ![License](https://poser.pugx.org/tiny-pixel/wp-performant-media/license) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/70a4cc122c2f45a9a0d6d24e2c7c4587)](https://www.codacy.com/app/pixelcollective/senzai?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pixelcollective/senzai&amp;utm_campaign=Badge_Grade)

[![Waffle.io - Columns and their card count](https://badge.waffle.io/pixelcollective/senzai.svg?columns=all)](https://waffle.io/pixelcollective/senzai) 

Development and remote provisionment for WordPress with Ansible, Docker, Traefik and a galaxy of niceties.

_This project is not production ready._

## Features
* Convenient development environment.
* Tools to aide both the management of Production environments and local dev work.
* Portainer allows you to create and manage site containers and utilities with great ease.
* Traefik allows for assignment of domains and provisionment of SSL with similar on-the-fly ease.
* Duplicity for manageable backups of the stack.
* Netdata for remote monitoring of server health and performance.

## Goals
* Stronger documentation
* Testing
* Composer & out-of-the-box compatibility with Bedrock & Sage.
* Structured /etc/hosts management.
* Lighter ansible configuration for local development (while maintaining parity).
* ansible-vault support.
* Potentially pulling from Trellis directly. 

## Development
* Configure variables in group_vars/all.yml.
* `Vagrant up` for local development
* It probably won't work.

## Deployment
* Configure playbook `inventory`.
* `ansible-playbook senzai.yml -b -K`
* It probably won't work.

## Contributing

I realize that this is incomplete and not fully functional. Hence, I don't need to be told (given that we're working Ansible and Docker I think it's safe to assume the ship is bowing the same for me as it is for you.)

But Pull Requests? Oh, absolutely. I have limited experience with a lot of this software and am really just kicking the tires with a fun side project. But, it would be so cool to see it working.

As always, be kind, both when collaborating on  Github and in the broader spheres you inhabit and shape by virtue of your presence. Remember that to be human is to suffer, and always move through this world with grace and humility. Treat women with respect. 

Also, give your money to [Roots](https://roots.io). You might also consider hiring [Tiny Pixel](https://tinypixel.io) to help you with less experimental WordPress development (we make really great sites!)