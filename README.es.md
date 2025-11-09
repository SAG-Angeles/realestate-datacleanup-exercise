<!--hide-->
# Proyecto final del prework - Guía paso a paso
<!--endhide-->

- Comprender un dataset nuevo.
- Utilizar los conocimientos adquiridos en el prework para resolver las cuestiones planteadas.
- Analizar, si fuera necesario, otras cuestiones.

<onlyfor saas="false" withBanner="false">

## 🌱  Cómo iniciar este proyecto

Sigue las siguientes instrucciones:

1. Crear un nuevo repositorio haciendo fork en el [proyecto de Git](https://github.com/4GeeksAcademy/realestate-datacleanup-exercise) o [haciendo clic aquí](https://github.com/4GeeksAcademy/realestate-datacleanup-exercise/fork).
2. Abre el repositorio creado recientemente en Codespace usando la [extensión del botón de Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Una vez que el VSCode del Codespace haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

</onlyfor>


## 📝 Instrucciones

1. Una vez que comiences a trabajar en el proyecto, verás un fichero `./project.es.ipynb` que contiene una serie de ejercicios.
2. Antes de iniciar, asegúrate de seleccionar el **Kernel adecuado**. 

    - Al abrir el notebook, aparecerá un mensaje en la parte superior indicando **"Select Kernel"**.  
    - Haz clic en **"Select Kernel"** (como se muestra en la imagen).       


![image-kernel](assets/image-kernel.png)

3. Se mostrará una lista con las opciones disponibles. Selecciona **"Python Environments"** y elige la versión de Python que deseas utilizar.  

    - Asegúrate de seleccionar la versión especificada en el archivo `devcontainer.json`, ya que esta es la recomendada para el proyecto.


![image-devcontainer](assets/devcontainer-image.png)

4. **Instalación de librerías necesarias**
   Para comenzar a trabajar en este proyecto, asegúrate de instalar las librerías requeridas. Esto se puede hacer fácilmente ejecutando el siguiente comando en tu terminal, en la carpeta donde se encuentra el archivo `requirements.txt`:

   ```bash
   pip install -r requirements.txt

5. **Repaso de librerías**  
   Antes de comenzar con el ejercicio, es crucial que realices un repaso exhaustivo sobre las librerías `pandas` y `numpy`. Asegúrate de comprender bien las siguientes áreas:

   - **Funciones y Sintaxis**: Familiarízate con las funciones más comunes de cada librería. Por ejemplo:
     - **Pandas**:
       - `pd.read_csv()`: Para cargar datos desde un archivo CSV.
       - `DataFrame.describe()`: Para obtener estadísticas descriptivas de un DataFrame.
       - `DataFrame.groupby()`: Para agrupar datos y aplicar funciones agregadas.
     - **NumPy**:
       - `np.array()`: Para crear arreglos Numpy.
       - `np.mean()`: Para calcular la media de un arreglo.
       - `np.sum()`: Para sumar los elementos de un arreglo.

   - **Ejemplos de Código**: Intenta escribir pequeños fragmentos de código que utilicen estas funciones. Esto te ayudará a recordar la sintaxis y a entender cómo se aplican en diferentes contextos.

   - **Documentación**: Dedica tiempo a leer la documentación oficial de ambas librerías. La documentación contiene ejemplos prácticos y explicaciones detalladas que pueden ser muy útiles.

   Este repaso te permitirá abordar el ejercicio de forma más cómoda y efectiva, aumentando tu confianza en el uso de estas herramientas. ¡Buena suerte!

¡Todo listo! Ahora puedes comenzar a resolver los ejercicios uno por uno. Recuerda leer atentamente cada enunciado y aplicar lo aprendido.



## 🚛 Cómo entregar este proyecto

Una vez que completes los ejercicios, sigue estos pasos para enviarlos correctamente:  

1. **Guarda y confirma los cambios** en tu repositorio local:  

   ```sh
   git add .
   git commit -m "Completed exercises"
   ```
2. Sube los cambios a GitHub con:

    ```sh
    git push origin main
    ```
3. Dirígete a [4Geeks.com](https://4geeks.com) para enviar el enlace de tu repositorio.

