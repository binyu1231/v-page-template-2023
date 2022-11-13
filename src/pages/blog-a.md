[[toc]]

## Title

### Details

``` ts
const item: ItemEntity = {
  id: 1,
  name: 'foo'
}

function getItems(id: ItemEntity['id']): Promise<ItemEntity> {
  // ...
}
```

<HelloWorld msg="Hello Vue 3.0 + Vite" />