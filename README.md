# Desafío: Modelado con Ecuaciones Diferenciales - Bienestar Animal y Refugios

**Estudiante:** Pabel Dante Churata Apaza
**CI:** 9230639
**Mención:** Desarrollo de Software e Innovación

## Descripción del Problema
Este proyecto propone un modelo matemático para analizar y proyectar la evolución de adopciones de mascotas en refugios locales, aportando al bienestar animal[cite: 1]. El objetivo es proporcionar una herramienta que permita simular cómo crece el número de adopciones en el tiempo, ayudando a las organizaciones a gestionar sus recursos y medir la efectividad de sus campañas[cite: 1].

## Modelo Matemático
El modelo se basa en una Ecuación Diferencial Ordinaria (EDO) de primer orden con condición inicial[cite: 1]. 

* **Variable dependiente ($y$):** Número de mascotas adoptadas.
* **Variable independiente ($t$):** Tiempo (meses o semanas).
* **Parámetros:** Tasa constante de adopción ($k$) y población máxima de mascotas buscando hogar ($M$).
* **Ecuación Diferencial:** $\frac{dy}{dt} = k(M - y)$
* **Condición Inicial:** $y(0) = y_0$ (Mascotas adoptadas al inicio del registro)[cite: 1].

## Métodos Numéricos y Análisis
La aplicación resuelve esta ecuación y realiza un análisis comparativo utilizando[cite: 1]:
1. **Solución Analítica:** Para obtener los valores exactos y verificar el modelo[cite: 1].
2. **Método de Heun (RK2):** Como primera aproximación numérica[cite: 1].
3. **Método de Runge-Kutta de 4.º orden (RK4):** Como método de alta precisión[cite: 1].
*Se incluyen los cálculos de error absoluto y relativo porcentual para evaluar la precisión de ambos métodos frente a la solución exacta*[cite: 1].

## Instrucciones de Ejecución
Para visualizar e interactuar con la simulación, existen dos opciones[cite: 1]:

**Opción 1: Ejecución Online (Recomendada)**
1. Haz clic en el enlace de GitHub Pages proporcionado en la entrega.
2. La aplicación es completamente funcional en el navegador y no requiere instalación[cite: 1].

**Opción 2: Ejecución Local**
1. Clona este repositorio en tu computadora usando `git clone`.
2. Ve a la carpeta del proyecto.
3. Haz doble clic en el archivo `index.html` para abrirlo en cualquier navegador web moderno (Chrome, Edge, Firefox, etc.).
4. Ingresa los parámetros, el tamaño de paso $h$ y el tiempo de simulación en la interfaz, y presiona el botón para generar las gráficas y tablas.<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0cfc260e-429d-493e-bd45-d2585e9156a9" />
