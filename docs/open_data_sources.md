# Fuentes de Datos Abiertos para el Proyecto Conexión Campo-Ciudad de Mercados Agroecológicos

Este informe presenta un análisis detallado de las principales fuentes de datos abiertos que pueden apoyar la implementación de una base de datos PostgreSQL para gestionar catálogos de productos agrícolas, órdenes de compra y logística de entrega entre productores rurales y consumidores urbanos.

## Fuentes de Datos Disponibles

La siguiente tabla recopila las principales fuentes de datos abiertos relevantes para el proyecto Conexión Campo-Ciudad, enfocándose en Bogotá y sus alrededores, así como otras regiones con información valiosa para el modelo de negocio agroecológico.

| Ciudad/Región | Fuente de Datos | URL de Acceso | Tipo de Datos | Categoría | Frecuencia de Actualización | Formato |
|---------------|-----------------|---------------|---------------|-----------|----------------------------|---------|
| Bogotá | Portal Datos Abiertos Bogotá | https://datosabiertos.bogota.gov.co/ | Datos geográficos, culturales, de inversión, estadísticos de la capital | Multisectorial (incluye agricultura y comercio) | Variable según conjunto de datos | Múltiples formatos de descarga[1] |
| Bogotá | Portal Datos para la Transparencia | https://gobiernoabiertobogota.gov.co/transparencia | Datos gubernamentales y de gestión pública | Transparencia, gestión pública | Periódica (no especificada) | No especificado[1] |
| Valle del Cauca | Secretaría de Desarrollo Rural, Agricultura y Pesca | https://www.valledelcauca.gov.co/agricultura/publicaciones/69735/datos-abiertos-secretaria-de-desarrollo-rural-agricultura-y-pesca/ | Consolidados agrícolas por municipios de cultivos transitorios y permanentes (2000-2021), Indicadores del Observatorio Agropecuario | Agricultura y desarrollo rural | Anual (con actualizaciones en septiembre 2023 y 2024) | No especificado[2] |
| Bogotá Región | Red de Mercados Agroecológicos | No disponible directamente | Información sobre productores agroecológicos, hortalizas, frutas, productos apícolas, pecuarios, alimentos procesados, medicinales | Agricultura ecológica | No especificada | No especificado[4] |
| Colombia (Nacional) | Portal de Datos Abiertos Colombia | https://www.datos.gov.co/ | Datos multisectoriales (incluye datos agrícolas, comerciales y logísticos) | Multisectorial | Variable según conjunto de datos | CSV, JSON, XML entre otros[5] |

### Características de los Datos de Portal Datos Abiertos Bogotá

El portal Datos Abiertos Bogotá ofrece más de 2.000 conjuntos de datos producidos por 70 entidades distritales de Bogotá[1]. Este portal renovó recientemente su imagen y herramientas de consulta, facilitando el acceso a datos geográficos y alfanuméricos agrupados por temática y entidad[1]. La plataforma está administrada por la Unidad Administrativa Especial de Catastro Distrital, en su rol de Coordinador de la Infraestructura de Datos Espaciales de Bogotá (Ideca)[1].

El proceso de consulta es sencillo:
1. Ingresar al portal https://datosabiertos.bogota.gov.co/
2. Buscar por conjunto de datos, entidad, palabra clave o temática
3. Visualizar la descripción del dato y opciones de consulta o descarga
4. Acceder a opciones de previsualización, licencia de uso y enlaces a otros recursos[1]

## Relevancia para el Proyecto Conexión Campo-Ciudad

### Datos Agrícolas y de Producción

La Secretaría de Desarrollo Rural, Agricultura y Pesca del Valle del Cauca ofrece datos particularmente relevantes para entender patrones de producción agrícola, con información consolidada de cultivos transitorios y permanentes entre 2000 y 2021, así como indicadores del Observatorio Agropecuario[2]. Estos datos permiten analizar tendencias de producción, estacionalidad y rendimientos que son fundamentales para la planificación de inventarios y catálogos de productos.

### Información sobre Mercados Agroecológicos

La Red de Mercados Agroecológicos de Bogotá Región cuenta con información sobre 200 productores, de los cuales 100 están certificados, abarcando un área total de 1,193 hectáreas[4]. Esta red maneja diversos productos relevantes para el proyecto:
- Hortalizas y frutas
- Productos apícolas
- Productos de origen pecuario
- Alimentos procesados
- Productos medicinales tradicionales[4]

### Beneficios de los Datos Abiertos para el Proyecto

El acceso a estos datos abiertos proporciona múltiples ventajas:
- Transparencia y rendición de cuentas
- Participación ciudadana
- Mejora y creación de nuevos productos y servicios
- Innovación
- Generación de conocimientos a partir de fuentes combinadas y análisis de grandes volúmenes de datos[5]

