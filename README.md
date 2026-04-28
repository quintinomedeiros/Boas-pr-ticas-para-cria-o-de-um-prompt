# Aprendendo a criar um prompt para obter as melhores respostas das IAs


## Contexto e Objetivos:
Este caderno temático foi organizado para estudar boas práticas de prompt engineering aplicadas à interação com IAs generativas. O foco é entender como formular instruções mais claras, consistentes e úteis, reduzindo ambiguidades e melhorando a qualidade das respostas. A base do estudo considera que prompt engineering é um processo iterativo: escrever, testar, ajustar e avaliar resultados.


## Curadoria de Fontes:
1. [OpenAI — Prompting](https://developers.openai.com/api/docs/guides/prompting)  
   Guia oficial com fundamentos e estratégias de prompt.

2. [OpenAI — Prompt Engineering](https://developers.openai.com/api/docs/guides/prompt-engineering)  
   Explica como escrever instruções eficazes para modelos de IA.

3. [OpenAI — Prompt Guidance](https://developers.openai.com/api/docs/guides/prompt-guidance)  
   Traz padrões e orientações para melhorar prompts.

4. [Google AI for Developers — Prompt Design Strategies](https://ai.google.dev/gemini-api/docs/prompting-strategies)  
   Estratégias e boas práticas para prompts no Gemini.

5. [Google Cloud — Gemini 3 Prompting Guide](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/start/gemini-3-prompting-guide)  
   Guia prático com exemplos e ajustes de prompting.

6. [Google Cloud — Prompt Engineering Guide](https://cloud.google.com/discover/what-is-prompt-engineering)  
   Visão geral sobre engenharia de prompts e uso em LLMs.

7. [Anthropic — Prompt Engineering Overview](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview)  
   Introdução oficial às práticas de prompt para Claude.

8. [Anthropic — Prompting Best Practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices)  
   Boas práticas detalhadas para melhorar a qualidade das respostas.

9. [Anthropic — AI Learning Resources](https://www.anthropic.com/learn)  
   Central de guias e materiais sobre uso de IA e prompts.

10. [Anthropic — Prompt Engineering for Business Performance](https://www.anthropic.com/news/prompt-engineering-for-business-performance)  
    Artigo com aplicação prática de prompts em contextos reais.

11. [Microsoft Learn — Prompt Engineering Techniques](https://learn.microsoft.com/en-us/azure/foundry/openai/concepts/prompt-engineering)  
    Técnicas de prompting aplicadas ao Azure OpenAI.

12. [Microsoft Learn — System Message Design for Azure OpenAI](https://learn.microsoft.com/en-us/azure/foundry/openai/concepts/advanced-prompt-engineering)  
    Orientações sobre mensagens de sistema e consistência de resposta.

13. [Microsoft Learn — Prompts Overview](https://learn.microsoft.com/en-us/microsoft-copilot-studio/prompts-overview)  
    Visão geral sobre prompts no Copilot Studio.

14. [OpenAI Cookbook — GPT-5 Prompting Guide](https://developers.openai.com/cookbook/examples/gpt-5/gpt-5_prompting_guide)  
    Guia prático com exemplos de otimização de prompts.

15. [Google AI Gemini API — Prompt Gallery](https://ai.google.dev/gemini-api/prompts)  
    Galeria de exemplos úteis para inspirar e testar prompts.

16. [Engenharia De Prompt: 7 Passos Para O Prompt Perfeito | ChatGPT/(https://www.youtube.com/watch?v=oFGXr2pgKLY)
    Entenda como criar um prompt phod@ no ChatGPT através da Engenharia de Prompt.
   
17. [44 VÍDEOS que vão mudar seu entendimento sobre prompts PARA SEMPRE](https://www.youtube.com/watch?v=GA2m-1m4zxk&list=PLbmt8d_ueDMV76q66QhK0EmyM93Zh7l5Y)
    Quer dominar o ChatGPT? Confira nosso primeiro vídeo da série e aprenda a criar prompts efetivos usando delimitadores de texto! 

18. [Como criar ótimos prompts nas últimas atualizações das IAs](https://www.youtube.com/watch?v=uPR2PutJ6c0)
    O especialista em inteligência artificial Pedro Burgos atualiza o que se sabe sobre gerar os melhores prompts para as ferramentas de IA com base em estudos científicos atuais.

19. [Como criar ÓTIMOS PROMPTS na prática com 5 TÉCNICAS](https://www.youtube.com/watch?v=xA7PdN_mLJ8)
    Neste vídeo, Bruno Pimenta explica o que é Engenharia de Prompt e apresenta 5 técnicas práticas para você criar comandos eficazes.

20. [COMO FAZER o CHATGPT DAR RESPOSTAS 100% CORRETAS - SACANI Ensina](https://www.youtube.com/watch?v=X51KsjOa41E)
    Como a Inteligência Artificial pode causar o fim da humanidade (com Sérgio Sacani)
    
## Engenharia de Prompts e "Cicatrizes":
1. A principal dor é ter que refinar o prompt para que possa se aproximar mais das necessidades que tinha, pois inicialmente, nem o criador do prompt tem muito claro o que precisa e com as respostas pode também aprimorar o que está pedindo e obtendo, quanto entendendo melhor o que precisa.
