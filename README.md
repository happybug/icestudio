# Icestudio

[![R&D](https://img.shields.io/badge/-R%26D-brightgreen.svg)](https://github.com/Jesus89/icestudio)
[![License](http://img.shields.io/:license-gpl-blue.svg)](http://opensource.org/licenses/GPL-2.0)

Experimental graphic editor for open FPGAs: [iCEstick](http://www.pighixxx.com/test/portfolio-items/icestick/) and [Icezum Alhambra](https://github.com/FPGAwars/icezum). Built on top of [icestorm project](http://www.clifford.at/icestorm/).

    GUI -> JSON -> Verilog, PCF

## Version 0.2 alpha

<img src="./doc/images/icestudio-0.2-project.png" width="600" align="center">

<img src="./doc/images/icestudio-0.2-block-inspection.png" width="600" align="center">

**Documentation: http://icestudio.readthedocs.io**

NOTE: this is an **early experimental version** and it is under development. Supported on Linux.

### Development

Install [nodejs](https://github.com/nodejs/node)
```bash
curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Install [bower](http://bower.io/)
```bash
sudo npm install -g bower
```

Install [grunt](http://gruntjs.com/)
```bash
sudo npm install -g grunt-cli
```

### Download

```bash
git clone https://github.com/FPGAwars/icestudio.git
cd icestudio
```

```bash
npm install
bower install
```

```bash
sudo apt-get install iverilog
```

```bash
pip install apio
apio install --all
```


### Execute

```bash
grunt serve
```

### Package

```bash
```

## Version 0.1

![][icestudio-0.1-demo]

### Installation

1. Install and configure the [drivers](https://github.com/FPGAwars/icestudio/wiki/Installing-the-drivers)

2. Download the [latest release](https://github.com/FPGAwars/icestudio/releases), unpack the zip and execute Icestudio

NOTE: initially supported on Linux (32, 64), Windows and Mac.

## Videos

### Version 0.1

[![Icestudio: GUI for open FPGAs](http://img.youtube.com/vi/Okl4Rr_i6Qk/0.jpg)](http://www.youtube.com/watch?v=Okl4Rr_i6Qk "Icestudio: GUI for open FPGAs")

[![Icestudio: code generation](http://img.youtube.com/vi/pG1DsF9MIj0/0.jpg)](http://www.youtube.com/watch?v=pG1DsF9MIj0 "Icestudio: code generation")

## Authors

* Jesús Arroyo

## Contributors

* Miguel Sánchez de León Peque
* Tomás Calvo

## Credits

* v0.1: using [AngularJS-Flowchart](https://github.com/codecapers/AngularJS-FlowChart)
* v0.2: using [JointJS](https://github.com/clientIO/joint)
* Sponsored by BQ.

## License

Licensed under [GPLv2](http://opensource.org/licenses/GPL-2.0) and [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

[icestudio-0.1-demo]: doc/images/icestudio-demo.gif
