# Señales y Sistemas con MATLAB Live Script

## Teoría, simulación y aplicaciones para ingeniería

Bienvenido al módulo interactivo de **Señales y Sistemas con MATLAB Live Script**. Este material ha sido diseñado para apoyar el aprendizaje de estudiantes de ingeniería mediante teoría, simulación computacional, análisis gráfico y aplicaciones prácticas.

---

## Presentación

El estudio de señales y sistemas constituye una base fundamental para diversas áreas de la ingeniería, especialmente telecomunicaciones, electrónica, control, procesamiento digital de señales, instrumentación, automatización e inteligencia artificial aplicada.

Este módulo utiliza **MATLAB Live Script** como entorno de aprendizaje interactivo, permitiendo combinar texto académico, ecuaciones, código ejecutable, gráficos y resultados computacionales en un mismo documento. De esta manera, el estudiante puede analizar los conceptos matemáticos y, al mismo tiempo, comprobar su comportamiento mediante simulaciones.

---

## Objetivo general

Comprender, representar, analizar y simular señales y sistemas mediante herramientas matemáticas y computacionales, con énfasis en el uso de MATLAB para el análisis en el dominio del tiempo y de la frecuencia.

---

## Resultados de aprendizaje

Al finalizar el estudio del módulo, el estudiante será capaz de:

1. Representar señales continuas y discretas en el dominio del tiempo.
2. Clasificar señales según sus propiedades matemáticas y físicas.
3. Aplicar operaciones básicas sobre señales.
4. Calcular energía y potencia de señales.
5. Analizar propiedades fundamentales de sistemas.
6. Identificar sistemas lineales invariantes en el tiempo.
7. Aplicar la convolución para determinar la respuesta de sistemas LTI.
8. Analizar señales periódicas mediante Series de Fourier.
9. Interpretar señales en el dominio de la frecuencia.
10. Aplicar la Transformada de Fourier, Laplace y Z en el análisis de señales y sistemas.
11. Desarrollar simulaciones mediante MATLAB Live Script.
12. Resolver problemas aplicados a ingeniería mediante herramientas computacionales.

---

# Índice del módulo

## Bloque 1. Representación de señales en el dominio del tiempo

### Capítulo 1. Introducción a señales y sistemas

- Introducción general a la asignatura.
- Concepto de señal.
- Concepto de sistema.
- Importancia de señales y sistemas en ingeniería.
- Primer ejemplo en MATLAB Live Script.

### Capítulo 2. Clasificación de señales

- Señales continuas y discretas.
- Señales analógicas y digitales.
- Señales periódicas y no periódicas.
- Señales pares e impares.
- Señales determinísticas y aleatorias.
- Señales de energía y potencia.

### Capítulo 3. Señales elementales continuas y discretas

- Impulso unitario.
- Escalón unitario.
- Rampa unitaria.
- Señales exponenciales.
- Señales sinusoidales.
- Señales rectangulares y triangulares.

### Capítulo 4. Operaciones básicas con señales

- Desplazamiento temporal.
- Escalamiento temporal.
- Reflexión temporal.
- Escalamiento de amplitud.
- Suma, resta y multiplicación de señales.

### Capítulo 5. Energía y potencia de señales

- Energía de una señal.
- Potencia promedio.
- Señales de energía.
- Señales de potencia.
- Cálculo en señales continuas y discretas.

---

## Bloque 2. Sistemas lineales invariantes en el tiempo y convolución

### Capítulo 6. Introducción y clasificación de sistemas

- Definición matemática de sistema.
- Sistemas continuos y discretos.
- Sistemas con memoria y sin memoria.
- Sistemas causales y no causales.
- Sistemas estables e inestables.
- Sistemas lineales y no lineales.
- Sistemas invariantes y variantes en el tiempo.

### Capítulo 7. Sistemas lineales invariantes en el tiempo

- Concepto de sistema LTI.
- Linealidad.
- Principio de superposición.
- Invariancia en el tiempo.
- Importancia de los sistemas LTI.

