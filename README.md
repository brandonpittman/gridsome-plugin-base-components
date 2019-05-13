# gridsome-plugin-base-components

Auto-import base components. [Like this.](https://vuejs.org/v2/guide/components-registration.html)

```html
<BaseInput
  v-model="searchText"
  @keydown.enter="search"
/>
<BaseButton @click="search">
  <BaseIcon name="search"/>
</BaseButton>
```
