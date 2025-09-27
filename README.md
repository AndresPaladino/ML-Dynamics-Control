## Machine Learning, Dynamical Systems, and Control
Ejercicios y ejemplos que vaya haciendo en mi lectura del libro Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control de J. Nathan Kutz and Steven L. Brunton

**Aviso:** Estas notas no son una guia, sino una recopilacion de las cosas que voy haciendo a medida que voy leyendo el libro, va a haber errores y voy a sacar conclusiones erroneas en muchas ocaciones. Supongo que a medida que vaya avanzando en el libro también voy a ir perfeccionando las tecnicas que uso :).
![readmeGif](CH01/generated_visualizations/readmeGif.gif)

### Requisitos
- Miniconda o Anaconda instalado.
### Instalación
```bash
git clone https://github.com/AndresPaladino/ML-Dynamics-Control.git
cd ML-Dynamics-Control
conda env create -f environment.yml
conda activate ddse

# Alternativamente se puede nombrar el entorno de otra manera usando
conda env create -f environment.yml -n [mi_entorno]
conda activate [mi_entorno]
 ```
### Uso
```bash
jupyter-notebook
```

### Exportar environment
```bash
conda env export --from-history > environment.yml
```
### Actualizar environment
```bash
conda env update --file environment.yml --prune
```


