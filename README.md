# Hyperscriptor

Super simple hyperscript helper on 21 lines

## Usage

Requires peer dependency [preact](https://github.com/developit/preact)

```sh
npm install hyperscriptor
```

```js
import { render } from 'preact'
import { div, h1 } from 'hyperscriptor'

const CoolHeading = div(
  {},
  h1(
    {},
    'HYPERSCRIPTOR!'
  )
)

render(CoolHeading, document.body)
```

## API

### element(props, children)

## TBD

*   Add support for using custom hyperscript functions,
    such as react's createElement.

*   Make it generic, not preact specific
