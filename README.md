# Yuri Matsumoto

[English version below](#english)

Estudante de Engenharia de Computação na UTFPR, em Pato Branco (PR). Trabalho com modelos de linguagem: ajuste fino, avaliação e o software em volta deles.

## No que estou trabalhando

**Iniciação Científica: correção automática de redações do ENEM com LLMs.** Ajuste fino com LoRA, avaliação em temas que o modelo nunca viu no treino e geração de feedback formativo para o aluno. Código, dados e o log datado de todos os experimentos estão em [IC-Redacoes-UTFPR/CorrecaoRedacao](https://github.com/IC-Redacoes-UTFPR/CorrecaoRedacao).

- QWK 0,78 na divisão oficial do corpus essay-br, em que o melhor resultado publicado é 0,79.
- Em temas inéditos o mesmo modelo cai para 0,66. Combinado com o BERTimbau por competência, sobe para 0,72. Não encontrei esse teste publicado para o essay-br.
- O modelo ajustado usava só 2 das 6 notas possíveis por competência. Trocar a nota mais provável pela média ponderada pelas probabilidades levou o QWK de 0,44 para 0,52.
- Quatro adaptadores LoRA (Qwen 2.5, Llama 3.1, Mistral e Gemma 2) publicados em [huggingface.co/YurinhoMatsumoto](https://huggingface.co/YurinhoMatsumoto).

**TCC: RAG para busca de jurisprudência do STJ.** Protótipo que compara três estratégias de recuperação sobre decisões de crimes contra a ordem tributária: esparsa (BM25), densa (embeddings) e híbrida (fusão RRF). Em andamento.

## Outros projetos

- [enem-essay-classifier](https://github.com/YuriMatsumotoSantos/enem-essay-classifier): mais de 15 algoritmos de classificação sobre 4.570 redações, de TF-IDF a embeddings do BERTimbau.
- [ProjetoIntegrador-DevOps](https://github.com/YuriMatsumotoSantos/ProjetoIntegrador-DevOps): aplicação Flask com métricas no Prometheus, Docker e CI.
- [sistemas-embarcados-freertos](https://github.com/YuriMatsumotoSantos/sistemas-embarcados-freertos) e [conversor-buck-controle-digital](https://github.com/YuriMatsumotoSantos/conversor-buck-controle-digital): tempo real e controle digital em STM32.
- [plataforma-enem](https://github.com/YuriMatsumotoSantos/plataforma-enem): plataforma de estudos para o ENEM, em Next.js e TypeScript, com um pipeline que extrai e classifica questões de prova usando LLM. Em desenvolvimento.

## Ferramentas

Python, Hugging Face Transformers, PEFT, TRL, vLLM, scikit-learn, TypeScript, Next.js, PostgreSQL, Docker, C para microcontroladores.

## Contato

[LinkedIn](https://www.linkedin.com/in/yuri-matsumoto-693138245/)

---

## English

Computer Engineering student at UTFPR, in Pato Branco, Brazil. I work with language models: fine-tuning, evaluation and the software around them.

### What I am working on

**Undergraduate research: automated scoring of ENEM essays with LLMs.** Fine-tuning with LoRA, evaluation on essay prompts the model never saw in training, and formative feedback for the student. Code, data and the dated log of every experiment are in [IC-Redacoes-UTFPR/CorrecaoRedacao](https://github.com/IC-Redacoes-UTFPR/CorrecaoRedacao).

- QWK 0.78 on the official split of the essay-br corpus, where the best published result is 0.79.
- On unseen prompts the same model drops to 0.66. Combined with BERTimbau per competency, it reaches 0.72. I did not find this test published for essay-br.
- The fine-tuned model used only 2 of the 6 possible scores per competency. Replacing the most likely score with the probability-weighted mean raised QWK from 0.44 to 0.52.
- Four LoRA adapters (Qwen 2.5, Llama 3.1, Mistral and Gemma 2) published at [huggingface.co/YurinhoMatsumoto](https://huggingface.co/YurinhoMatsumoto).

**Final thesis: RAG for case law search at STJ, Brazil's Superior Court of Justice.** A prototype that compares three retrieval strategies over tax crime rulings: sparse (BM25), dense (embeddings) and hybrid (RRF fusion). In progress.

### Other projects

- [plataforma-enem](https://github.com/YuriMatsumotoSantos/plataforma-enem): ENEM study platform in Next.js and TypeScript, with a pipeline that extracts and classifies exam questions using an LLM. In development.
- [enem-essay-classifier](https://github.com/YuriMatsumotoSantos/enem-essay-classifier): more than 15 classification algorithms over 4,570 essays, from TF-IDF to BERTimbau embeddings.
- [ProjetoIntegrador-DevOps](https://github.com/YuriMatsumotoSantos/ProjetoIntegrador-DevOps): Flask application with Prometheus metrics, Docker and CI.
- [sistemas-embarcados-freertos](https://github.com/YuriMatsumotoSantos/sistemas-embarcados-freertos) and [conversor-buck-controle-digital](https://github.com/YuriMatsumotoSantos/conversor-buck-controle-digital): real time and digital control on STM32.

### Tools

Python, Hugging Face Transformers, PEFT, TRL, vLLM, scikit-learn, TypeScript, Next.js, PostgreSQL, Docker, C for microcontrollers.

### Contact

[LinkedIn](https://www.linkedin.com/in/yuri-matsumoto-693138245/)
