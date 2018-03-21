# How to build and run an NPM project

## Foreword
This is a simple guide for noobs like me. Based on Microsoft's Typescript Node Starter, this tutorial provides a step by step set of instructions about what commands to try to get up and running on a node project.

This tutorial applies to most node projects that contain a server and/or user interface. For more complicated projects (that don't have their own documentation) try step number two below and use common sense from there.

## Getting Started

Note: These instructions may contain extra steps for some projects. So do not fear if you encounter `npm ERR! missing script:` errors.

1. 	install necessary modules:
	```
	npm install
	```
1. (Optional) You can view available actions by simply typing:
	```
	npm run
	```
1. Build the project
	```
	npm run build
	```
1. Run the server (you may want to do this in a separate command prompt!)
	```
	npm run serve
	```
1. Run the user interface (particularly applies to electron/console apps)
	```
	npm run start
	```
1. Alternative: Sometimes the server will supply an ip address that can be opened in browser.

## Troubleshooting

#### `npm run serve` results in an error
This is likely a result of the server depending on another process that is not running. If the app uses MongoDB, for example, this can be remedied by running `mongodb` in another tab. You may need to run as sudo/admin.
