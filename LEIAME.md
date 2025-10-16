# 🧠 Estudo de Caso 1  


Neste estudo de caso, criamos **assistente de programação em Python** usando **IA**, com suporte de ferramentas modernas como **Groq** (para processamento rápido de linguagem natural) e **Streamlit** (para criar a interface web interativa da aplicação).

---

##  Etapa 1 — Criar e Ativar o Ambiente Virtual

Abra o **terminal** ou **prompt de comando**, navegue até a pasta onde estão os arquivos do projeto e execute:

```bash
conda create --name dsaec1 python=3.13
````
Ative o ambiente recém-criado:
````bash
conda activate dsaec1
# ou
source activate dsaec1
```

Instale o pip (caso ainda não esteja instalado) e todas as dependências do projeto listadas no arquivo requirements.txt:
````bash
conda install pip
pip install -r requirements.txt
````
Para iniciar o assistente, rode o seguinte comando:

````bash
streamlit run dsa_assistente.py
````
