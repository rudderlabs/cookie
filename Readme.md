

 This repository contains the required resources for the cookie component.

## Installation

    $ component install component/cookie

## Example

```js
// set
cookie('name', 'tobi')
cookie('name', 'tobi', { path: '/' })
cookie('name', 'tobi', { maxage: 60000 }) // in milliseconds
cookie('species', 'ferret')

// get
var name = cookie('name')
// => "tobi"

var cookies = cookie()
// => { name: "tobi", species: "ferret" }

// clear
cookie('name', null)
```
## Contact Us

If you come across any issues while using this repository, please feel free to start a conversation on our [Slack](https://resources.rudderstack.com/join-rudderstack-slack) channel. We will be happy to help you.
