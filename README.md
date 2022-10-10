# Nutibara-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Maximo DOleo

#Ejemplo
```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'nutibara-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 2,
        maxCount: 10
    }}
    >
    {
        ({ reset, count, increaseBy, maxCount, isMaxCountReached }) => (
            <>
                <ProductImage  />
                <ProductTitle />
                <ProductButtons/>
            </>
        )
    }
</ProductCard>
```