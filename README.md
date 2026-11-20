# Trading ACME><BRAND

Gráfico de velas para cripto, forex, acciones, índices y metales.
Se abre como web normal (GitHub Pages) y más adelante se convierte en PWA.

## Estructura del repositorio

```
index.html                         la aplicación completa
README.md                          este archivo
.nojekyll                          archivo vacío, evita que GitHub Pages procese los archivos
lib/
  technicalindicators.js           librería de indicadores (RSI, MACD, Bollinger)
  technicalindicators-LICENSE.txt  licencia MIT de esa librería
img/
  logo.png                         logo de la marca de agua (256 px)
  logo-512.png                     logo grande, para el ícono de la PWA
```

Pendiente para el final (PWA): `manifest.json` y `sw.js` en la raíz, e `img/logo-192.png`.

## Antes de publicar

- No escribas la clave de Twelve Data en `index.html` si el repositorio es público.
  Déjala como viene y pégala desde Ajustes (⚙) en tu celular.

## Créditos

- Gráficos: TradingView Lightweight Charts™ (Apache 2.0) https://www.tradingview.com/
- Indicadores: technicalindicators (MIT)
- Datos: Binance y Twelve Data
