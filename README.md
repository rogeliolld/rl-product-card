# RL-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Rogelio Llerena

## Ejemplo
```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'rl-product-card';

```

```

<ProductCard
    product={product}
    initialValues={{
        count: 4,
        maxCount: 10,
    }}
    >
    {({ reset, isMaxCountReached, count, maxCount, increaseBy }) => (
        <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
        </>
    )}
</ProductCard>

```