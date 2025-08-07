- Crea un entorno virtual de Python e instala Gradio utilizando los siguientes comandos en la terminal:
```
pip3 install virtualenv 
virtualenv my_env # create a virtual environment my_env
source my_env/bin/activate # activate my_env
```
- Luego, instala las bibliotecas requeridas en el entorno:
```
# installing required libraries in my_env
pip install langchain==0.1.0 openai==0.28 gradio==4.21.0 chromadb tiktoken
```