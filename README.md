# 🌵 Chatbot Tiringa - IA com Personalidade
integrantes: Emmylio, Eric, Ytallo

Projeto final desenvolvido para a disciplina de Inteligência Artificial Aplicada. O objetivo foi criar um chatbot com uma *persona* forte (o personagem Tiringa), utilizando Engenharia de Prompt para simular dialetos regionais e comportamento "hostil/engraçado".

## 📝 Sobre o Projeto
O sistema utiliza a API do **Google Gemini (Modelo 1.5 Flash)** e a interface **Gradio**. 
O diferencial deste projeto é o **System Prompt** complexo que força a IA a ignorar suas diretrizes de "assistente prestativo" para assumir a identidade de um homem do campo, mentiroso e impaciente.

## 🚀 Como Executar

Este projeto foi desenvolvido no Google Colab. Para testar:

1. Baixe o arquivo `.ipynb` deste repositório ou abra diretamente no Colab.
2. Gere uma API Key gratuita no [Google AI Studio](https://aistudio.google.com/).
3. No código, localize a variável `onde esta o codigo da api` e cole sua chave:
   ```python
   MINHA_API_KEY = "COLE_SUA_CHAVE_AQUI"
