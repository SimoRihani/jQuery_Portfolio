# Polymer_Portfolio

This code is a simple, personal, and visual portfolio. For now, it is dedicated to be used on mrihani.vvv.enseirb-matmeca.fr (not yet).

It is based on [Polymer 1.0](https://www.polymer-project.org/) [Starter Kit Project](https://github.com/PolymerElements/polymer-starter-kit).


### Included out of the box:

* [Polymer](https://www.polymer-project.org/), [Paper](https://elements.polymer-project.org/browse?package=paper-elements), [Iron](https://elements.polymer-project.org/browse?package=iron-elements) and [Neon](https://elements.polymer-project.org/browse?package=neon-elements) elements
* [Material Design](http://www.google.com/design/spec/material-design/introduction.html) layout
* Routing with [Page.js](https://visionmedia.github.io/page.js/)
* Unit testing with [Web Component Tester](https://github.com/Polymer/web-component-tester)
* Optional offline setup through [Platinum](https://elements.polymer-project.org/browse?package=platinum-elements) Service Worker elements
* End-to-end Build Tooling (including [Vulcanize](https://github.com/Polymer/vulcanize))
* [Recipes](/docs/README.md/) for ES2015 support, Polymer performance, using Chrome Dev Editor, Deploying to GitHub Pages, Deploying to Firebase, Mobile Chrome Apps and lint tools.
* 
## Getting Started

To take advantage of this project you need to:

1. Get a copy of the code.
2. Install the dependencies if you don't already have them.
3. Deploy the code.

### Get the code

[Download](https://github.com/SimoRihani/Polymer_Portfolio).

### Install dependencies

#### Quick-start 

With Node.js installed, run the following one liner from the root of your Polymer_Portfolio download:

```sh
npm install -g gulp bower && npm install && bower install
```

#### Prerequisites 

The portfolio requires the following major dependencies:

- Node.js, used to run JavaScript tools from the command line.
- npm, the node package manager, installed with Node.js and used to install Node.js packages.
- gulp, a Node.js-based build tool.
- bower, a Node.js-based package manager used to install front-end packages (like Polymer).
- The Polymer_Portfolio gulp build process (the same as Polymer Starter Kit one) uses platform specific tools which is handled by node-gyp which is included in node.js. See https://github.com/nodejs/node-gyp/blob/master/README.md for additional platform specific dependencies.

**To install dependencies:**

1)  Check your Node.js version.

```sh
node --version
```

The version should be at or above 0.12.x.

2)  If you don't have Node.js installed, or you have a lower version, go to [nodejs.org](https://nodejs.org) and click on the big green Install button.

3)  Install `gulp` and `bower` globally.

```sh
npm install -g gulp bower
```

This lets you run `gulp` and `bower` from the command line.

4)  Install the portfolio's local `npm` and `bower` dependencies.

```sh
cd Polymer_Portfolio && npm install && bower install
```

This installs the element sets (Paper, Iron, Platinum) and tools the portfolio requires to build and serve apps.

### Development workflow

#### Serve / watch

```sh
gulp serve
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

###Useful links

- A demonstration of the client side : https://www.youtube.com/watch?v=g4eWmH3QEk4&feature=youtu.be



