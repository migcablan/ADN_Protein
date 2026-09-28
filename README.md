# Práctica: Del ADN a la Proteína

## 1. Requisitos e Instalación

Abre una terminal y ejecuta el siguiente comando para instalar las librerías necesarias:

```bash
pip install biopython requests ipykernel
```

---

## 2. Abrir en Visual Studio Code

1. Abre **Visual Studio Code**.
2. Instala la extensión **Jupyter** (de Microsoft) desde la pestaña de extensiones (`Ctrl + Shift + X`).
3. Ve a `Archivo` -> `Abrir carpeta...` y selecciona la carpeta donde tengas el proyecto.
4. Abre el archivo `Del_ADN_a_la_Proteina.ipynb`.
5. En la esquina superior derecha del editor, haz clic en **Seleccionar Kernel** (*Select Kernel*) y elige tu entorno de Python.

---

## 3. Ejecución

* **Celda a celda:** Pulsa el botón de **Play** ($\blacktriangleright$) a la izquierda de cada celda o usa el atajo `Shift + Enter`.
* **Todo el cuaderno:** Haz clic en **Ejecutar todo** (*Run All*) en la barra superior.

---

## 4. Orden de los Ejercicios en el Notebook

1. **Ejercicio 1:** Replicación y comprobación de la hebra complementaria con Biopython.
2. **Ejercicio 2:** Lectura de archivo FASTA y obtención del transcrito de ARNm.
3. **Ejercicio 3:** Traducción a proteína y prueba de mutaciones puntuales.
4. **Ejercicio 4:** Simulación de dos isoformas por *splicing* alternativo.
5. **Ejercicio 5:** Análisis de extremos N/C y cálculo de propiedades con `ProtParam`.
6. **Ejercicio 6:** Ejecución del pipeline integral del dogma central desde un archivo FASTA.