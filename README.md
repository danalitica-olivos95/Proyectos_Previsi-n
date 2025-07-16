# Proyectos_Prevision.
Proyecto que comprende el negocio con el área de Previsión Exequial, identificando fuentes clave y necesidades analíticas prioritarias.
# Diccioenario de datos.

| Nombre del Campo                | Tipo de Dato | Descripción                                                           | Ejemplo               |
| ------------------------------- | ------------ | --------------------------------------------------------------------- | --------------------- |
| `Contrato`                      | Texto        | Número o código único que identifica el contrato del afiliado         | `C20230415`           |
| `Cedula`                        | Numérico     | Número de documento del contratante o titular                         | `1032456789`          |
| `Nombre_Contratante`            | Texto        | Nombre completo del contratante                                       | `Carlos Pérez`        |
| `Documento_Titular`             | Numérico     | Número de documento del titular del servicio                          | `9876543210`          |
| `Nombre_Titular`                | Texto        | Nombre completo del titular del servicio                              | `Marta Gómez`         |
| `Teléfono_1`                    | Texto        | Teléfono principal de contacto                                        | `6013456789`          |
| `Teléfono_2`                    | Texto        | Teléfono secundario de contacto                                       | `3156789876`          |
| `Celular`                       | Texto        | Número de celular informado                                           | `3201234567`          |
| `Correo_electrónico`            | Texto        | Correo electrónico principal                                          | `ejemplo@mail.com`    |
| `Nit_Entidad`                   | Texto        | NIT de la entidad que gestiona el contrato                            | `900123456-7`         |
| `Entidad`                       | Texto        | Nombre de la entidad                                                  | `Colsubsidio`         |
| `Celular_Imputado`              | Texto        | Celular sugerido por imputación (fuente externa)                      | `3001234567`          |
| `Correo_electrónico_verificada` | Booleano     | Indica si el correo fue validado correctamente                        | `TRUE` / `FALSE`      |
| `Telefono_1_tipo`               | Texto        | Clasificación del teléfono 1 (Ej: fijo, móvil, call center, genérico) | `Fijo` / `Móvil`      |
| `Telefono_1_origen`             | Texto        | Fuente del teléfono 1 (manual, web, imputado, etc.)                   | `Manual` / `Imputado` |
| `Telefono_2_tipo`               | Texto        | Clasificación del teléfono 2                                          | `Genérico` / `Móvil`  |
| `Telefono_2_origen`             | Texto        | Fuente del teléfono 2                                                 | `SAP` / `Digitado`    |
| `Prefijo`                       | Texto        | Prefijo geográfico del teléfono (Ej: 601 para Bogotá)                 | `601`                 |
| `Operador`                      | Texto        | Nombre del operador celular                                           | `Claro` / `Movistar`  |

