# Preguntas Frecuentes (FAQ)

## Generales

### ¿Cuál es el objetivo principal de este proyecto?
Desarrollar modelos predictivos precisos para identificar factores de riesgo y predecir la probabilidad de desarrollo de cuatro enfermedades principales en mujeres: diabetes, cáncer, enfermedad hepática y enfermedad tiroidea.

### ¿De dónde provienen los datos utilizados?
Los datos utilizados son sintéticos basados en patrones epidemiológicos reales. No corresponden a pacientes reales, aunque mantienen las correlaciones y distribuciones típicas de las variables de interés en poblaciones femeninas.

## Aspectos Técnicos

### ¿Por qué se eligieron diferentes algoritmos para las distintas enfermedades?
Cada enfermedad presenta patrones únicos en los datos. Tras realizar pruebas comparativas, se seleccionó el algoritmo que ofrecía mejor rendimiento para cada condición específica.

### ¿Cómo se manejaron los desbalances en las clases?
Se aplicaron técnicas de sobremuestreo (SMOTE) y submuestreo para equilibrar las clases y mejorar el rendimiento de los modelos en enfermedades de baja prevalencia.

### ¿Es posible aplicar estos modelos a poblaciones masculinas?
No. Los modelos fueron específicamente entrenados con datos de población femenina y consideran factores biológicos específicos de mujeres. La aplicación a población masculina requeriría un rediseño completo.

## Uso y Limitaciones

### ¿Estos modelos pueden utilizarse en entornos clínicos reales?
No. Estos modelos son herramientas de investigación y no están validados para uso clínico. Cualquier aplicación práctica requeriría validación clínica rigurosa, aprobación regulatoria y supervisión médica.

### ¿Cuáles son las principales limitaciones de los modelos?
- No consideran interacciones medicamentosas
- Limitada representación de grupos minoritarios en ciertos segmentos
- No incorporan factores genéticos detallados
- Precisión variable dependiendo del grupo etario

### ¿Se puede acceder a los datos de entrenamiento?
No. Por razones de privacidad y condiciones de la licencia, los datos no están disponibles públicamente.

## Soporte

### ¿Cómo puedo reportar errores o problemas?
Los problemas pueden ser reportados a través del sistema de issues del repositorio, aunque dado que el código es de visualización únicamente, no se garantiza soporte técnico.

### ¿Existe documentación adicional disponible?
Sí, toda la documentación relevante se encuentra en los archivos del repositorio. Para detalles específicos de implementación, consulte los comentarios dentro de cada notebook.