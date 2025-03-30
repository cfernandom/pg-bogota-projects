# Fuentes de Datos Abiertos para Proyecto Conexión Campo-Ciudad de Mercados Agroecológicos

Esta tabla estructurada presenta fuentes de datos abiertos relevantes para implementar una base de datos PostgreSQL que gestione catálogos de productos agrícolas, órdenes de compra y logística de entrega, optimizando la cadena de suministro campo-ciudad para mercados agroecológicos.

## Fuentes de Datos Principales

| Ciudad/Región | Fuente de Datos | URL de Acceso | Tipo de Datos | Categoría | Frecuencia de Actualización | Formato |
|---------------|-----------------|---------------|---------------|-----------|----------------------------|---------|
| Colombia | Ministerio de Agricultura y Desarrollo Rural | https://www.datos.gov.co | Datos primarios del sector agropecuario sin procesar, puestos a disposición bajo la Ley de Transparencia 1712 de 2014 | Agricultura, Desarrollo Rural | Variable (según conjunto de datos) | CSV, JSON (formatos estándar e interoperables)[2] |
| Colombia | Agencia de Desarrollo Rural | https://www.adr.gov.co/transparencia/datos-abiertos/ | Predios Beneficiarios PIDAR, Usuarios de proyectos registrados, Costos iniciativas, Perfiles de proyectos inscritos, Ciudades beneficiarias, Distritos de Riego activos | Agricultura, Desarrollo Rural | Anual (referencia a "vigencia 2020") | No especificado[3] |
| Castilla y León, España | Junta de Castilla y León - Sistema de Información Estadística | https://datosabiertos.jcyl.es/web/jcyl/set/es/medio-rural-pesca/agricultura/1284801509249 | Explotaciones agrarias, superficies agrarias, familiares trabajadores en explotaciones, margen bruto, maquinaria agrícola y unidades ganaderas desglosados por año y municipio | Agricultura, Estadística | Anual (datos estadísticos históricos) | API para consultas personalizadas[4] |
| Bogotá, Colombia | Secretaría de Desarrollo Económico - Mercados Campesinos | https://mercadoscampesinos.gov.co | Registro de productores y organizaciones campesinas, emprendedores de proyectos agroproductivos de la Región Central (Bogotá, Cundinamarca, Boyacá, Meta, Tolima y Huila) | Agricultura Urbana, Comercialización | Continua (registro permanente) | Formularios web (Google Forms)[5] |
| Madrid, España | Centro Logístico de Productores Agroecológicos (MAR de Alimentación) | No especificado directamente | Información sobre cooperativas hortícolas, pequeñas agroindustrias, asociaciones de tiendas ecológicas y abastecimiento común de la bio-región de Madrid | Logística Alimentaria, Cadena de Suministro | Mensual (reuniones mencionadas) | No especificado[6] |
| España | Red de Municipios por la Agroecología | https://www.municipiosagroeco.red/espacios-de-intercambio/ | Información sobre gobernanza alimentaria, asesoría a iniciativas productivas, acceso a tierra, redes locales de logística y distribución, compra pública alimentaria | Políticas Alimentarias, Gobernanza, Logística | Periódica (eventos y seminarios) | Recursos web, documentos técnicos[1] |

## Recursos Específicos para Logística y Distribución

| Ciudad/Región | Fuente de Datos | URL de Acceso | Tipo de Datos | Categoría | Frecuencia de Actualización | Formato |
|---------------|-----------------|---------------|---------------|-----------|----------------------------|---------|
| Bogotá, Colombia | Jardín Botánico de Bogotá - Programa de Agricultura Urbana | https://bogota.gov.co/mi-ciudad/desarrollo-economico/participar-en-mercados-agroecologicos-de-noviembre-en-jardin-botanico | Datos sobre huerteros urbanos y periurbanos, productos frescos y procesados, participantes en mercados agroecológicos "Bogotá es mi huerta" | Agricultura Urbana, Comercialización | Mensual (mercados mensuales) | Formularios de registro web[5] |
| Madrid, España | Estrategia de Alimentación Saludable y Sostenible 2018-2021 | No especificado directamente | Información sobre modelos de distribución de productores a grupos de consumo, nodos de distribución, logística y optimización de intercambios de mercancías | Logística Alimentaria, Planificación Urbana | No especificado | No especificado[6] |

## Consideraciones Técnicas para la Implementación

Para implementar efectivamente la base de datos PostgreSQL que gestione catálogos de productos agrícolas, órdenes de compra y logística de entrega, se recomienda:

