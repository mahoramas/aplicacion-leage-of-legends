# leage-of-legends

## Descripción
El leage of legends es un juego bastante popular en donde se enfrentan 2 equipos de 5 para ver quien rompe antes el nexo enemigo, para ello tienes que elegir un campeon con habilidades únicas para enfrentarte a tu enemigo, y comprar objetos acorde al requerimiento de la partida.
Esto es algo que hace que muchos jugadores no se animen a probar el juego, por eso con este proyecto se busca crear una aplicacion que facilite ese proceso de saber que hacer o que usar.
A demas se podran subir los mejores clips de tus jugadas para que todos los que quieran puedan ver lo bueno que eres con tu personaje principal.

# Especificación de actores y casos de uso

## Actores
**Usuario sin registrar**: Usuario que no esta registrado pero puede ver los consejos de objetos y ver las mejores jugadas de otras personas.
**Usuario registrado**: Usuario que si esta registrado con lo que puede hacer lo mismo que un usario sin registrar a demas de poder subir sus propios clips y dar su opinion de los consejos proporcionados por la aplicación.
**Administrador**: Tiene todos los permisos a demas de poder banear a usuarios y modificar los consejos al actualizarse el juego.

## Casos de uso
**Usuario sin registrar**
* **Ver consejos**: El usuario puede ver los consejos que da la aplicación.
* **Ver contenido**: El usuario puede ver los videos de las mejores jugadas.
  
**Usuario registrado**
* **Subir contenido**: El usuario puede subir contenido a la aplicación.
* **Dar opinión**: El usuario puede dar opinion sobre los consejos de la aplicación.

**Administrador**
* **Banear usuarios**: El administrador puede banear usuarios de la aplicación para que no puedan subir contenido ni dar opinión.
* **Actualizar consejos**: El administrador puede actualizar los consejos de la aplicación.

## Diagrama de casos de uso
<img src="diseño/images/Diagrama LoL.drawio.png">

### Actores
|  Actor | Usuario sin registrar |
|---|---|
| Descripción  | _Usuario sin registrar en la aplicación_  |
| Características  |_Usa la aplicación sin registrar_ |
| Relaciones | __  |
| Referencias | _Ver consejos, ver contenido_ |   
|  Notas |  __ |
| Autor  | _Marcos Hernández Oramas_ |
|Fecha | _20/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

---

|  Actor | Usuario registrado |
|---|---|
| Descripción  | _Usuario que esta registrado en la aplicación_  |
| Características  |_Usa la aplicación registrado_ |
| Relaciones | __  |
| Referencias | _Subir contenido, dar opinión_ |   
|  Notas |  __ |
| Autor  | _Marcos Hernández Oramas_ |
|Fecha | _20/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

---

|  Actor | Administrador |
|---|---|
| Descripción  | _Administrador de la aplicción_  |
| Características  |_Usa la aplicación sin restricciones_ |
| Relaciones | __  |
| Referencias | _Banear usuarios, actualizar consejos_ |   
|  Notas |  __ |
| Autor  | _Marcos Hernández Oramas_ |
|Fecha | _12/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

---

### Casos de uso
|  Caso de Uso	CU | Ver consejos |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Usuario sin registrar, Usuario registrado, Administrador_ |
  | Descripción | _Ver los consejos de la aplicación_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---
  
  |  Caso de Uso	CU | Ver contenido |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Usuario sin registrar, Usuario registrado, Administrador_ |
  | Descripción | _Ver los contenidos de la aplicación_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

  |  Caso de Uso	CU | Subir contenido |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Usuario registrado, Administrador_ |
  | Descripción | _Subir contenido a la aplicación_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

  |  Caso de Uso	CU | Dar opinión |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Usuario registrado, Administrador_ |
  | Descripción | _Dar opinión sobre los consejos de la aplicación_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

  |  Caso de Uso	CU | Banear usuarios |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Administrador_ |
  | Descripción | _Banear a usuarios de la aplicación_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

  |  Caso de Uso	CU | Actualizar consejos |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Administrador_ |
  | Descripción | _Actualizar los consejos de la aplicación_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---