## Conclusión

Las fuentes de datos abiertos disponibles en Bogotá y otras regiones de Colombia ofrecen una base sólida para desarrollar el sistema PostgreSQL que conectará a productores rurales con consumidores urbanos. El Portal de Datos Abiertos Bogotá, junto con los datos específicos del sector agrícola del Valle del Cauca y la información sobre mercados agroecológicos, proporcionan el contexto necesario para optimizar la cadena de suministro campo-ciudad, garantizar precios justos y reducir desperdicios.

La implementación de la base de datos deberá integrar estos diversos conjuntos de datos, aprovechando especialmente la información geográfica, productiva y de mercado para crear un sistema eficiente que aborde la problemática identificada del 42% de pequeños productores sin acceso a mercados formales y el desperdicio del 18% de las cosechas.

Citations:
[1] https://www.catastrobogota.gov.co/noticia/datos-abiertos-bogota-acceso-libre-y-gratuito-los-datos-geograficos-y-alfanumericos
[2] https://www.valledelcauca.gov.co/agricultura/publicaciones/69735/datos-abiertos-secretaria-de-desarrollo-rural-agricultura-y-pesca/
[3] https://www.agencialogistica.gov.co/transparencia-y-acceso-a-la-informacion-publica/7-datos-abiertos/
[4] https://pgs.ifoam.bio/pgs_groups/377
[5] https://gobiernodigital.mintic.gov.co/692/w3-propertyvalue-47237.html
[6] https://bogota.gov.co/mi-ciudad/gestion-publica/datos-abiertos-en-bogota
[7] https://www.minagricultura.gov.co/SIG/DocumentosSIG/5GESTION_DE_INFORMACION_Y_DEL_CONOCIMIENTO/Procedimiento-Identificaci%C3%B3n-de-Datos-Abiertos-V1.pdf
[8] https://www.acueducto.com.co/wps/portal/EAB2/Home/transparencia_informacion_publica/datos_abiertos/que+son+los+datos+abiertos
[9] https://sembrandoconfianza.com/red-de-mercados-agroecologicos-de-bogota-region/
[10] https://www.colombiacompra.gov.co/transparencia/gestion-documental/datos-abiertos
[11] https://historico.gobiernobogota.gov.co/content/datos-abiertos
[12] https://herramientas.datos.gov.co/taxonomy/term/3
[13] https://bogota.gov.co/que-hacer/ambiente/mercados-campesinos-agroecologicos-de-bogota-6-y-7-de-julio-2024
[14] https://www.datos.gov.co
[15] https://desarrolloeconomico.gov.co/seccion-datos-abiertos/
[16] https://gobiernodigital.mintic.gov.co/portal/238768:Datos-Abiertos
[17] https://datosabiertos.bogota.gov.co
[18] https://www.sic.gov.co/bases-y-repositorios-bibliograficos-de-libre-acceso
[19] https://scj.gov.co/es/transparencia/datos-abiertos/seccion-datos-abiertos
[20] https://www.habitatbogota.gov.co/transparencia/datos-abiertos/seccion-de-datos-abiertos
[21] https://www.minagricultura.gov.co/Paginas/Datos-Abiertos.aspx
[22] https://es.semrush.com/trending-websites/co/transportation-and-logistics
[23] https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Datos-Abiertos-Agricola-y-Fertilizantes/y2zk-c694
[24] https://www.datos.gov.co/Educaci-n/LOGISTICA/npby-7tdt
[25] https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Evaluaciones-Agropecuarias-Municipales-EVA/2pnw-mmge
[26] https://datosabiertos.bogota.gov.co/dataset?organization=sdm
[27] https://gobiernoabiertobogota.gov.co
[28] https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Base/66x9-24rb
[29] https://datosabiertos.bogota.gov.co/dataset/c7510af3-0ba6-4cbe-8edb-aa53ccaccc3f/resource/9caf245c-b697-4ab5-b20b-6a508f5ac721
[30] https://jbb.gov.co/generacion-de-conocimiento/mercado-campesino-agroecologico/
[31] https://www.datos.gov.co/w/jdnt-rxts/dneh-mcp2?cur=jXMkfG9gGqX&from=ke2ySF65DJv
[32] https://jbb.gov.co/nueva-jornada-de-mercados-campesinos-agroecologicos-en-el-jardin-botanico-de-bogota/
[33] https://www.datos.gov.co/w/v29b-znjj/dneh-mcp2?cur=4V1MdsUN1-s
[34] https://www.datos.gov.co/en/en/dataset/Mercados-campesinos-en-Bogot-por-localidades/jdnt-rxts
[35] https://datos.icde.gov.co
[36] https://siac-datosabiertos-mads.hub.arcgis.com

---
Respuesta de Perplexity: pplx.ai/share
