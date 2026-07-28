# Proyecto Gestor — plugins QGIS

Repositorio público de distribución de los plugins QGIS del Proyecto Gestor.

## Instalar o actualizar desde QGIS

Agregue esta dirección en **Complementos → Administrar e instalar
complementos → Configuración → Repositorios de complementos**:

```text
https://github.com/Gisdeveloper95/Proyecto_gestor_qgis_plugins/releases/latest/download/plugins.xml
```

El catálogo XML siempre corresponde al último release publicado y cada versión
conserva sus seis ZIP históricos sin sobrescritura.

Los plugins Calidad GPKG funcionan con GeoPackage o con capas vectoriales
cargadas en QGIS y no requieren acceso a PostgreSQL.
