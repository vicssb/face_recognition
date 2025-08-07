<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">
<p>
<div align="right"> 
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brasil" width="30"/> </a>
</div>
  <H1><b> Victor Sérgio Silva Barros </b> </H1>
</p> 

<div align="top" style="display: flex; justify-content: space-between;">
  <img src="./img/artificial-intelligence.png" alt="Logo Inteligência Artificial" width="80"/>
  <img src="./img/pineconeLog.png" alt="Logo pinecone" width="80"/>
  <img src="./img/logoN8N.png" alt="Logo N8N" width="80"/>
</div>

Gerar respostas precisas e contextualizadas para perguntas técnicas.
Automatizar tarefas repetitivas de busca e análise de informações.

## Introdução

Este projeto tem como objetivo Integrar inteligência artificial e automação para o acesso a informações complexas e transformá-las em conhecimento útil. Neste projeto utilizei a técnica RAG (Retrieval Augmented Generation), ou Geração de recuperação aumentada. Foi criado um Agente no N8N que é um verdadeiro especialista técnico personalizado em qualquer área! 


## Estrutura do Projeto

1. **Criação da Base de Conhecimento**:
  - Consultar e extrair dados de fontes diversas de forma eficiente.
   - A cada minuto o agente verifica se um novo arquivo foi incluído em uma determinada pasta do Google Drive.
   - Embeddings do Google Gemini são representações numéricas de dados de texto, imagem ou vídeo, que capturam o significado e as relações semânticas entre eles. Esses vetores numéricos permitem que modelos de aprendizado de máquina, especialmente de IA generativa, processem e produzam linguagem de forma mais eficaz, identificando padrões complexos e relações semânticas específicas de um determinado conteúdo. 
   - Pinecone é um banco de dados vetorial gerenciado na nuvem, projetado para otimizar a pesquisa de similaridade de dados em aplicações de inteligência artificial. Ele permite que desenvolvedores integrem facilmente pesquisa vetorial em seus aplicativos, como pesquisa semântica, sistemas de recomendação e análise de dados orientada por IA. 
  ![Fluxo N8N](./img/RAG-Vicssb.png)
  [Baixar Fluxo N8N](rag_vicssb.json)

2. **Agente de IA de RAG**:
  - O agente RAG faz o seguinte: Recuperação: a solicitação do usuário é usada para consultar uma base de dados de conhecimento externa, como um repositório de vetores, pesquisa de palavra-chave ou banco de dados SQL. A meta é obter os dados de suporte necessários para a resposta do LLM
   - Ajuste dos hiperparâmetros.
   ![Fluxo N8N](./img/Vic_Agent.png)
  [Baixar Fluxo N8N](Vic_Agent.json)
  

## Requisitos

- Python 3.7 ou superior.
- Framework TensorFlow ou PyTorch para desenvolvimento e treinamento de modelos de IA.
- Ferramenta de anotação de imagens (exemplo: LabelImg) para preparar os dados de entrada.
- Conta no Google Drive para armazenamento e atualização automática dos arquivos de conhecimento.
- Pinecone para gerenciamento e busca de vetores de embeddings.
- Gemini API para geração de embeddings de texto, imagem ou vídeo.
- N8N para automação dos fluxos e integração dos agentes

## Uso no Chat do N8N
![Chat N8N](./img/chat1.png)

## Uso no Chat na WEB
![Chat na WEB](./img/chat2.png)

## Referência

Para mais detalhes, consulte: https://docs.n8n.io/


## Licença

Este projeto está licenciado sob a Licença MIT.

## Controle de versão
 
1.0.0
 
 
## Autor
 
**Victor Sérgio Silva Barros**: 


<p align="left">
  <a href="mailto:vicssb@gmail.com" alt="Gmail" target = "_blank">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=mailto:vicssb@gmail.com" /></a>

  <a href="https://www.linkedin.com/in/victor-sergio-silva-barros/" alt="Linkedin" target = "_blank">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/victor-sergio-silva-barros/" /></a>

  <a href="https://wa.me/+5512981328278" alt="WhatsApp" target = "_blank">
  <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=https://wa.me/+5512987085327"/></a>

  </p>  

<p>Por favor, siga o github e junte-se a nós!
Obrigado pela visita e boa codificação!</p>


