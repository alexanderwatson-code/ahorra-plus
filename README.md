# Ahorra+

App web sencilla que responde una sola pregunta: **¿cuánto puedo gastar hoy sin romper mi meta de ahorro del mes?**

Configuras tu ingreso, tus gastos fijos y tu meta una vez al mes. Después solo registras lo que gastas, y la app reparte lo que te queda entre los días que faltan.

## Cómo calcula

```
dinero libre del mes = ingreso − gastos fijos − meta de ahorro
disponible hoy       = (dinero libre − lo gastado antes de hoy) ÷ días que quedan (incluido hoy)
                       − lo gastado hoy
```

Si un día gastas de más, la diferencia se reparte entre los días siguientes; si gastas de menos, al día siguiente tienes un poco más.

## Funciones

- Indicador de color: verde (vas bien), ámbar (te queda menos del 40 % de hoy), rojo (te pasaste).
- Registro de gastos con nota opcional y opción para borrarlos.
- Resumen del mes: gastado, lo que queda y días restantes.
- Los datos se guardan en tu navegador (`localStorage`); no se envían a ningún servidor.
- Al empezar un mes nuevo te pide confirmar la configuración.
- Modo oscuro automático y se puede instalar en el celular (PWA) y usar sin conexión.

## Uso

Abre `index.html` en el navegador, o visita la versión publicada en GitHub Pages:
https://alexanderwatson-code.github.io/ahorra-plus/

## Tecnologías

HTML, CSS y JavaScript sin librerías ni dependencias.

## Autor

Alexander Watson — [GitHub](https://github.com/alexanderwatson-code) · [LinkedIn](https://linkedin.com/in/Alexander-Watson-H)
