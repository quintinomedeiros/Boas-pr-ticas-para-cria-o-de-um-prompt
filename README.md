# Aprendendo a criar um prompt para obter as melhores respostas das IAs


## Contexto e Objetivos:
Este caderno temático foi organizado para estudar boas práticas de prompt engineering aplicadas à interação com IAs generativas. O foco é entender como formular instruções mais claras, consistentes e úteis, reduzindo ambiguidades e melhorando a qualidade das respostas. A base do estudo considera que prompt engineering é um processo iterativo: escrever, testar, ajustar e avaliar resultados.


## Curadoria de Fontes:
1. [Atenção! Prompt não é comando: é estratégia. Aprenda a usar a IA Generativa como um expert.](https://web.dio.me/articles/atencao-prompt-nao-e-comando-e-estrategia-aprenda-a-usar-a-ia-como-um-expert-e2352a331540?back=/articles)
   Preste atenção para aprender sobre IA generativa

2. [Transforme caos em insights: automatize a análise de Big Data com Python e Pandas](https://web.dio.me/articles/transforme-caos-em-insights-automatize-a-analise-de-big-data-com-python-e-pandas-c082de8c9582?back=/articles)
   Por que Python virou a linguagem da análise de dados?

3. [Construa um agente de recomendação de trading inteligente com Python](https://web.dio.me/articles/construa-um-agente-de-recomendacao-de-trading-inteligente-com-python-78715698e8ac?back=/articles)
   Este artigo apresenta um guia prático para a criação de um sistema de recomendação de operações de trading em Python

4. [Pare de perder tempo com planilhas: domine o excel e revolucione sua análise de dados](https://web.dio.me/articles/pare-de-perder-tempo-com-planilhas-domine-o-excel-e-revolucione-sua-analise-de-dados-e752b64fe38a?back=/articles)
   Este artigo explora quatro aspectos fundamentais do uso do Excel 

5. [Análise de dados e Machine Learning Simplificados com Python](https://web.dio.me/articles/analise-de-dados-e-machine-learning-simplificados-com-python?back=/articles)
   Usando Bibliotecas Python na Análise de Dados

6. [Como utilizar engenharia de prompt para melhorar seus resultados](https://web.dio.me/articles/como-utilizar-engenharia-de-prompt-para-melhorar-seus-resultados-YKJDZ6?back=/articles)
   Como utilizar engenharia de prompt para melhorar seus resultados

7. [OpenAI — Prompting](https://developers.openai.com/api/docs/guides/prompting)  
   Guia oficial com fundamentos e estratégias de prompt.

8. [OpenAI — Prompt Engineering](https://developers.openai.com/api/docs/guides/prompt-engineering)  
   Explica como escrever instruções eficazes para modelos de IA.

9. [OpenAI — Prompt Guidance](https://developers.openai.com/api/docs/guides/prompt-guidance)  
   Traz padrões e orientações para melhorar prompts.

10. [Google AI for Developers — Prompt Design Strategies](https://ai.google.dev/gemini-api/docs/prompting-strategies)  
   Estratégias e boas práticas para prompts no Gemini.

11. [Google Cloud — Gemini 3 Prompting Guide](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/start/gemini-3-prompting-guide)  
   Guia prático com exemplos e ajustes de prompting.

12. [Google Cloud — Prompt Engineering Guide](https://cloud.google.com/discover/what-is-prompt-engineering)  
   Visão geral sobre engenharia de prompts e uso em LLMs.

13. [Anthropic — Prompt Engineering Overview](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview)  
   Introdução oficial às práticas de prompt para Claude.

14. [Anthropic — Prompting Best Practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices)  
   Boas práticas detalhadas para melhorar a qualidade das respostas.

15. [Anthropic — AI Learning Resources](https://www.anthropic.com/learn)  
   Central de guias e materiais sobre uso de IA e prompts.

16. [Anthropic — Prompt Engineering for Business Performance](https://www.anthropic.com/news/prompt-engineering-for-business-performance)  
    Artigo com aplicação prática de prompts em contextos reais.

17. [Microsoft Learn — Prompt Engineering Techniques](https://learn.microsoft.com/en-us/azure/foundry/openai/concepts/prompt-engineering)  
    Técnicas de prompting aplicadas ao Azure OpenAI.

18. [Microsoft Learn — System Message Design for Azure OpenAI](https://learn.microsoft.com/en-us/azure/foundry/openai/concepts/advanced-prompt-engineering)  
    Orientações sobre mensagens de sistema e consistência de resposta.

19. [Microsoft Learn — Prompts Overview](https://learn.microsoft.com/en-us/microsoft-copilot-studio/prompts-overview)  
    Visão geral sobre prompts no Copilot Studio.

20. [OpenAI Cookbook — GPT-5 Prompting Guide](https://developers.openai.com/cookbook/examples/gpt-5/gpt-5_prompting_guide)  
    Guia prático com exemplos de otimização de prompts.

21. [Google AI Gemini API — Prompt Gallery](https://ai.google.dev/gemini-api/prompts)  
    Galeria de exemplos úteis para inspirar e testar prompts.

22. [Engenharia De Prompt: 7 Passos Para O Prompt Perfeito | ChatGPT](https://www.youtube.com/watch?v=oFGXr2pgKLY)
    Entenda como criar um prompt phod@ no ChatGPT através da Engenharia de Prompt.
   
23. [44 VÍDEOS que vão mudar seu entendimento sobre prompts PARA SEMPRE](https://www.youtube.com/watch?v=GA2m-1m4zxk&list=PLbmt8d_ueDMV76q66QhK0EmyM93Zh7l5Y)
    Quer dominar o ChatGPT? Confira nosso primeiro vídeo da série e aprenda a criar prompts efetivos usando delimitadores de texto! 

24. [Como criar ótimos prompts nas últimas atualizações das IAs](https://www.youtube.com/watch?v=uPR2PutJ6c0)
    O especialista em inteligência artificial Pedro Burgos atualiza o que se sabe sobre gerar os melhores prompts para as ferramentas de IA com base em estudos científicos atuais.

25. [Como criar ÓTIMOS PROMPTS na prática com 5 TÉCNICAS](https://www.youtube.com/watch?v=xA7PdN_mLJ8)
    Neste vídeo, Bruno Pimenta explica o que é Engenharia de Prompt e apresenta 5 técnicas práticas para você criar comandos eficazes.

26. [COMO FAZER o CHATGPT DAR RESPOSTAS 100% CORRETAS - SACANI Ensina](https://www.youtube.com/watch?v=X51KsjOa41E)
    Como a Inteligência Artificial pode causar o fim da humanidade (com Sérgio Sacani)
    
## Engenharia de Prompts e "Cicatrizes":
1. A principal dor é ter que refinar o prompt para que possa se aproximar mais das necessidades que tinha, pois inicialmente, nem o criador do prompt tem muito claro o que precisa e com as respostas pode também aprimorar o que está pedindo e obtendo, quanto entendendo melhor o que precisa.
