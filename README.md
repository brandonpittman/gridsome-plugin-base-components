# gridsome-plugin-base-components

Auto-import base components. [Like
this.](https://vuejs.org/v2/guide/components-registration.html) Components
should be in `src/components` and start with `Base`.

If you have files in `src/composables` that fit the pattern `use-something.{js,ts}`, these will also be required.

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
