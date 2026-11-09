# MGS Seguros Sierra de Grazalema — presentación local

Rediseño local completo en HTML5, CSS3, JavaScript vanilla y SVG. Entrada principal en `index.html`, compatible con Live Server.

## Datos locales

El nombre MGS Seguros Sierra de Grazalema, la actividad de agencia de seguros, el teléfono 665 15 82 31 y la dirección C. Jerez, 41, 11670 El Bosque, Cádiz proceden del encargo actualizado. Los enlaces telefónicos utilizan `tel:+34665158231` y Maps busca `Calle+Jerez+41+11670+El+Bosque+Cadiz`.

El vínculo comercial de esta oficina con la entidad permanece pendiente de verificación y se indica expresamente en el bloque de información de la aseguradora. La presentación utiliza la denominación facilitada y distingue los datos locales de los canales nacionales.

Las búsquedas oficiales por teléfono y dirección del 09/11/2026 carecieron de coincidencia inequívoca. Se consultó también el localizador público oficial mediante el código postal 11670. Su respuesta textual no permitió identificar la oficina. Estos intentos documentan el límite de la comprobación, sin acreditar representación o autorización de marca. La actividad concreta y los productos de esta oficina se consultan por el teléfono facilitado.

## Identidad de MGS

Fuentes oficiales consultadas el 09/11/2026.

- https://www.mgs.es/ confirma la denominación de la entidad MGS, Seguros y Reaseguros S.A.
- https://www.mgs.es/publica-17-theme/images/logo.svg contiene los colores #003082 y #FF8500.
- https://www.mgs.es/wps/portal/publica/avisolegal recoge la titularidad y protección de marca y contenidos, cuya reproducción requiere autorización expresa.
- https://www.mgs.es/wps/dondeencontrarnos ofrece el localizador de la red de atención.

La propuesta presenta el nombre mediante tipografía ordinaria. El favicon utiliza las iniciales geográficas SG. Se toman azul y naranja como referencias cromáticas, combinados con el blanco cálido #F7F5F1, azul noche #172C40, piedra #D9D9D5 y negro #24282B de la dirección artística local. La página atribuye a los canales nacionales la información de la entidad.

## Fotografía, tipografía y recursos

La imagen de portada es una escena arquitectónica generada con la herramienta integrada `image_gen`, identificada como ilustrativa y ajena a la oficina o a una situación asegurada. Original en `assets/images/originals/everyday-space.png`, variantes JPEG optimizadas a 768 y 1536 px. Prompt y correspondencias en `qa/image-generation-prompts.json`.

La fotografía local muestra El Bosque desde la carretera a Benamahoma. Obra de El Pantera, 2008, bajo CC BY-SA 4.0. Crédito y licencia visibles en la página, con detalle de las versiones optimizadas en `assets/images/PHOTO-LICENSE.md`. La fotografía representa el entorno local y se fecha expresamente.

Plus Jakarta Sans variable se aloja localmente. Procedencia en https://github.com/google/fonts/tree/main/ofl/plusjakartasans y licencia SIL OFL conservada en `assets/fonts/OFL-PlusJakartaSans.txt`.

## Comprobaciones

Vista previa local HTTP en el puerto 8793 con respuesta 200 verificada. Desde Landing webs, ejecutar `node mgs-seguros-sierra-de-grazalema/qa/preview-server.mjs` y luego `node mgs-seguros-sierra-de-grazalema/qa/browser-check.mjs`. Requiere Chrome instalado en su ruta estándar de Windows.

Chrome headless a 375, 390, 768, 1440 y 1920 px. Imágenes y fuente cargadas, contenido ajustado al ancho, navegación interna y foco por tabulador, controles principales con altura mínima de 44 px. Cero excepciones JavaScript detectadas y sintaxis comprobada mediante `node --check`. Movimiento reducido y lectura sin JavaScript comprobados. Pruebas de interacción con movimiento reducido. Revisión visual de imágenes y capturas de móvil, tablet y escritorio.

Comprobación de un H1 y una etiqueta `noindex, nofollow` en head. Enlaces de llamada, Maps y canales oficiales revisados por formato. Los externos llevan `target="_blank"` y `rel="noopener noreferrer"`. La comparación SHA-256 comprueba el alcance frente a las otras 13 webs. El trabajo se guarda localmente en esta carpeta. Safari y dispositivos físicos quedan pendientes de prueba.
