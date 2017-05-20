[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/iron-collapse-button)

# iron-collapse-button
An iron-collapse with a trigger section and optional expand/collapse icons.

## Installation

```
bower install --save iron-collapse-button
```

## Usage
Just define an element that has `slot="collapse-trigger"` and another with
`slot="collapse-content"` and it takes care of the rest.

## Demo
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="iron-collapse-button.html">
    <custom-style>
      <style is="custom-style" include="demo-pages-shared-styles">
        .flex {
          @apply --layout-flex;
        }
        iron-collapse-button {
          margin: 8px 0;
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
  <div slot="collapse-content">Content</div>
</iron-collapse-button>
<iron-collapse-button opened>
  <div slot="collapse-trigger" class="flex">Flexbox trigger</div>
  <div slot="collapse-content">Content</div>
</iron-collapse-button>
```

Full demo:
[webcomponents.org](https://www.webcomponents.org/element/jifalops/iron-collapse-button/demo/demo/index.html)
| [github](https://jifalops.github.io/iron-collapse-button/components/iron-collapse-button/demo/).

API: [webcomponents.org](https://www.webcomponents.org/element/jifalops/iron-collapse-button/iron-collapse-button)
| [github](https://jifalops.github.io/iron-collapse-button).

## Contributing

1. Fork it on Github.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT](https://opensource.org/licenses/MIT)
