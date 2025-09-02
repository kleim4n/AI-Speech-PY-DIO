# AI-Speech-PY-DIO
Um projeto simples de assistente virtual desenvolvido em Python, focado em Processamento de Linguagem Natural (PLN). A assistente é capaz de reconhecer comandos de voz em português, processá-los e executar tarefas pré-definidas, respondendo também com uma voz sintetizada.

## ✨ Funcionalidades

  - ✅ **Reconhecimento de Voz**: Ouve o ambiente através do microfone e converte a fala em texto.
  - ✅ **Síntese de Voz**: Responde aos comandos com uma voz em português.
  - ✅ **Ações Automatizadas**: Executa tarefas com base nos comandos de voz, como:
      - Pesquisar vídeos no YouTube.
      - Realizar uma pesquisa geral na web.
      - Encontrar a farmácia mais próxima no Google Maps.
      - Informar as horas atuais.
  - ✅ **Conversor de Texto para Áudio**: Um comando especial que permite ao usuário digitar um texto e salvá-lo como um arquivo `.mp3`.
  - ✅ **Comando de Encerramento**: Permite finalizar a execução da assistente por voz.

## 🛠️ Tecnologias Utilizadas

  - **Python 3**
  - **SpeechRecognition**: Para o reconhecimento de fala (Speech-to-Text).
  - **gTTS (Google Text-to-Speech)**: Para a síntese de voz (Text-to-Speech).
  - **Pygame**: Para a reprodução dos arquivos de áudio gerados.
  - **PyAudio**: Dependência para acesso ao microfone.
  - **webbrowser**: Biblioteca padrão do Python para abrir links no navegador.

## 🚀 Como Executar o Projeto

### Pré-requisitos

  - Python 3.8 ou superior.
  - `pip` (gerenciador de pacotes do Python).
  - Um microfone funcional e configurado no seu sistema.

### Instalação

1.  **Clone este repositório ou baixe os arquivos.**

    ```bash
    # Se estiver usando git
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2.  **Crie um ambiente virtual (recomendado):**

    ```bash
    # Para Windows
    python -m venv venv
    .\venv\Scripts\activate

    # Para macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Instale as dependências necessárias:**

    ```bash
    pip install SpeechRecognition gTTS pygame PyAudio
    ```

### Uso

1.  **Execute o script principal no seu terminal:**

    ```bash
    python assistente_virtual.py
    ```

2.  **Aguarde a mensagem de inicialização.** A assistente dirá "Olá\! Estou pronta para ajudar." e o terminal exibirá "Ouvindo...".

3.  **Diga um dos comandos disponíveis.**

## 🗣️ Comandos Disponíveis

  - `"Pesquisar por [termo da sua pesquisa]"`: Abre uma busca no Google.
  - `"YouTube [termo do vídeo]"`: Abre uma busca no YouTube.
  - `"Encontrar farmácia"`: Abre o Google Maps com a localização das farmácias, ou outro estabelecimento, próximas.
  - `"Que horas são?"`: Informa a hora atual.
  - `"Texto para voz"`: Inicia a funcionalidade para converter um texto digitado em um arquivo de áudio.
  - `"Sair"` ou `"Desligar"`: Encerra a assistente.

-----