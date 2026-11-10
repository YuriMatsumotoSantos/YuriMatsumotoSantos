# Yuri Matsumoto

Estudante de Engenharia de Computação na UTFPR, em Pato Branco (PR). Trabalho com modelos de linguagem: ajuste fino, avaliação e o software em volta deles.

## No que estou trabalhando

**Iniciação Científica: correção automática de redações do ENEM com LLMs.** Ajuste fino com LoRA, avaliação em temas que o modelo nunca viu no treino e geração de feedback formativo para o aluno. Código, dados e o log datado de todos os experimentos estão em [IC-Redacoes-UTFPR/CorrecaoRedacao](https://github.com/IC-Redacoes-UTFPR/CorrecaoRedacao).

- QWK 0,78 na divisão oficial do corpus essay-br, em que o melhor resultado publicado é 0,79.
- Em temas inéditos o mesmo modelo cai para 0,66. Não encontrei esse teste publicado para o essay-br.
- O modelo ajustado usava só 2 das 6 notas possíveis por competência. Trocar a nota mais provável pela média ponderada pelas probabilidades levou o QWK de 0,44 para 0,52.
- Quatro adaptadores LoRA (Qwen 2.5, Llama 3.1, Mistral e Gemma 2) publicados em [huggingface.co/YurinhoMatsumoto](https://huggingface.co/YurinhoMatsumoto).

**TCC: RAG para busca de jurisprudência do STJ.** Protótipo que compara três estratégias de recuperação sobre decisões de crimes contra a ordem tributária: esparsa (BM25), densa (embeddings) e híbrida (fusão RRF). Em andamento.

## Outros projetos

- [enem-essay-classifier](https://github.com/YuriMatsumotoSantos/enem-essay-classifier): mais de 15 algoritmos de classificação sobre 4.570 redações, de TF-IDF a embeddings do BERTimbau.
- [ProjetoIntegrador-DevOps](https://github.com/YuriMatsumotoSantos/ProjetoIntegrador-DevOps): aplicação Flask com métricas no Prometheus, Docker e CI.
- [sistemas-embarcados-freertos](https://github.com/YuriMatsumotoSantos/sistemas-embarcados-freertos) e [conversor-buck-controle-digital](https://github.com/YuriMatsumotoSantos/conversor-buck-controle-digital): tempo real e controle digital em STM32.
- Plataforma de estudos para o ENEM, em Next.js e TypeScript, com um pipeline que extrai e classifica questões de prova usando LLM. Em desenvolvimento.

## Ferramentas

Python, Hugging Face Transformers, PEFT, TRL, vLLM, scikit-learn, TypeScript, Next.js, PostgreSQL, Docker, C para microcontroladores.

## Contato

[LinkedIn](https://www.linkedin.com/in/yuri-matsumoto-693138245/)
