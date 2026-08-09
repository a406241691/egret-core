<p align="center">
    <img src="./docs/img/egret_logo.jpg"
         height="130">
</p>
<p align="center">
    <a href="https://a406241691.github.io">
        <img src="https://img.shields.io/github/forks/egret-labs/egret-core.svg"
             alt="forks">
    </a>
    <a href="https://a406241691.github.io">
        <img src="https://img.shields.io/github/stars/egret-labs/egret-core.svg"
             alt="stars">
    </a>
    <a href="https://a406241691.github.io">
        <img src="https://img.shields.io/badge/version-5.4.1-green.svg"
             alt="version">
    </a>
    <a href="./LICENSE.md">
        <img src="https://img.shields.io/badge/license-New%20BSD-blue.svg"
             alt="license">
    </a>
</p>

[EN](README.md) / [CN](README_CN.md)

# Egret Engine

The Egret Engine is a HTML5 game engine. It provides modules to handle common game development tasks such as 2D and 3D rendering, GUI systems, and audio and resource management. The Egret engine is flexible and suitable for 2D or 3D projects. It allows developers to work without worrying about low-level browser impelementation, HTML5 performance, or fragmentation issues.

## Platform Coverage 

### Mobile

![](https://img.shields.io/badge/iOS-8.0%2B-lightgrey.svg)
![](https://img.shields.io/badge/Android-4.0%2B-brightgreen.svg)
![](https://img.shields.io/badge/Windows%20Phone-8-orange.svg)

### PC

![](https://img.shields.io/badge/Chrome--brightgreen.svg)
![](https://img.shields.io/badge/Safari--yellow.svg)
![](https://img.shields.io/badge/FireFox--orange.svg)
![](https://img.shields.io/badge/Edge--red.svg)
![](https://img.shields.io/badge/IE-9+-blue.svg)

# Installation

To Install the Egret Engine:

* [Download](https://a406241691.github.io) the Egret Engine Manager.

* Then, follow the [installation and deployment instructions](https://a406241691.github.io) 

Once installation is complete, Egret's engine and tools are easy to manage.

# Getting Started

#### TypeScript

Egret projects are developed using TypeScript, which is a superset of JavaScript. Please refer to the TypeScript manual for more information. The Egret API and ActionScript3 (AS3) are very similar. It will be easy to get started with Egret if you are familiar with AS3.

#### Create a project by command line

Use following command to create a default game object:

    egret create HelloWorld

You may also add parameters if required: Use `empty` | `game` | `gui` | `eui` to specify different projects. 

After running this command, you should now see a folder called 'HelloWorld'.

#### Write your first line of code

By default, the entry point for an Egret game projects is src / Main.ts. To make write the first line of code for your project, find the createGameScene () function, and add console.log ("Hello World");

After making your changes, the code should now look like this:

    private createGameScene():void {
            // log
            console.log("Hello World");
            var sky:egret.Bitmap = this.createBitmapByName("bgImage");
            this.addChild(sky);
            var stageW:number = this.stage.stageWidth;
            var stageH:number = this.stage.stageHeight;
            sky.width = stageW;
            sky.height = stageH;
            //...
        }

Here, we've called `console.log("log content that we'd like to display")`. This will display our log message in the browser's developer tool.

    We recommend using Chrome to debug the Egret project.

Use the following command to build Egret projects:

    egret build

Use the following command to run Egret projects:

    egret startserver

![](./docs/img/console.png)

For more information, please refer to the Learning Module documentation.

# Demos

Tower Defence Demo
![](./docs/img/3d_demo_1.png)
Click [here](https://a406241691.github.io) for online experience.<br/>

Click [here](https://a406241691.github.io) for more 2D/3D demos.<br/>

# Show Case

Click here to see [Show Case](https://a406241691.github.io)<br/>

# Learn

* Access [Doc](https://a406241691.github.io) to get Engine document
* Access [Example](https://a406241691.github.io) to learn demo source code
* Access [API](https://a406241691.github.io) to get API document
* Access [Video](https://a406241691.github.io) to get videos
* Access [Community](https://a406241691.github.io) to communicate with other developers

# Tools

* Access [Egret Engine](https://a406241691.github.io) to get Egret Engine launcher
* Access [Egret Wing](https://a406241691.github.io) to get Egret IDE
* Access [Dragonbones Pro](https://a406241691.github.io) to get DragonBones
* Access [Moew Tools](https://a406241691.github.io)

# Third Party Library

* Use [base64texture](https://a406241691.github.io) to convert base64 String to egert Texture
* Use [dcagent](https://a406241691.github.io) DataEye SDK for Egret
* Use [ecs](https://a406241691.github.io) component system
* Use [euiextension](https://a406241691.github.io) EUI extension
* Use [gesture](https://a406241691.github.io) Gesture library
* Use [keyboard](https://a406241691.github.io) Keyboard event listener
* Use [Greensock](https://a406241691.github.io) Greensock animation library
* Use [jszip](https://a406241691.github.io) jszip Compression library
* Use [md5](https://a406241691.github.io) A simple MD5 Library
* Use [mouse](https://a406241691.github.io) PC mouse support library
* Use [particle](https://a406241691.github.io) particle system
* Use [physics](https://a406241691.github.io) p2Physics engine，current version 0.7.0
* Use [socket](https://a406241691.github.io) socket.io
* Use [tiled](https://a406241691.github.io) tiledmap support library
* Use [weixinapi](https://a406241691.github.io) WeChat API
* More third party libraries please visit [here](https://a406241691.github.io) 

# Contributing

Asking a question is the first step to participating in an open-source community. You can report Egret issues [here](https://a406241691.github.io).
It is recommended that issues be discussed in the [official community portal](https://a406241691.github.io), as it can help with solving problems efficiently.

# License

This content is released under the (https://a406241691.github.io) BSD License.

![](https://img.shields.io/badge/license-New%20BSD-blue.svg)
