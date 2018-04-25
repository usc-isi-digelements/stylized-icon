# stylized-icon

A Polymer Element showing a stylized icon.  Use `icon-button` if you need click/tap behavior.

### Example
```html
<stylized-icon
  icon="icons:polymer"
  style-class="style-class"
  title-tooltip="Text">
</stylized-icon>
```

### Styling

`<stylized-icon>` provides the following custom properties and mixins for styling:

Custom property                  | Description                                             | Default
---------------------------------|---------------------------------------------------------|--------
`--stylized-icon-color`          | The color for the icon button.                          | --paper-grey-600
`--stylized-icon-mixin`          | The custom style mixin for the icon button.             | none
`--stylized-icon-active-color`   | The color for the icon button if active.                | --paper-grey-900
`--stylized-icon-active-mixin`   | The custom style mixin for the icon button if active.   | none
`--stylized-icon-disabled-color` | The color for the icon button if disabled.              | --paper-grey-300
`--stylized-icon-disabled-mixin` | The custom style mixin for the icon button if disabled. | none

The `styleClass` property has the following preconfigured options:

- amber
- black
- blue
- blue-grey
- brown
- cyan
- deep-orange
- deep-purple
- green
- grey
- indigo
- light-blue
- light-green
- lime
- orange
- pink
- purple
- red
- teal
- white
- yellow

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

