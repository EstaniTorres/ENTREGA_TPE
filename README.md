### Clonar el repositorio
en git bash realizar lo siguiente:

git clone https://github.com/EstaniTorres/ENTREGA_TPE.git

cd ENTREGA_TPE //entra a la carpeta del repositorio

code . //abre la carpeta en el editor de codigo

## Configuración del Entorno
Sigue estos pasos para preparar el entorno de trabajo:

1. **Iniciar una nueva terminal.**

2. **Crear un entorno virtual (venv)** para utilizar Jupyter Notebook:  
   python -m venv <nombre_del_entorno>
   
3. **Activar el ambiente vitual**:
   
  En Windows:
    <nombre_del_entorno>\Scripts\activate
   
  En macOS / UNIX:
    source <nombre_del_entorno>/bin/activate
    
5. **selecionar una kernel para podes usar la yupiter notebook**
6. **elegir la kernerl con el mismo nombre que el ambiente virtual**
7. **Instalar dependencias necesarias**:
   
   pip install -r requirements.txt
