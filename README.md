# react-rating-emoji

> An animated emoji rating component

[![NPM](https://img.shields.io/npm/v/react-rating-emoji.svg)](https://www.npmjs.com/package/react-rating-emoji) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-rating-emoji
```

## Usage

```jsx
import React, { useState } from 'react'

import { RatingComponent } from 'react-rating-emoji'
import 'react-rating-emoji/dist/index.css'

const App = () => {
  const [rating, setRating] = useState(0);

  const handleRating = (newRating) => {
    setRating(newRating);
  }

  return <RatingComponent rating={rating} onClick={handleRating} />
}

export default App

```

## License

MIT © [https://github.com/ultimateakash](https://github.com/https://github.com/ultimateakash)