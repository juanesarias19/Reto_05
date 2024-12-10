# Reto_05

---
**Nota:** Los ejercicios del 1-5 se encuentran en el notebook anexo a este repositorio

---

 #### 6. Consultar qué es y cómo funciona pip en python.

### ¿Qué es pip?

pip es un sistema de gestión para instalar paquetes de software escritos en Python

Muchos paquetes pueden ser encontrados en el Python Package Index (PyPI). Python 2.7.9 y posteriores (en la serie Python2), Python 3.4 y posteriores incluyen pip (pip3 para Python3) por defecto.

pip es un acrónimo recursivo que se puede interpretar como Pip Instalador de Paquetes o Pip Instalador de Python

---

### ¿Cómo funciona? 

* Para la intalacion de paquetes se utiliza el comnado:

<code class="language-text">pip install &lt;module_name&gt;</code>

* De la misma manera se puede desintalar algun paquete

<code class="language-text">pip uninstall &lt;module_name&gt;</code>

* Instalar una versión específica

<code class="language-text">pip install nombre_paquete==versión</code>

\* **Ejemplo:**
<code class="language-text">pip install numpy==1.21.0</code>
Esto asegura que se instale una versión específica del paquete.

* Estos paquetes tambien se pueden actualizar usando en comando:

<code class="language-text">pip install --upgrade nombre_paquete</code>

* El siguiente comando muestra una lista de todos los paquetes instalados en el entorno actual.

<code class="language-text">pip list</code>

* Usando el siguiente comando podemos mostrar información sobre un paquete, este comando muestra detalles como la versión instalada, dependencias y ubicación del paquete.

<code class="language-text">pip show nombre_paquete</code>


#### 7. Hacer un listado de módulos populares para python que se puedan instalar com pip y consultar cómo instalarlos.


A continuación se presenta una lista con los módulos mas populares de python

|   | Library         | Usage                                                          | Installation Command          |
|---|-----------------|----------------------------------------------------------------|--------------------------------|
| 1| **NumPy**       | Numerical computation and handling multidimensional arrays.    | ```pip install numpy```       |
| 2 | **Pandas**      | Data manipulation and analysis of tabular data.               | ```pip install pandas```      |
|3| **Matplotlib**  | Creating 2D plots and data visualizations.                    | ```pip install matplotlib```  |
|4| **Seaborn**     | Statistical data visualization with attractive charts.        | ```pip install seaborn```     |
|5| **Scikit-learn**| Machine Learning.                                             | ```pip install scikit-learn```|
|6| **TensorFlow**  | Building deep learning models.                                | ```pip install tensorflow```  |
|7| **Flask**       | Lightweight web application development.                      | ```pip install flask```       |
|8| **Django**      | Robust and scalable web application development.              | ```pip install django```      |
|9| **Requests**    | Efficient HTTP requests.                                      | ```pip install requests```    |
|10| **PyTorch**     | Building deep learning models.                                | ```pip install torch torchvision``` |
|11| **OpenCV**      | Image and video processing.                                   | ```pip install opencv-python```|
|12| **FastAPI**     | Fast and modern API development.                              | ```pip install fastapi uvicorn```|
|13| **Jupyter Notebook** | Create and share interactive documents with code, text, and visualizations. | ```pip install notebook```|
|14| **SciPy**       | Advanced functions for linear algebra, optimization, integration, and statistics. | ```pip install scipy```|
|16| **Plotly**      | Interactive and advanced data visualization.                  | ```pip install plotly```      |
