# Hyperscriptor

Super simple hyperscript helper on 21 lines

## Usage

Requires peer dependency [preact](https://github.com/developit/preact)

```sh
npm install hyperscriptor
```

```js
import { render } from 'preact'
import { div, h1, h2 } from 'hyperscriptor'

const CoolHeadings = () => div({}, [
  h1({}, 'HYPERSCRIPTOR!')
  h2({}, 'Here is a subheading')
])

render(CoolHeading(), document.body)
```

## API

### element(props, children)

`props` work as expected, just pass in an object with the corresponding keys.
`children` can be a string, element or array.

Unable to find a proper api documentation for preact's `h` function,
I leave you with [react's createElement](https://facebook.github.io/react/docs/top-level-api.html#react.createelement)
which is practically indentical.

## TBD

*   Add support for using custom hyperscript functions,
    such as react's createElement.

*   Make it generic, not preact specific
