<p align="center">
  <img src="https://github.com/isabelleysseric/Reinforcement-Learning-Research-Project/blob/master/norlab_logo_noir.PNG?raw=true" />
</p>

<br/>
<br/>

# DOCKER-COMPOSE-IGNITION SOURCE INSTALLATION
<br/>
<br/>

[SSIM-Sim](https://norlab.youtrack.cloud/issues?q=project:%20%7B%F0%9D%94%96%20SNOW-sim%7D) (Youtrack)
&nbsp; • &nbsp;[SNOW](https://norlab.ulaval.ca/research/snow/) (WebSite)
&nbsp; • &nbsp;[Reinforcement-Learning-Research-Project](https://github.com/isabelleysseric/Reinforcement-Learning-Research-Project) (GitHub)
&nbsp; • &nbsp;[Reinforcement-Learning-Research-Project](https://github.com/isabelleysseric/Reinforcement-Learning-Research-Project/wiki) (Wiki)
&nbsp; • &nbsp;[isabelleeysseric](https://app.gazebosim.org/isabelleeysseric) (Fuel Ignition Gazebo)
&nbsp; • &nbsp;[isabelleysseric](https://hub.docker.com/u/isabelleysseric) (Docker)
&nbsp; • &nbsp;[isabelleysseric.com](https://isabelleysseric.com) (Portfolio)
&nbsp; • &nbsp;[isabelle-eysseric](https://www.linkedin.com/in/isabelle-eysseric/) (Linkedin)
<br/>
<br/>


*Author: Isabelle Eysseric*

<br/>
<br/>

## Introduction

THis is Docker Compose for Gazebo Ignition Fortress.  

<br/>
<br/>

## Instructions

Pre-run (local)

```shell
$ sh scripts/generate_docker_xauth.sh
```

Start

```shell
$ docker-compose -f <local or remote>/<intel or nvidia>/docker-compose.yml up
```

End

```shell
$ docker-compose -f <local or remote>/<intel or nvidia>/docker-compose.yml down
```

Removal

```shell
$ docker-compose -f <local or remote>/<intel or nvidia>/docker-compose.yml down -v --rmi all
```

<br/>
<br/>

## Example

How to run it locally and with Intel graphics.

```shell
$ docker-compose -f local/intel/docker-compose.yml up
```

