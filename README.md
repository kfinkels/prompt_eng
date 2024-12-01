# prompt_engineering

Prompt Engineering workshop for Developers

## Getting started

### Install and run ollama with llama3 model

Follow instruction in: https://github.com/ollama/ollama

Run ollama with llama3:

`ollama run llama3`

Validate the prompt:

```
>>> how much is 1+1
The answer to 1+1 is... (drumroll please)... 2!
```


### Create Python environment and install jupyter

* Create virtual env:

   `virtualenv -p python3 venv`

* Activate the virtual env:

   `source venv\bin\activate`

* Install jupyter-lab and ollama python library:

   `pip install jupyterlab`

* Run jupyter:

   `jupyter lab`
