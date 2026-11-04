# Evaluador · Mes de las 5S (Escorial)

App de un solo archivo (`index.html`, sin dependencias) para puntuar y rankear los sectores de la competencia según el Reglamento v2.

## Reglas implementadas
| Criterio | Pts | Cálculo |
|---|---|---|
| Brecha cerrada | 60 | (Final − Inicial) ÷ (100 − Inicial) × 60; si baja, 0 |
| Tablero B | 25 | Parte A (15): cierre ponderado (altas ×2) + Parte B (10): calidad |
| Nivel final | 15 | Auditoría final ÷ 100 × 15 |
| Penalización | −10 | Por hallazgo de innecesarios escondidos |

Desempate: más acciones de criticidad alta cerradas. Sello 5S Sostenible: auditoría sorpresa ≥ 90% de la final.

Mientras no haya auditoría final, usa la cruzada y marca el ranking como parcial.

## Uso
Abrir `index.html` en el navegador. Los datos se guardan en el navegador; usar "Guardar respaldo (JSON)" para llevarlos a otra PC.

## Publicar en GitHub Pages
Subir `index.html` y `README.md` a un repo → Settings → Pages → rama `main`, carpeta `/root`.
