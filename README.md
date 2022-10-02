# PC-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Paul Cortes

## Ejemplo

```js
import {ProductCard, ProductImage, ProductTitle, ProductButtons } from 'pc-product-card'
```

```js
<ProductCard
  product={product}
  initialValues={{
    count: 4,
    maxCount: 10,
  }}
>
  {({ reset, count, increaseBy, isMaxCountReached }) => (
    <>
      <ProductImage/>
      <ProductTitle />
      <ProductButtons />            
    </>
  )}
</ProductCard>
```