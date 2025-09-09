# Projeto Agente de IA no Google Colab

Este projeto demonstra a criação de um agente de IA interativo utilizando a API Gemini no Google Colab.

## Descrição

Este notebook do Google Colab configura e utiliza a API Gemini para criar um agente de conversação simples. Ele permite que o usuário interaja com o modelo Gemini através de um loop de chat interativo.

## Funcionalidades

- Instalação das bibliotecas necessárias (`google-generativeai`).
- Configuração da API Gemini utilizando uma chave de API armazenada de forma segura nos segredos do Colab.
- Listagem dos modelos Gemini disponíveis para geração de conteúdo.
- Inicialização de um modelo Gemini específico (`gemini-2.0-flash-exp` neste exemplo).
- Criação de um chat interativo com histórico.
- Loop de entrada do usuário para enviar prompts ao agente de IA e exibir as respostas.

## Pré-requisitos

- Uma conta Google.
- Acesso ao Google Colab.
- Uma chave de API para a API Gemini. Você pode obter uma em [Google AI Studio](https://aistudio.google.com/).
- A chave de API deve ser adicionada aos segredos do Colab com o nome `GOOGLE_GEMINI_API_KEY`.

## Como usar

1. Abra este notebook no Google Colab.
2. Certifique-se de ter adicionado sua chave de API Gemini aos segredos do Colab com o nome `GOOGLE_GEMINI_API_KEY`.
3. Execute todas as células do notebook em sequência.
4. A célula que inicia o chat interativo (`3DAmJ_iJZSC2`) solicitará um prompt. Digite sua pergunta ou instrução e pressione Enter.
5. O agente de IA responderá. Você pode continuar digitando prompts até digitar 'fim' para sair do chat.

## Estrutura do Notebook

- **Instalação:** Instala a biblioteca `google-generativeai`.
- **Importação:** Importa as bibliotecas necessárias.
- **Configuração da API:** Configura a API Gemini com a chave de API.
- **Listar Modelos:** Exibe os modelos Gemini disponíveis.
- **Inicializar Modelo:** Inicializa o modelo Gemini a ser utilizado.
- **Chat Interativo:** Implementa o loop de chat com o agente de IA.

## Contribuindo

Contribuições são bem-vindas! Se você tiver sugestões de melhoria ou encontrar problemas, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

[Seu tipo de licença, por exemplo, MIT License]

## Autor

[Seu Nome ou Pseudônimo]
