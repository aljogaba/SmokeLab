# EXP-002 — Notas de desarrollo y oportunidades metodológicas

**Experimento:** Costilla y aldilla de cerdo — humo ligero y acabado dual  
**Fecha del experimento:** 18 de octubre de 2026  
**Fecha de incorporación al sitio:** 18 de octubre de 2026  
**Estado:** Fase I documentada; Fase II pendiente  
**Autor:** Alberto Jorge Galindo Barboza

## 1. Qué se incorporó al proyecto

Se dio de alta EXP-002 respetando la arquitectura existente de Smoke Lab y sin modificar la lógica de EXP-001. Se incorporaron:

- expediente público `experiments/exp-002-costilla-aldilla.html`;
- entrada en el índice de experimentos;
- expediente de laboratorio para EXP-002;
- registro térmico;
- registro de evaluación sensorial;
- sección Smoke Science específica del ensayo;
- apartado `Coming up` para mantener abierta la Fase II;
- estructura de galería fotográfica con rutas estables para sustitución posterior de PNG.

## 2. Información experimental documentada

La Fase I registra fecha, hora de inicio, peso inicial, anatomía/presentación del corte, división de piezas, binder, formulación y cantidades del rub, especie de madera y aproximación de cantidad utilizada, temperatura de cámara, disposición por niveles, temperaturas internas observadas, momento de envoltura, volumen aproximado de vino blanco por paquete, cambios de temperatura de cámara, decisión de acelerar la cocción, acabado natural/BBQ, observación post-servicio y resultados sensoriales.

También se documentan explícitamente las limitaciones de interpretación: anatomía y posición en el ahumador quedaron confundidas; la porción sometida a 20–25 minutos adicionales no fue un control experimental; y la banda rosada observada se describe como compatible visualmente con smoke ring, no como demostración de su mecanismo.

## 3. Hallazgos que deben conservarse para futuros experimentos

EXP-002 mostró que el sistema actual ya puede documentar mucho más que una receta. La evaluación sensorial permitió triangular una oportunidad de mejora: sabor, humo y corteza fueron altamente aceptados, mientras la terneza mostró mayor margen de optimización. La observación post-cocción sugiere evaluar mayor tiempo térmico y evitar que la hora de servicio obligue a acelerar el final.

La Fase II permitirá estudiar conservación, descongelación, regeneración térmica y acabado diferido. Debe tratarse como continuación del mismo experimento, no como un experimento independiente, salvo que el diseño cambie sustancialmente.

## 4. Campos que conviene estandarizar desde los próximos experimentos

### Identificación y contexto
- ID del experimento y fase.
- fecha y horas de inicio, cambios de fase, retiro y servicio.
- objetivo e hipótesis antes de iniciar.
- número de comensales/evaluadores y tipo de panel.

### Materia prima
- corte anatómico con nomenclatura local y, cuando sea posible, equivalencia técnica.
- peso total y peso individual de cada pieza.
- espesor o dimensiones relevantes.
- condición inicial: refrigerada/descongelada y temperatura interna inicial.
- recorte de grasa, membranas u otras modificaciones.

### Sazonado
- binder: tipo y cantidad aproximada.
- formulación del rub en gramos y, preferentemente, también como porcentaje del peso de carne.
- tiempo entre aplicación del rub y entrada al ahumador.
- salsas, líquidos y otros ingredientes con marca/formulación cuando sea relevante para reproducibilidad.

### Combustible y humo
- especie de madera.
- masa de madera utilizada en gramos, además de descripción física.
- dimensiones aproximadas de los trozos.
- humedad/estado de la madera cuando pueda medirse o clasificarse.
- combustible base y método de encendido.
- momento de incorporación de la madera y duración aproximada de humo visible.
- descripción cualitativa del humo cuando sea pertinente.

### Equipo y ambiente térmico
- ahumador utilizado.
- posición exacta de cada pieza y nivel/parrilla.
- temperatura de cámara idealmente a nivel de parrilla además del termómetro de tapa.
- temperatura ambiente y condiciones meteorológicas relevantes.
- aperturas de tapa y cambios importantes de combustible/ventilación.

### Seguimiento de cada pieza
- asignar identificadores individuales (p. ej. R1, R2, A1, A2).
- registrar temperatura interna por pieza, no solo por tipo de corte.
- hora de cada medición.
- criterio de cambio de fase.
- prueba de resistencia de sonda/probe tenderness con escala o descriptor estandarizado.
- temperatura y condición al retiro.
- tiempo de reposo por pieza.

### Envoltura y fase húmeda
- hora y temperatura interna al envolver.
- material de envoltura.
- líquido añadido y volumen exacto.
- integridad del paquete y pérdidas observadas.
- tiempo total envuelto.

### Acabado
- natural/BBQ u otro tratamiento.
- temperatura o intensidad aproximada del fuego.
- duración del acabado.
- número de volteos.
- cantidad aproximada de salsa.
- criterio visual/táctil de finalización.

