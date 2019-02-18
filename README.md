# Reactisizer

### Installation

```bash
npm install --save reactisizer`
```

### Usage

```jsx
import React, { Component } from 'react'
import Reactisizer from 'reactisizer'

...
  render() {
    const {width, top, left, height} = this.state
    return (
        <Reactisizer
          left={left}
          top={top}
          width={width}
          height={height}
          aspectRatio={16 / 9}
          zoomable='n, w, s, e, nw, ne, se, sw'
          // onResizeStart={this.handleResizeStart}
          onResize={this.handleResize}
          // onResizeEnd={this.handleUp}
          // onDragStart={this.handleDragStart}
          onDrag={this.handleDrag}
          // onDragEnd={this.handleDragEnd}
        />
    )
...