### Capítulo 8. Respuesta al impulso

- Concepto de impulso unitario.
- Respuesta al impulso.
- Caracterización de sistemas LTI.
- Respuesta al impulso en sistemas continuos y discretos.

### Capítulo 9. Convolución discreta

- Definición de convolución discreta.
- Interpretación gráfica.
- Procedimiento paso a paso.
- Uso de la función `conv` en MATLAB.
- Aplicaciones en filtros digitales.

### Capítulo 10. Convolución continua

- Definición de convolución continua.
- Integral de convolución.
- Interpretación gráfica.
- Aproximación numérica en MATLAB.
- Aplicaciones en circuitos, comunicaciones y control.

---

## Bloque 3. Análisis en frecuencia y transformadas

### Capítulo 11. Introducción al dominio de la frecuencia

- Necesidad del análisis en frecuencia.
- Frecuencia, periodo y frecuencia angular.
- Amplitud y fase.
- Representación temporal y frecuencial.

### Capítulo 12. Series de Fourier

- Introducción a las Series de Fourier.
- Serie trigonométrica.
- Coeficientes de Fourier.
- Serie exponencial compleja.
- Fenómeno de Gibbs.
- Simulación en MATLAB.

### Capítulo 13. Transformada de Fourier

- Definición de la Transformada de Fourier.
- Transformada inversa.
- Propiedades principales.
- Transformada de señales básicas.
- Análisis espectral con MATLAB.

### Capítulo 14. Espectro de amplitud y fase

- Espectro de amplitud.
- Espectro de fase.
- Representación unilateral y bilateral.
- Transformada rápida de Fourier.
- Uso de la FFT en MATLAB.

### Capítulo 15. Transformada de Laplace

- Definición de la Transformada de Laplace.
- Región de convergencia.
- Transformada inversa.
- Función de transferencia.
- Polos y ceros.
- Estabilidad de sistemas continuos.

### Capítulo 16. Transformada Z y sistemas discretos

- Definición de la Transformada Z.
- Región de convergencia.
- Transformada Z inversa.
- Sistemas discretos en el dominio Z.
- Polos y ceros en el plano Z.
- Aplicaciones en filtros digitales.

---

## Bloque 4. Aplicaciones integradoras

### Capítulo 17. Aplicaciones en telecomunicaciones y procesamiento digital de señales

- Señales en sistemas de comunicación.
- Análisis de señales de audio.
- Filtrado básico.
- Ruido en señales.
- Simulación de filtros en MATLAB.
- Aplicaciones con sensores.

### Capítulo 18. Proyecto final integrador

- Planteamiento del problema.
- Selección de una señal de estudio.
- Análisis temporal.
- Análisis de energía y potencia.
- Análisis mediante convolución.
- Análisis en frecuencia.
- Interpretación de resultados.
- Presentación del Live Script final.

---

# Archivos del módulo

Los capítulos se desarrollarán progresivamente en formato **MATLAB Live Script**:

```text
live_scripts/
├── cap_01_introduccion_senales_sistemas.mlx
├── cap_02_clasificacion_senales.mlx
├── cap_03_senales_elementales.mlx
├── cap_04_operaciones_senales.mlx
├── cap_05_energia_potencia_senales.mlx
├── cap_06_clasificacion_sistemas.mlx
├── cap_07_sistemas_lti.mlx
├── cap_08_respuesta_impulso.mlx
├── cap_09_convolucion_discreta.mlx
├── cap_10_convolucion_continua.mlx
├── cap_11_dominio_frecuencia.mlx
├── cap_12_series_fourier.mlx
├── cap_13_transformada_fourier.mlx
├── cap_14_espectro_amplitud_fase.mlx
├── cap_15_transformada_laplace.mlx
├── cap_16_transformada_z.mlx
├── cap_17_aplicaciones_integradoras.mlx
└── cap_18_proyecto_final.mlx
