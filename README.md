# kubilay

This is an npm package. It has several methods that helps user to create HTML elements in fewer lines.

### Usage

```
const kubilay = require('kubilay');

const nav = kubilay.createElement('nav', 'd-none d-md-block');
```

```
import { createElementWithText } from 'kubilay';

const p = createElementWithText('p', 'text-success d-md-block', 'Ankara is the capital of Turkey.');
```

```
import { createImage } from 'kubilay';
import Image from './image.png';"

const imageElement = createImage(Image, `A cat image`, 'rounded');
```

### Install

- `npm install kubilay`

### Run tests

- There is no automated tests for this project, yet.

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/kubilaycaglayan/kubilay/issues).

## Show your support

Give a ⭐️ if you like this project!

## Author

👤 **Kubilay Caglayan**

- Website: [kubilay](https://kubilaycaglayan.com)
- Github: [@kubilaycaglayan](https://github.com/kubilaycaglayan)
- Twitter: [@kbcaglayan](https://twitter.com/kbcaglayan)
- Linkedin: [linkedin](https://linkedin.com/in/kubilaycaglayan)
