# Ollama - Introdução

Link para o site oficial: [https://ollama.com/](https://ollama.com/)

O **Ollama** é um projeto open source que permite rodar modelos de IA direto no seu computador. Com ele você gerencia e executa modelos facilmente. Além disso, o Ollama expõe uma **REST API**. Isso significa que você pode integrar os modelos às suas aplicações, como por exemplo utilizando o langchain.

## Benefícios

- Privacidade: Como está local, dados não passam por nada além do seu próprio computador;
- Customização: É possível realizar fine tuning;
- Facilidade: Subir modelo com Rest API.

## Casos de Usos

- Desenvolver aplicações que integram IA;
- Segurança;
- Pesquisa.

## Problema

A principal limitação vai ser o **hardware**

- Espaço em disco para baixar o modelo;
- VRAM (ou RAM) o suficiente para carregar o modelo na memória;
- GPU (ou CPU) com potência para responder em tempo razoável.

**VRAM**: Video RAM, memória dedicada exclusivamente à GPU, caso não possua GPU compatível (NVIDIA/AMD), a VRAM será uma fatia da RAM.