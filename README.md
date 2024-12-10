# API_BCRA_Porcentaje_de_prestamos_en_relacion_a_depositos_Bancarios_en_Argentina

Este proyecto consume la API del BCRA para analizar el Porcentaje de préstamos en relación a depósitos Bancarios en Argentina.

Fue desarrollado como un desafío de APIs Públicas del Banco Central de la República Argentina para Coderhouse.

## Descripción del Proyecto

Este proyecto proporciona una forma sencilla de acceder a los datos del BCRA sobre el porcentaje de préstamos en relación a los depósitos bancarios.  Permite visualizar la información directamente en el navegador, facilitando el análisis de las tendencias.

## Cómo ejecutar el código

1. Clona este repositorio: `git clone https://github.com/RickyFer22/API_BCRA_Porcentaje_de_prestamos_en_relacion_a_depositos_Bancarios_en_Argentina.git`
2. Abre el archivo `index.html` en tu navegador.

## Ejemplo de respuesta de la API

```json
[
  {
    "d": "2023-08-31",
    "v": 0.4432
  },
  {
    "d": "2023-09-01",
    "v": 0.4423
  }
]
```

Donde:

* `"d"`: Fecha (YYYY-MM-DD)
* `"v"`: Valor del porcentaje
