# List of the current repos in use

A quick way of getting all the clone url for all the related repositories is:

        curl https://api.github.com/users/wakaru44/repos 2>/dev/null | jq ".[].clone_url" | grep "personal\|workstation\|simplebutton\|sbs"

Below, there is a more elaborated description of each.

## the Troposphere stack
spin a simple machine

    https://github.com/wakaru44/troposphere.workstation.git

owned by wakaru

## Cordova Simple Button Stack

The mobile app with the button to launch

    https://github.com/wakaru44/cordova.simplebuttonstack.git

owned by wakaru

## Flask SBS API

the api that sits behind the app

    https://github.com/wakaru44/flask.sbs_api.git

Owned by wakaru

## Docker Flask SBS API

the dockerfiles to run everything nicely

    https://github.com/wakaru44/docker.sbs_flask_api.git

Owned by wakaru

## Ansible Personal

The configuration for a personal workstation. Install the basics and configure some stuff I'm currently working on

    git remote add origin https://github.com/wakaru44/ansible.personal.git

Owned by wakaru


