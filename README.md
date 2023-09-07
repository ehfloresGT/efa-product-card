# EFA-Product-Card

Este es un paquete de pruebas para despliegue en NPM.

### Edgar Flores

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'efa-product-card';
```

```
<ProductCard
  product={product}
  initialValues={{
    count: 4,
    // maxCount: 10,
  }}
>
  {
    ({reset, count, isMaxCountReached, maxCount, increaseBy }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard>
```