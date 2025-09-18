# 🗣️ Assistente Virtual com Voz (Python + Vosk + gTTS + PyGame)

Este projeto implementa um **assistente virtual por voz**, capaz de ouvir comandos, responder com fala, contar piadas, tocar músicas, buscar informações na Wikipedia, abrir sites e muito mais.  

O assistente funciona **offline para reconhecimento de voz** usando [Vosk](https://alphacephei.com/vosk/) e pode gerar áudio com **Google Text-to-Speech (gTTS)** ou **Pyttsx3** (voz local offline).  

---

## 🚀 Funcionalidades

- 🎤 **Reconhecimento de voz offline** com [Vosk]  
- 🗣️ **Síntese de fala** com **gTTS** (Google TTS online) ou **pyttsx3** (voz local)  
- 🎶 **Controle de música** com PyGame (tocar/parar músicas)  
- 📚 **Busca na Wikipedia** e leitura de resumos  
- 😂 Contar piadas com [pyjokes](https://pypi.org/project/pyjokes/)  
- 🌐 Abrir sites comuns via comando de voz (Google, Wikipedia, LinkedIn, YouTube)  
- ⏰ Informar a hora atual  
- 🖥️ Interface simples com widgets no Jupyter Notebook para testar TTS  

---

## 📦 Requisitos

Certifique-se de ter o **Python 3.8+** instalado e rode:

```bash
pip install gtts pyttsx3 pygame sounddevice vosk wikipedia pyjokes ipywidgets

/vosk-model-small-en-us-0.15/
    ├── am
    ├── conf
    ├── ...
---
```
## 🎮 Exemplos de Comandos de Voz

- **"open google"** → abre o Google  
- **"open wiki"** → abre a Wikipedia  
- **"linked in"** → abre o perfil do LinkedIn  
- **"youtube"** → pesquisa no YouTube  
- **"search"** → busca na Wikipedia e lê resumo  
- **"joke"** → conta uma piada  
- **"what time"** → diz a hora atual  
- **"exit"** / **"quit"** / **"bye"** → encerra o assistente  
