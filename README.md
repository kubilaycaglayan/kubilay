# kubilay

This npm package has several methods that helps user to create HTML elements in fewer lines.
Also has athousand separator method.

### Usage

### Install
###
- `npm install kubilay`
###
##### createElement
```javascript
const kubilay = require('kubilay');

const nav = kubilay.createElement('nav', 'd-none d-md-block');
```
##### createElementWithText
```javascript
import { createElementWithText } from 'kubilay';

const p = createElementWithText('p', 'text-success d-md-block', 'Ankara is the capital of Turkey.');
```
##### createImage
```javascript
import { createImage } from 'kubilay';
import Image from './image.png';"

const imageElement = createImage(Image, `A cat image`, 'rounded');
```
##### separate
```javascript
import { separate } from 'kubilay';

separate('123456789.00) // => '123,456,789.00'
```

### Run tests

- `npm run test`

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
