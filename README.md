# vim-babel-snippets
===================

Next generation JavaScript and React snippets for Vim
Require [garbas/vim-snipmate](https://github.com/garbas/vim-snipmate)

# Installation
=============

Use [Vundle](http://github.com/gmarik/vundle)

```
" vim-babel-snippets:
Bundle "huangguozhen/vim-babel-snippets"
" SnipMate and its dependencies:
Bundle "MarcWeber/vim-addon-mw-utils"
Bundle "tomtom/tlib_vim"
Bundle "garbas/vim-snipmate"

" Other sets of snippets (optional):
Bundle "honza/vim-snippets"
```

# Usage
======

In insert mode
```
rcc<Tab>
```

expanding to

```
import React, { Component, PropType } from 'react'

export default class ClassName extends Component {
  render () {
    return (

    )
  }
}
```

## Available snippets

### React

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rccl→`   | legacy component skeleton |
| `cdm→`   | `componentDidMount() {…}` |
| `cdup→`  | `componentDidUpdate(prevProps, prevState) {…}` |
| `cwm→`   | `componentWillMount() {…}` |
| `cwr→`   | `componentWillReceiveProps(nextProps) {…}` |
| `cwun→`  | `componentWillUnmount() {…}` |
| `cwup→`  | `componentWillUpdate(nextProps, nextState) {…}` |
| `fdn→`   | `React.findDOMNode(…)` |
| `gdp→`   | `getDefaultProps() {…}` |
| `gis→`   | `getInitialState() {…}` |
| `ren→`   | `render() {…}` |
| `sst→`   | `this.setState(…)` |
| `scu→`   | `shouldComponentUpdate(nextProps, nextState) {…}` |
| `props→` | `this.props` |
| `state→` | `this.state` |
