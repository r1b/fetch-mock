# fetch-mock
Mock http requests made using [fetch](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/fetch)

![node version](https://img.shields.io/node/v/fetch-mock.svg?style=for-the-badge)
[![licence](https://img.shields.io/npm/l/fetch-mock.svg?style=for-the-badge)](https://github.com/wheresrhys/fetch-mock/blob/master/LICENSE)
![npm downloads](https://img.shields.io/npm/dm/fetch-mock.svg?style=for-the-badge)

[![CircleCI](https://img.shields.io/circleci/project/github/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://circleci.com/gh/wheresrhys/workflows/fetch-mock)
[![Code coverage](https://img.shields.io/coveralls/github/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://coveralls.io/github/wheresrhys/fetch-mock)
[![bitHound dependencies](https://img.shields.io/bithound/dependencies/github/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://www.bithound.io/github/wheresrhys/fetch-mock/master/dependencies/npm)

```js
fetchMock.mock('http://example.com', 200);
const res = await fetch('http://example.com');
assert(res.ok);
fetchMock.restore();
```

## Table of Contents

  * [Requirements](#requirements)
  * [Documentation and Usage](http://www.wheresrhys.co.uk/fetch-mock/)
  * [License](#license)
  * [Housekeeping](#housekeping)

---

**I devote a lot of time to maintaining fetch-mock for free. I don't ask for payment, but am raising money for a refugee charity - <a href="https://www.justgiving.com/fundraising/rhys-evans-walk">please consider donating</a>**

---


## Requirements

fetch-mock requires the following to run:

*	[Node.js](https://nodejs.org/) 8+ for full feature operation
*	[Node.js](https://nodejs.org/) 0.12+ with [limitations](http://www.wheresrhys.co.uk/fetch-mock/installation)
*	[npm](https://www.npmjs.com/package/npm) (normally comes with Node.js)
*	Either of the following
	- [node-fetch](https://www.npmjs.com/package/node-fetch) when testing in a nodejs
	- A browser that supports the `fetch` API when testing in a browser

## Documentation and Usage
See the [project website](http://www.wheresrhys.co.uk/fetch-mock/)


## License
fetch-mock is licensed under the [MIT](https://github.com/wheresrhys/fetch-mock/blob/master/LICENSE) license.  
Copyright © 2018, Rhys Evans


## Housekeeping

![npm version](https://img.shields.io/npm/v/fetch-mock.svg?style=for-the-badge)
[![bitHound dev dependencies](https://img.shields.io/bithound/devDependencies/github/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://www.bithound.io/github/wheresrhys/fetch-mock/master/dependencies/npm)
[![bitHound code](https://img.shields.io/bithound/code/github/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://www.bithound.io/github/wheresrhys/fetch-mock/master/files)
[![issues](https://img.shields.io/codeclimate/issues/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://codeclimate.com/github/wheresrhys/fetch-mock/maintainability)
[![maintainability](https://img.shields.io/codeclimate/maintainability/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://codeclimate.com/github/wheresrhys/fetch-mock/maintainability)
[![tech debt](https://img.shields.io/codeclimate/tech-debt/wheresrhys/fetch-mock.svg?style=for-the-badge)](https://codeclimate.com/github/wheresrhys/fetch-mock/maintainability)
