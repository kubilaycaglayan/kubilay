# kubilay

This npm package has several methods that helps user to create HTML elements in fewer lines.

```
const createElement = (element, className) => {
  const elm = document.createElement(element);
  elm.className = className;
  return elm;
};

const nav = createElement('nav', 'd-none d-md-block');
body.appendChild(nav);
```

## Author

👤 **Kubilay Caglayan**

- Website: [kubilay](https://kubilaycaglayan.com)
- Github: [@kubilaycaglayan](https://github.com/kubilaycaglayan)
- Twitter: [@kbcaglayan](https://twitter.com/kbcaglayan)
- Linkedin: [linkedin](https://linkedin.com/in/kubilaycaglayan)
