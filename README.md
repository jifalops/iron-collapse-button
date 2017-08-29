[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/iron-collapse-button)

# iron-collapse-button
An iron-collapse with a trigger section and optional expand/collapse icons.

## Installation

```
bower i -S iron-collapse-button      # Polymer 2.0 class based
bower i -S iron-collapse-button#^0.4 # Polymer 2.0 hybrid (1.x compatible)
```

## Usage
Show/hide collapsible content by filling the trigger and content slots.

## Demo
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="iron-collapse-button.html">
    <custom-style>
      <style include="demo-pages-shared-styles">
        .flex {
          @apply --layout-flex;
        }
        iron-collapse-button {
          margin: 8px 0;
        }
        ul {
          margin-top: 0;
        }
      </style>
    </custom-style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<iron-collapse-button>
  <div slot="collapse-trigger">Trigger</div>
  <div slot="collapse-content">
    <ul>
      <li>Do this</li>
      <li>or that</li>
    </ul>
  </div>
</iron-collapse-button>
<iron-collapse-button opened>
  <div slot="collapse-trigger" class="flex">Flexbox trigger</div>
  <div slot="collapse-content">
    <ul>
      <li>or this</li>
      <li>not that</li>
    </ul>
  </div>
</iron-collapse-button>
```

Full demo:
[webcomponents.org](https://www.webcomponents.org/element/jifalops/iron-collapse-button/demo/demo/index.html)
| [github](https://jifalops.github.io/iron-collapse-button/components/iron-collapse-button/demo/).

API: [webcomponents.org](https://www.webcomponents.org/element/jifalops/iron-collapse-button/iron-collapse-button)

## Contributing

1. Fork it on Github.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT](https://opensource.org/licenses/MIT)
