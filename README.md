# Simple Stand-Up API
## Descripción
Esta es una API súper sencilla creada como parte de un encuentro de stand-up con alumnos. La API fue generada utilizando Mockaroo para el dataset y está desplegada en GitHub Pages. Este proyecto formó parte de una mini capacitación sobre GitHub.

## Características
- ***Generación de Datos:*** Utiliza Mockaroo para generar datos ficticios.
- ***Despliegue:*** Implementado en GitHub Pages.
- ***Educación:*** Parte de una capacitación para enseñar a los alumnos sobre el uso de GitHub y la creación de APIs simples.

## Endpoints
### Obtener Datos
- **GET** *'/data/people.json'*
  - ***Descripción:*** Obtiene un conjunto de datos generados. (100 en total)
  - ***Respuesta:***
 
```json
[
  {
    "id": 1,
    "first_name": "Titos",
    "last_name": "Yelding",
    "email": "tyelding0@boston.com",
    "gender": "Male",
    "ip_address": "42.22.108.53"
  },
  {
    "id": 2,
    "first_name": "Hannie",
    "last_name": "Khrishtafovich",
    "email": "hkhrishtafovich1@mlb.com",
    "gender": "Female",
    "ip_address": "92.71.95.90"
  }
]
```

## Uso

- Clonar el repositorio:

``` bash
git clone https://github.com/tu-usuario/api-example.git
```

- Navegar al directorio del proyecto:

```bash
cd api-example
```
Abrir tu editor de código y habilitar el Live Server para ver la API desplegada.

## Contribución
Si deseas contribuir a este proyecto, sigue estos pasos:

- Haz un fork del proyecto.
- Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
- Realiza tus cambios y haz commit (git commit -m 'Agrega una nueva característica').
- Haz push a la rama (git push origin feature/nueva-caracteristica).
- Abre un Pull Request.
