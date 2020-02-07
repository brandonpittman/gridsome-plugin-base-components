# gridsome-plugin-base-components

Auto-import base components. [Like
this.](https://vuejs.org/v2/guide/components-registration.html) Components
should be in `src/components` and start with `Base`.

## Installation

`npm i gridsome-plugin-base-components`

Add this to `gridsome.config.js`:

```javascript
plugins: [
	{
		use: 'gridsome-plugin-base-components',
	}
]
```


```html
<BaseInput
  v-model="searchText"
  @keydown.enter="search"
/>
<BaseButton @click="search">
  <BaseIcon name="search"/>
</BaseButton>
```

<a href="https://www.buymeacoffee.com/blp" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>
