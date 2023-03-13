As the name implies, custom elements are HTML elements, like `<div>`, `<span>` , but something we can name ourselves that are defined via a browser API. They always have a dash in them.

Custom elements contain their own semantics, behaviors, markup and can be shared across frameworks and browsers.

```js
class MyComponents extends HTMLElement {
    connectedCallback() {
        this.innerHTML = `<h1>Custom Element</h1>`
    }
}
customElements.define('my-components', MyComponents)
```