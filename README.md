# paint-app-switcher

#### The AppSwitcher Component Styles and Assets

**Package Dependencies**

* Paint 0.8.10

**Component Dependencies**

* Panel
* Modal

**How to Use**

In your `Bower.json` include
`"paint-app-switcher": "git+https://github.com/alphasights/paint-app-switcher.git"`

And then after loading Paint use
`@include 'bower-components/paint-app-switcher/stylesheeets/components/app-switcher'`

Reset the assets path with

```scss
$app-switcher: (
  assets-path: 'paint-app-switcher/assets/images/'
);
```
based on your application settings.