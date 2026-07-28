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

Desde `0.0.77`, si el paquete de trabajo entrega un proyecto QGIS `.qgz` junto
al GeoPackage, el plugin conserva sus formularios profesionales, pestañas y
relaciones al abrir una inconsistencia. Mantenga ambos archivos en la misma
carpeta. Si el `.qgz` no está disponible, QGIS muestra su formulario básico.

Desde `0.0.78`, Detalle de inconsistencias incorpora búsqueda por
manzana/NPN/PK, contador visible y un filtro persistente para ocultar registros
con excepción. El filtro viene activado de forma predeterminada y no altera las
exportaciones completas de la corrida.

Desde `0.0.79`, los filtros operativos se separan entre generales y específicos
para NPH, Condominio, PH/PH matriz e Informalidad. Las condiciones `0–9` son
personalizables. Además, cada plugin padre puede generar desde
**Exportar → Plugin hijo bloqueado (ZIP)** un perfil instalable, simplificado y
con sus reglas y filtros congelados.
