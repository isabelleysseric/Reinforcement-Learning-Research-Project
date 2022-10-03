<p align="center">
  <img src="https://github.com/isabelleysseric/Reinforcement-Learning-Research-Project/blob/master/norlab_logo_noir.PNG?raw=true" />
</p>
<br/>
<br/>

# TEMPLATE FILES FOR GAZEBO IGNITION IN SDF FORMAT
<br/>
<br/>

[SSIM-Sim](https://norlab.youtrack.cloud/issues?q=project:%20%7B%F0%9D%94%96%20SNOW-sim%7D) (Youtrack)
&nbsp; • &nbsp;[SNOW](https://norlab.ulaval.ca/research/snow/) (WebSite)
&nbsp; • &nbsp;[SNOW-sim](https://github.com/isabelleysseric/Reinforcement-Learning-Research-Project) (GitHub)
&nbsp; • &nbsp;[Wiki SNOW-sim](https://github.com/isabelleysseric/Reinforcement-Learning-Research-Project/wiki) (Wiki)
&nbsp; • &nbsp;[isabelleysseric](https://hub.docker.com/u/isabelleysseric) (Docker)
&nbsp; • &nbsp;[User: isabelleeysseric](https://app.gazebosim.org/isabelleeysseric) (Fuel Ignition Gazebo)
&nbsp; • &nbsp;[Models: NORLAB](https://app.gazebosim.org/search;q=NORLAB) (Fuel Ignition Gazebo)
&nbsp; • &nbsp;[isabelleysseric.com](https://isabelleysseric.com) (Portfolio)
&nbsp; • &nbsp;[isabelle-eysseric](https://www.linkedin.com/in/isabelle-eysseric/) (Linkedin)
<br/>
<br/>


*Author: Isabelle Eysseric*
<br/>
<br/>


## Introduction
<br/>

**Template SDF for World**:  

* World Name
    * Physics: DART by default
    * Plugin: Physics
    * Plugin: UserCommands
    * Plugin: SceneBroadcaster
    * GUI
        * Plugin: 3D scen
        * Plugin: World control
        * Plugin: World statistics
        * Plugin: Entity tree
        * Plugin: Transform Control
    * Scene
    * Light: Sun
    * Model

<br/>

**Template SDF for model**:  
* Model Name
    * Pose: X Y Z Roll Pitch Yaw
    * Link: name 
        * Optional: Inertial: Properties
        * Collision: Geometry & Surface
        * Visual: Geometry & Material

<br/>
