# Valuación-Fibra-Mty-NAV

## Descripción del proyecto
Este proyecto tiene como objetivo estimar el valor intrínseco aproximado del CBFI de Fibra Monterrey mediante un modelo de valuación basado en NAV ajustado, utilizando el NOI del portafolio y distintos escenarios de tasa de capitalización (cap rate).

El análisis busca responder la siguiente pregunta:
¿El precio actual del CBFI de Fibra Monterrey refleja un descuento frente a su valor intrínseco, o el mercado ya reconoce plenamente el valor del portafolio inmobiliario?

## Metodología
El modelo de valuación se basa en los siguientes pasos:

1. Anualización del NOI a partir del ION trimestral.
2. Estimación del Valor Empresa (EV) mediante la fórmula:
   
   EV = NOI / Cap Rate

3. Cálculo del NAV ajustado:

   NAV = EV - Deuda Neta

4. Cálculo del NAV por CBFI:

   NAV/CBFI = NAV / CBFIs en circulación

5. Comparación del NAV por CBFI contra el precio de mercado actual.
6. Cálculo del cap rate implícito de mercado.

## Resultados principales
- El cap rate implícito de mercado se ubica aproximadamente entre 6.8% y 7.0%.
- Bajo escenarios de cap rate base y conservador, el NAV estimado por CBFI es menor al precio de mercado actual.
- Esto sugiere que el mercado valúa a Fibra Monterrey con un cap rate bajo, consistente con un portafolio de alta calidad.

## Conclusión
El análisis sugiere que Fibra Monterrey no se encuentra claramente infravalorada bajo escenarios de cap rate conservadores. El precio actual parece reflejar un escenario optimista en términos de tasa de capitalización, por lo que el potencial de apreciación dependería principalmente del crecimiento del NOI y futuras adquisiciones.

## Herramientas utilizadas
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Autor
Pedro Ortega Bringas — Proyecto de análisis financiero y valuación inmobiliaria.
