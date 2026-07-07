# El vacío del alquiler social — España en el contexto europeo

Policy brief interactivo sobre el parque de vivienda social en España: cuánto hay, cómo se compara con la Unión Europea, y cómo se reparte —de forma muy desigual— entre comunidades autónomas.

**[→ Ver el brief interactivo](https://stalaveralodos-ux.github.io/housing-rights-spain/)**

Este repositorio es una extensión del programa de investigación de mi tesis doctoral — *The Constitutional Role of Municipalities in the Governance of Social Rights* (Sant'Anna, 2026) — aplicando la misma pregunta de fondo (¿cómo se traduce el derecho a la vivienda en la práctica administrativa territorial?) a datos públicos españoles y europeos.

## Qué muestra

- **Comparativa europea**: España destina el 3,3% de su parque de vivienda principal a alquiler social, frente a una media de la UE-27 del 8,0% y a máximos como el 29% de Países Bajos o el 24% de Austria.
- **Desglose autonómico**: el parque de 251.937 viviendas de titularidad autonómica en España se concentra de forma muy desigual — Andalucía, País Vasco y Madrid concentran más de la mitad del total, mientras otras comunidades apenas superan las 200 unidades.
- **Régimen de tenencia**: qué proporción de ese parque es alquiler, alquiler con opción a compra, o vivienda destinada a la venta — un indicador indirecto de cuánta política de vivienda social es realmente permanente frente a transitoria.

## Estructura del repositorio

```
housing-rights-spain/
├── README.md
├── data/
│   ├── ccaa_vivienda_social_2023.csv        ← parque autonómico por régimen de tenencia
│   └── eu_comparativa_alquiler_social.csv   ← comparativa UE-27
└── docs/
    └── index.html                            ← el brief interactivo (servido vía GitHub Pages)
```

## Fuentes

- Ministerio de Vivienda y Agenda Urbana, *Observatorio de Vivienda y Suelo — Boletín Especial Vivienda Social 2024* (enero 2025). Tabla 2.2 (parque autonómico) y Tabla 2.1 (comparativa europea, con datos de base de Eurostat y Housing Europe).
- Instituto Nacional de Estadística (INE), Encuesta de Condiciones de Vida.

## Metodología y limitaciones

Los datos autonómicos corresponden a la Encuesta sobre vivienda social remitida en 2023 a comunidades autónomas y principales ayuntamientos. **No incluyen el parque de titularidad municipal** (aproximadamente 121.000 viviendas adicionales a nivel estatal, sin desglose territorial público disponible), por lo que las cifras aquí mostradas infravaloran el parque social real de aquellas comunidades donde el grueso de la vivienda social es de gestión municipal más que autonómica.

Los datos europeos combinan el último Censo de Población y Vivienda de Eurostat (2011, parque total) con datos de Housing Europe sobre alquiler social; varios países no cuentan con dato de 2023 y se emplea el más reciente disponible.

Este es un prototipo a escala autonómica/provincial, no municipal: es el nivel de máxima granularidad con series homogéneas y comparables para toda España. Las fases siguientes de este proyecto incorporarán una capa municipal para los tres casos de estudio de la tesis doctoral (Turín, Barcelona, Atenas) y una capa temporal con series trimestrales.

## Sobre la autora

Silvia Talavera Lodos — investigadora en derecho constitucional comparado y gobernanza europea de la vivienda y la migración. [Portfolio completo](https://stalaveralodos-ux.github.io/s.talaveralodos) · [Linktree](https://linktr.ee/s.talaveralodos)
