# markvis
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fgeekplux%2Fmarkvis.svg?type=shield)](https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fgeekplux%2Fmarkvis?ref=badge_shield)


make visualization in markdown.

## Install

```bash
yarn add markvis --save
npm install markvis --save
```

## Usage

```js
const md = require('markdown-it')()
const vis = require('markvis')
const d3 = require('d3')  // in browser environment
const d3node = require('d3-node') // in node environment

md.use(vis).render(`
  your makrdown content
`, {
  d3,    // in browser environment
  d3node // in node environment
})
```

there are [Examples](./test/test.js) which in node environment.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


### LICENSE

**markvis** © [geekplux](https://github.com/geekplux), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by geekplux with help from contributors ([list](https://github.com/geekplux/markvis/contributors)).

> [github.com/geekplux](https://github.com/geekplux) · GitHub [@geekplux](https://github.com/geekplux) · Twitter [@geekplux](https://twitter.com/geekplux)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fgeekplux%2Fmarkvis.svg?type=large)](https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fgeekplux%2Fmarkvis?ref=badge_large)