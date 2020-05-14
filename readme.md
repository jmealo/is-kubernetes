# is-kubernetes [![Build Status](https://travis-ci.org/jmealo/is-kubernetes.svg?branch=master)](https://travis-ci.org/jmealo/is-kubernetes)

> Check if the process is running on Kubernetes. Forked from: [sindresorhus/is-docker](https://github.com/sindresorhus/is-docker#readme)


## Install

```
$ npm install is-kubernetes
```


## Usage

```js
const isKubernetes = require('is-kubernetes');

if (isKubernetes()) {
	console.log('Running in a pod on kubernetes');
}
```


## License
MIT © [Sindre Sorhus](https://sindresorhus.com)
MIT © [Jeff Mealo](https://jeffmealo.com) 