### Rendimiento
- peso cocido final.
- pérdida de peso absoluta y porcentual.
- peso de porción comestible cuando sea útil.
- rendimiento por corte/pieza.

### Evaluación sensorial
Mantener como mínimo: terneza, jugosidad, sabor general, aroma de humo, intensidad de humo, corteza/acabado y evaluación global. Conservar preferencia entre tratamientos y comentario abierto. Registrar si el panel es entrenado/no entrenado, ciego/no ciego y tamaño `n`.

En experimentos comparativos futuros conviene codificar las muestras para reducir sesgo y separar, cuando sea posible, evaluación de costilla y aldilla en lugar de calificarlas como un único producto.

### Registro fotográfico
Definir fotografías mínimas obligatorias: materia prima, preparación/rub, colocación inicial, mitad de cocción, punto de envoltura, apertura del paquete, acabado, pieza completa terminada, corte transversal y evidencia de observaciones especiales. Mantener nombres de archivo vinculados al ID del experimento y fase.

## 5. Áreas de mejora del sistema Smoke Lab

1. **Pasar de cronología narrativa a datos por pieza.** EXP-002 demuestra que piezas anatómicamente distintas pueden evolucionar a velocidades diferentes. El registro debe permitir curvas térmicas individuales.
2. **Separar variables planeadas de desviaciones.** Registrar protocolo previsto y, por separado, ajustes durante la ejecución (por ejemplo, aceleración por horario de servicio). Esto permite aprender de las desviaciones sin reescribir retrospectivamente el protocolo.
3. **Incorporar rendimiento gravimétrico.** Peso crudo y cocido permitirá comparar retención de humedad/rendimiento entre técnicas.
4. **Estandarizar la madera por masa.** La descripción “medio trozo de ~10 cm de diámetro” es útil, pero insuficiente para replicación. La masa y, eventualmente, humedad de la madera mejorarían comparabilidad.
5. **Medir el microambiente real.** Incorporar sonda de cámara a nivel de parrilla ayudaría a separar la lectura de tapa de la exposición térmica efectiva.
6. **Formalizar decisiones por textura.** Temperatura interna debe permanecer como guía; el endpoint debe incorporar probe tenderness y observaciones de tejido conectivo.
7. **Fortalecer diseño sensorial.** Para comparaciones natural vs BBQ o técnicas futuras, usar porciones codificadas y evaluación separada por tratamiento/corte cuando el objetivo sea comparar.
8. **Conservar observaciones inesperadas.** El hallazgo post-servicio de EXP-002 muestra que las observaciones no planeadas pueden generar la hipótesis del siguiente ensayo. Debe existir un campo formal `Observaciones emergentes / hipótesis generadas`.
9. **Experimentos por fases.** Incorporar estado de fase (planificada, en curso, completada, seguimiento pendiente) para experimentos longitudinales como conservación/regeneración.
10. **Distinguir evidencia de interpretación.** Mantener separados datos medidos, percepción sensorial, interpretación técnica e hipótesis. Esta distinción debe ser una regla editorial de Smoke Lab.

## 6. Campos recomendados para la plantilla maestra v2

La próxima evolución de `experiment-template.html` debería contemplar, sin obligar a mostrar todos los campos públicamente: identificación; objetivo; hipótesis; materia prima; preparación; rub; combustible/madera; equipo; ambiente; mapa de posición de piezas; protocolo previsto; cronología real; registro térmico por pieza; desviaciones del protocolo; envoltura; acabado; reposo; rendimiento; evaluación sensorial; registro fotográfico; Smoke Science; observaciones emergentes; limitaciones; interpretación; oportunidades de mejora; seguimiento/Coming up; archivos de datos asociados.

## 7. Pendientes específicos de EXP-002

- Incorporar los PNG definitivos en `assets/img/experiments/exp-002/`.
- Registrar cómo y cuándo se enfrían/congelan las piezas reservadas.
- Registrar duración real de almacenamiento congelado.
- Documentar descongelación.
- Ejecutar y registrar regeneración a fuego bajo.
- Separar acabado natural y BBQ según se decida.
- Repetir evaluación sensorial de Fase II.
- Comparar cualitativamente Fase I vs Fase II, dejando claro que no constituye un ensayo controlado si las condiciones no son equivalentes.
- Al cerrar Fase II, actualizar el veredicto provisional y decidir qué campos pasan formalmente a la plantilla maestra v2.

## 8. Regla editorial derivada de EXP-002

Smoke Lab debe documentar no solo **qué se hizo**, sino también **qué estaba planeado, qué cambió durante la cocción, qué se observó, qué puede afirmarse con los datos, qué no puede afirmarse y qué pregunta queda para el siguiente ensayo**. Esa estructura convierte la bitácora culinaria en una plataforma acumulativa de experimentación y aprendizaje.