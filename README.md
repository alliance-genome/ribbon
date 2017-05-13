# ribbon
Short form matrix view of all GO annotations for a given gene

## Acknowledgments
- Thanks to Josh Goodman for making his code available as a launching point

## Installation
- Make sure node.js is installed - see https://nodejs.org/en/download/

- Once node.js is on your machine then dependent packages need to be brought in. Running `npm install` in the components's root directory will install everything you need for development.
 - Note that you may need to run 'npm install' as sudo.

## Demo Ribbon Server

- `npm start` will run a local server with the ribbon's demo app at [http://localhost:3000](http://localhost:3000) with hot module reloading. 
- To actually see a populated 'ribbon' you will need to provide the resource name and the resource's gene identifier in the URL. That is:  [http://localhost:3000/?db=MGI&id=MGI:97490](http://localhost:3000/?db=MGI&id=MGI:97490) or [http://localhost:3000/?db=ZFIN&id=ZDB-GENE-990415-173](http://localhost:3000/?db=ZFIN&id=ZDB-GENE-990415-173) 

## Examples
- fly
![img](docs/flyribbon.png)

- zebrafish

![img](docs/zfinribbon.png)

- mouse
![img](docs/mouseribbon.png)
