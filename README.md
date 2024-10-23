
# DeepSortApp

Este proyecto utiliza el algoritmo **Deep SORT** para realizar seguimiento de objetos en videos, junto con herramientas modernas como **YOLO**. Está configurado para trabajar con las últimas versiones de las dependencias necesarias para el correcto funcionamiento.

## Video de referencia
Para ver una demostración completa de cómo funciona este proyecto, consulta el siguiente video:
- [Ver video en YouTube](https://www.youtube.com/watch?v=jIRRuGN0j5E)

## Requisitos
- **Versión de Python:** 3.7

### Instalación de dependencias
A continuación, se detallan las dependencias necesarias para ejecutar este proyecto y los comandos para su instalación:

- **Ultralytics (v8.3.15):**
  ```bash
  pip install ultralytics
  ```

- **Scikit-learn (v1.5.2):**
  ```bash
  pip install scikit-learn
  ```

- **TensorFlow (v2.17.0):**
  ```bash
  pip install tensorflow
  ```

- **Scikit-image (v0.24.0):**
  ```bash
  pip install scikit-image
  ```

- **Filterpy (v1.4.5):**
  ```bash
  pip install filterpy
  ```

- **NumPy (v1.26.4):**
  ```bash
  pip install numpy
  ```

- **OpenCV (v4.10.0.84):**
  ```bash
  pip install opencv-python
  ```

### Instalar Deep SORT
Clona el repositorio oficial de **Deep SORT** con el siguiente comando:

```bash
git clone https://github.com/nwojke/deep_sort.git
```

### Modelo para Deep SORT
Crea una carpeta llamada `model_data` en el directorio raíz del proyecto e incluye el siguiente modelo preentrenado en ella:
- [Descargar modelo MARS-small128.pb](https://github.com/Qidian213/deep_sort_yolov3/blob/master/model_data/mars-small128.pb)

## Uso del Proyecto
Este proyecto ha sido modificado para ser compatible con las versiones actuales de las dependencias mencionadas. Los archivos de Deep SORT, el tracker y el archivo principal (**main**) se han ajustado para trabajar sin inconvenientes con estas versiones.

### Video de prueba
Asegúrate de añadir el archivo `data.mp4` a la carpeta raíz del repositorio. Puedes descargar el video de prueba desde el siguiente enlace:
- [Descargar video data.mp4](https://drive.google.com/drive/folders/1kZ0QVwlwMERyTyi5c72GeqKgr8qAUx2o)