1. Acceder directamente a cada portal para verificar formatos específicos de descarga y APIs disponibles
2. Diseñar procesos ETL (Extracción, Transformación y Carga) adecuados para cada fuente
3. Establecer mecanismos para actualización periódica según la frecuencia de cada fuente
4. Considerar la integración con sistemas geoespaciales para la optimización de rutas de distribución
5. Implementar estructuras de datos que faciliten el análisis de precios, disponibilidad y estacionalidad de productos

Esta selección de fuentes de datos abiertos proporcionará información valiosa para el desarrollo del proyecto de conexión campo-ciudad, permitiendo optimizar la cadena de suministro y facilitar el acceso directo entre productores agroecológicos y consumidores urbanos.

Citations:
[1] https://www.municipiosagroeco.red/espacios-de-intercambio/
[2] https://www.minagricultura.gov.co/Paginas/Datos-Abiertos.aspx
[3] https://www.adr.gov.co/transparencia/datos-abiertos/
[4] https://datosabiertos.jcyl.es/web/jcyl/set/es/medio-rural-pesca/agricultura/1284801509249
[5] https://bogota.gov.co/mi-ciudad/desarrollo-economico/participar-en-mercados-agroecologicos-de-noviembre-en-jardin-botanico
[6] https://www.fontagro.org/new/uploads/productos/16108_-_Producto_2_4.pdf
[7] https://www.valledelcauca.gov.co/agricultura/publicaciones/69735/datos-abiertos-secretaria-de-desarrollo-rural-agricultura-y-pesca/
[8] https://www.municipiosagroeco.red
[9] https://sioc.minagricultura.gov.co/DocumentosContexto/S3877-Plan%20Nacional%20de%20Agrolog%C3%ADstica.pdf
[10] https://www.mapa.gob.es/es/estadistica/temas/estadisticas-agrarias/agricultura/superficies-producciones-anuales-cultivos/
[11] https://mercado-agroecologico.utp.edu.co
[12] https://www.fontagro.org/new/uploads/productos/16108_-_Producto_2_13.pdf
[13] https://datos.gob.es/es/documentacion/como-los-datos-abiertos-pueden-impulsar-el-sector-agricola-y-forestal
[14] https://herramientas.datos.gov.co/taxonomy/term/3
[15] https://herramientas.datos.gov.co/noticias/datos-abiertos-en-colombia
[16] http://www.fao.org/statistics/es
[17] https://www.juntadeandalucia.es/agriculturaypesca/ifapa/riaweb/web/datosabiertos
[18] http://infoandina.org/infoandina/sites/default/files/forum_topic/files/lectura_3_caracterizacicn_de_mercados_locales_macas_y_echarry.pdf
[19] https://repositorio.cepal.org/bitstream/handle/11362/47208/1/CEPAL-FAO21-22_es.pdf
[20] https://www.ecosur.mx/mercados-agroecologicos-en-colombia-destacados-por-afectividad-y-precios-justos%EF%BF%BC/
[21] https://datos.gob.es/es/doc-tags/agricultura
[22] https://datosabiertos.bogota.gov.co/dataset/huertas-de-agricultura-urbana
[23] https://www.datos.gov.co/api/views/2xnf-ye6y/rows.csv?accessType=DOWNLOAD
[24] https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Base/66x9-24rb
[25] https://www.ine.es/dyngs/INEbase/es/categoria.htm?c=Estadistica_P
[26] https://datos.gob.es/es/blog/aplicaciones-de-la-ciencia-de-datos-abiertos-para-la-agricultura
[27] https://geoportal.igac.gov.co/contenido/datos-abiertos-agrologia
[28] https://www.datos.gov.co
[29] https://www.dnp.gov.co/Prensa_/Podcast/Paginas/del-campo-a-la-ciudad-la-alternativa-sostenible-de-dona-rosita.aspx
[30] https://datos.icde.gov.co/search?collection=Dataset&tags=ordenamiento+ambiental
[31] https://www.datos.gov.co/Ambiente-y-Desarrollo-Sostenible/Negocios-Verdes/nyug-ff48/data
[32] https://www.datos.gov.co/api/views/4t9r-7v7i/rows.csv?accessType=DOWNLOAD
[33] https://datosabiertos.bogota.gov.co/dataset/huertas-de-agricultura-urbana/resource/faccda81-efbe-4e53-b3cf-05cdff642571
[34] https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Datos-Abiertos-Agricola-y-Fertilizantes/y2zk-c694

---
Respuesta de Perplexity: pplx.ai/share
