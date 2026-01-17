#  Virtual Voice Assistant (Python)

Este projeto implementa um **Assistente Virtual por Voz** desenvolvido em Python, utilizando técnicas de **Processamento de Linguagem Natural (PLN)**, reconhecimento de fala e síntese de voz.

O sistema foi projetado para ser executado no **Google Colab**, mas também pode ser adaptado para execução local.

---

##  Objetivo do Projeto

Criar um assistente virtual capaz de:

* Ouvir comandos por voz
* Converter fala em texto
* Processar comandos em linguagem natural
* Executar ações automáticas
* Responder ao usuário por voz (Text-to-Speech)

---

##  Tecnologias Utilizadas

O projeto utiliza as seguintes bibliotecas:

* `speech_recognition` – Reconhecimento de fala
* `pyttsx3` – Conversão de texto em áudio (Text-to-Speech)
* `pyaudio` – Captura de áudio do microfone
* `webbrowser` – Abertura automática de sites
* `wikipedia` – Busca de informações
* `datetime` – Manipulação de data e hora

---

##  Como Executar no Google Colab

### Passo 1 — Clonar o repositório

```
!git clone https://github.com/WendyValdes/Virtual-assistant.git

```

### Passo 2 — Entrar na pasta do projeto

```
%cd Virtual-assistant

```

### Passo 3 — Instalar dependências

```
!pip install SpeechRecognition pyttsx3 wikipedia pyaudio

```

>  Nota: Em alguns ambientes o `pyaudio` pode exigir configuração adicional.

### Passo 4 — Executar o assistente

Abra o notebook e execute a célula principal contendo o código do assistente.

---

##  Exemplos de Comandos

Você pode dizer coisas como:

* “Abrir YouTube”
* “Pesquisar na Wikipedia sobre Python”
* “Que horas são?”
* “Abrir Google”

---

##  Estrutura do Projeto

```
Virtual-assistant/
│
├── assistant.ipynb   # Código principal no Colab
├── README.md         # Documentação do projeto
└── requirements.txt  # (opcional) Dependências

```

---

##  Contribuições

Contribuições são bem-vindas!

Você pode contribuir através de:

* Correção de bugs
* Melhorias na documentação
* Novas funcionalidades
* Testes automatizados

Para contribuir:

1. Faça um fork do repositório
2. Crie uma branch (`feature/nova-funcionalidade`)
3. Faça suas alterações
4. Abra um Pull Request


  
