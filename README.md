# Control Uber

Página personal para llevar ganancias diarias de Uber, gasolina, km y ahorro semanal (mantenimiento, impuesto vehicular y SOAT).

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (ej. `control-uber`).
2. Sube `index.html` (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. En 1–2 minutos queda en `https://TU-USUARIO.github.io/control-uber/`.

## Cómo calcula

- **Neto diario** = ganancias − gasolina
- **Ahorro mantenimiento** = km × $/km configurado
- **Gasolina diaria** = km ÷ km por galón × precio del galón (editable por día)
- **Ahorro semanal** = km de la semana × $/km + (impuesto + SOAT + seguro anual) ÷ 52
- **Libre** = neto − ahorro total
- Las semanas van de lunes a domingo.

## Importante sobre los datos

Los datos se guardan en el navegador (localStorage) del dispositivo donde los registras. No se suben a GitHub.
- Usa **Respaldo (JSON)** de vez en cuando para guardar una copia.
- Usa **Restaurar** para pasarlos a otro celular/PC.

## Traer tu Excel

Guarda tu hoja como CSV con estas columnas en este orden (con encabezado):

```
fecha;km;gasolina;ganancias
16/11/2026;180;45000;210000
```

y usa **Importar CSV**.
