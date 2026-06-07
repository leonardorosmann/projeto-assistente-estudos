# Assistente Inteligente para Estudos

## Descrição

Sistema desenvolvido utilizando n8n e Inteligência Artificial para auxiliar estudantes na análise de conteúdos acadêmicos.

A solução recebe textos enviados por meio de um Webhook, processa as informações utilizando um modelo de Inteligência Artificial e gera automaticamente:

* Resumo do conteúdo;
* Principais tópicos abordados;
* Perguntas para revisão.

## Problema

Estudantes frequentemente recebem uma grande quantidade de materiais de estudo e nem sempre possuem tempo suficiente para realizar uma leitura completa.

Isso dificulta a identificação dos principais conceitos e reduz a eficiência do processo de aprendizagem.

## Solução

O workflow automatiza a análise do conteúdo utilizando Inteligência Artificial Generativa.

O usuário envia um texto para o sistema e recebe automaticamente:

* Resumo do conteúdo;
* Cinco tópicos principais;
* Cinco perguntas para revisão.

## Tecnologias Utilizadas

* n8n
* Ollama
* Llama 3
* Webhook
* Inteligência Artificial Generativa

## Fluxo da Automação

Webhook → Edit Fields → Basic LLM Chain → Respond to Webhook

## Funcionamento

1. O usuário envia um texto através do Webhook.
2. O conteúdo é tratado pelo nó Edit Fields.
3. O modelo Llama 3 realiza a análise.
4. O sistema gera resumo, tópicos e perguntas.
5. O resultado é retornado ao usuário.

## Autor

Leonardo Rosmann
