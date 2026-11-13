# MelliScope — demo

Demostración en línea del **simulador educativo de fisiología glucémica y monitorización continua de glucosa**.

**▶ Probar la demo: <https://drodpaz.github.io/melliscope/>**

Funciona en el navegador, sin instalación y sin conexión: todo el simulador cabe en un único archivo `index.html`.

## Qué es

Un modelo determinista de glucosa e insulina calcula la respuesta a las comidas, a la insulina y al ejercicio, y un sensor de monitorización continua simulado la lee con retraso respecto a la sangre, ruido y pérdidas de señal.

Incluye monitor en tiempo real con flecha de tendencia y alarmas simuladas, 21 escenarios docentes, revisión de descargas, análisis de tiempo en rango y perfil ambulatorio, curso guiado, modos instructor/consulta/paciente/curso, pantalla de sensor sincronizada para proyector, y castellano y gallego.

> **Simulador educativo — no es un dispositivo médico.** No reproduce exactamente la fisiología humana. Los resultados son simulados y no deben utilizarse para calcular o modificar dosis de insulina en pacientes reales.

## Versión y cita

Este repositorio contiene el artefacto **v4.0.0**, idéntico al publicado en Zenodo.

**DOI:** [10.5281/zenodo.24117758](https://doi.org/10.5281/zenodo.24117758)

```bibtex
@software{rodriguezpaz_melliscope_2026,
  author    = {Rodríguez Paz, Domingo Damián},
  title     = {MelliScope: simulador educativo de fisiología glucémica
               y monitorización continua de glucosa},
  year      = {2026},
  version   = {4.0.0},
  doi       = {10.5281/zenodo.24117758},
  url       = {https://drodpaz.github.io/melliscope/}
}
```

## Autoría

Concepción, especificación funcional y clínica y dirección del proyecto: **Domingo Damián Rodríguez Paz** ([ORCID 0000-0002-1503-695X](https://orcid.org/0000-0002-1503-695X)).

El código se generó con asistencia de un modelo de inteligencia artificial (Claude, de Anthropic) a partir de esa especificación.

Las insulinas proceden de sus fichas técnicas (AEMPS/CIMA o EMA); la composición de los alimentos, de BEDCA y USDA FoodData Central; y el índice glucémico, de tablas publicadas.

## Licencia

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) — ver [LICENSE](LICENSE).

Puedes usar, compartir y adaptar el material con atribución, **sin fines comerciales**, y compartiendo las obras derivadas bajo la misma licencia.

Para cualquier uso comercial hace falta permiso expreso del autor.
