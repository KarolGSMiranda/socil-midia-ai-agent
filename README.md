# socil-midia-ai-agent
Agente de IA para planejamento de redes sociais, usando LLM Gemini, RAG com FAISS e workflow LangGraph para gerar, ajustar e validar cronogramas de posts automaticamente.

Este projeto implementa um agente de IA capaz de criar cronogramas de postagens para redes sociais de forma automatizada. Ele combina:
- LLM Gemini 2.5 para geração de texto criativa.
- RAG (Retrieval-Augmented Generation) com FAISS para consultas a documentos PDF com normas e diretrizes de redes sociais.
- LangGraph para modelar o workflow de decisões (gerar cronograma, ajustar plano, pedir informações, sugerir ideias, validar plano).
- Pydantic para garantir saída estruturada em JSON dos cronogramas.


Funcionalidades:
- Geração automática de cronogramas semanais, quinzenais ou mensais.
- Sugestão de conteúdos, formatos e plataformas adequadas.
- Validação e ajuste de planos existentes.
- RAG para embasamento em documentos da empresa.

Ideal para equipes de marketing, social media ou desenvolvedores que querem automatizar a criação de conteúdos em redes sociais usando IA.
