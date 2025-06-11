# CEIA - Redes neuronales informadas por física

Bienvenidos al repositorio de material didáctico y académico del curso "Redes neuronales informadas por física".

Estos contenidos también podrán encontrarlo en  podrán encontrarla en el [campus académico del curso](https://campusposgrado.fi.uba.ar/course/view.php?id=390), junto con la información relacionada a la planificación de la cursada y canales de comunicación.

## Organización de la información

Aquí encontraran todo el material didactico utilizado durante la cursada. Se habilita una nueva rama por cursada para dejar registro de actualizaciones. Registro de cursadas:

- [3er bimestre 2025](https://github.com/FIUBA-Posgrado-Inteligencia-Artificial/CEIA-PINN/tree/3b2025).

En el repositorio se alojan las presentaciones y prácticas de cada módulo del curso. 

También se encuentran los temas propuestos para realizar el trabajo integrador. El objetivo es trabajar en un caso que les permita introducirse en los temas vistos durante el curso, explorando las herramientas disponibles y detectando las dificultades que pueden presentarse en la temática de las Redes neuronales informadas por la física. Este trabajo les permitirá aplicar los conceptos aprendidos, identificar posibles desafíos y desarrollar habilidades prácticas que serán fundamentales para su comprensión y manejo de las PINN.

## Requerimientos y configuraciones

### Colab Cloud

Todas las prácticas pueden ejecutarse a través de [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb). Colab es la plataforma basada en la nube que permite escribir y ejecutar código desarrollado en Python en un entorno web. Proporciona acceso a recursos de computación, incluidos GPUs. No se requiere instalación, ya que todo se ejecuta en un navegador web. Se instalan bibliotecas adicionales según sea necesario.

### Librerías de Python

- **NumPy**: herramientoa para cálculo numérico y manipulación matricial.
- **SciPy**: funciones matemáticas avanzadas y herramientas de optimización.
- **Matplotlib**: visualización de datos y gráficos.

Juntas, estas librerías proporcionan un conjunto de herramientas completo completo para el análisis de datos, la computación científica y la visualización de datos para el Teaching Kit. Puede usarse Miniconda para instalar y gestionar estas bibliotecas.

Documentación:

- [NumPy](https://numpy.org/doc/)
- [SciPy](https://docs.scipy.org/doc/)
- [Matplotlib](https://matplotlib.org/stable/contents.html)

Pytorch y TensorFlow son los frameworks de deep learning empleados en el curso. Puede usarse Miniconda para instalar y gestionar estas librerías.

- **Pytorch**: conocido por sus grafos de computación dinámico, lo hace flexible para el desarrollo de modelos de aprendizaje profundo.
- **TensorFlow**: ampliamente utilizado para construir y entrenar redes neuronales profundas, ofrece APIs de alto nivel para un desarrollo rápido y control de bajo nivel.

Documentación:

- [PyTorch](https://pytorch.org/docs/stable/index.html)
- [TensorFlow](https://www.tensorflow.org/guide)

### Miniconda

En caso de trabajar en local, se recomienda emplear Miniconda. Se trata de un instalador mínimo gratuito para conda. Es una versión bootstrap pequeña de Anaconda que incluye solo conda, Python, los paquetes de los que ambos dependen y un pequeño número de otros paquetes útiles. Resulta versatil para crear entornos independientes de programación. Puede descargarse desde [aquí](https://docs.anaconda.com/miniconda/miniconda-other-installer-links/).

### Empleo de GPU

Si se cuenta con GPUs, se debe instalar el compilador que permita el cómputo en paralelo.

- **CUDA**: modelo de programación desarrollado por [NVIDIA](nvidia.com). Se pueden escribir programas en lenguajes como C, C++ y Fortran, y ejecutar cálculos en paralelo en la GPU.
- **ROCm**: se trata de una pila de software de código abierto diseñada para el desarrollo de soluciones de inteligencia artificial (IA) y computación de alto rendimiento (HPC) en las GPU de [AMD](amd.com).

> IMPORTANTE: en el curso se trabajará con configuraciones orientadas al empleo de CUDA.

Documentación para descarga:

- [CUDA](https://developer.nvidia.com/cuda-downloads) (en el caso de Windows, ver también la siguiente sección).
- [ROCm (Linux)](https://rocm.docs.amd.com/en/latest/); [ROCm (Windows)](https://rocm.docs.amd.com/projects/install-on-windows/en/latest/)

### Windows subsystems for Linux

Muchos de las herramientas necesarias para desarrollar modelos PINN, fueron concebidas en Linux, por lo que en ciertos casos resulta más oficiente trabajar en dicho SO. Puede ocurrir que se cuente con Windows como sistema operativo nativo y no sea posible migrar a Linux. En ese caso, se puede emplear [_Windows systems for linux_](https://learn.microsoft.com/es-es/windows/wsl/) (WSL). Se trata de una característica de Windows que permite ejecutar un entorno Linux en la máquina Windows, sin necesidad de una máquina virtual independiente ni de arranque dual. Además, es posible programar con [Visual Studio Code](https://code.visualstudio.com/) desde Windows, conextándose al entorno de WSL.

Como se trabajará con configuraciones orientadas al empleo de CUDA, seguir las instrucciones de instalación especificadas [aquí](https://learn.microsoft.com/en-us/windows/ai/directml/gpu-cuda-in-wsl).

## Clonado y acceso al contenido del repositorio

Puede clonarse el repositorio en una máquina local y acceder, por ejemplo, al módulo 2 (empleando clave SSH en distintos SO, ver generación [aquí](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) y su incorporación [aquí](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)):
´´´
    git clone git@github.com:FIUBA-Posgrado-Inteligencia-Artificial/CEIA-PINN.git
    cd ‘modulo 2 - repaso fisica matematica’
´´´
