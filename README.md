![Alt text](repo_data/dreamer-logo.png "Optional title")

Dreamer-Experiment-Handler
==================

Experiment-Handler For Dreamer Project (GÉANT Open Call).

Overview
-----------
I

---------------------------

## Requires

If you’re new to Node.js development, you’ll need to set up a few things first:
- Dreamer-Mininet-Extensions ([can be found here](https://github.com/netgroup/Dreamer-Mininet-Extensions))
- Dreamer-Topology3D([can be found here](https://github.com/netgroup/Dreamer-Topology3D))
- Node.js, easily installed on Mac, Windows, and Linux with packages from [nodejs.org](nodejs.org).
- [Supervisor](https://github.com/isaacs/node-supervisor) (optional): is used to restart programs when they crash. 
```sh
	 $ npm install supervisor -g
```


--------------------
 
Getting Started
---------------------

Assuming git installed:

```sh
$ git clone https://github.com/netgroup/Dreamer-Experiment-Handler.git
```
**Set the path of the Dreamer-Mininet-Extensions project.** By default Dreamer-Mininet-Extensions path is:

		config.mininet.mininet_extension_path = "/home/user/dreamer-mininet-extensions";

otherwise modify the file **config.js** according to your deployment. 

###Start the Dreamer-Experiment-Handler

```sh
$ cd Dreamer-Experiment-Handler/
$ node app.js
```
otherwise using [Supervisor](https://github.com/isaacs/node-supervisor):
```sh
$ cd Dreamer-Experiment-Handler/
$ supervisor app.js
```

---------------------

License
=======

This sofware is licensed under the Apache License, Version 2.0.

Information can be found here:
 [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).