# Análise de Sentenças com Inteligência Artificial

Este projeto tem como objetivo realizar a análise de algumas sentenças utilizando técnicas de Processamento de Linguagem Natural (PLN). Utilizamos um modelo de IA para realizar a análise de sentimentos das falas de Thanos, personagem da Marvel, e observar os insights emocionais por trás de suas palavras.

## Como Funciona?

As sentenças são analisadas por um modelo de IA para identificar padrões e sentimentos. O modelo atribui um sentimento geral para cada sentença, além de calcular a confiança da análise.

## Sentenças de Exemplo

1. "A natureza está em equilíbrio. A destruição é necessária para a renovação."
2. "Eu sou inevitável."
3. "Com a morte de metade da população, o universo alcançará o equilíbrio."
4. "O que é um sacrifício, senão um preço a ser pago pela grandeza?"
5. "O poder está nas mãos de quem controla a morte."

## Análise de Sentimentos das Frases de Thanos

Utilizando o modelo **`nlptown/bert-base-multilingual-uncased-sentiment`** para análise de sentimentos, as seguintes observações foram feitas:

1. **"A natureza está em equilíbrio. A destruição é necessária para a renovação."**
   - **Sentimento**: **Positivo**  
   - **Confiança**: 0.50  
   - **Análise**: Thanos vê a destruição como algo necessário para o equilíbrio, com uma visão mais positiva do processo de renovação.

2. **"Eu sou inevitável."**
   - **Sentimento**: **Muito Negativo**  
   - **Confiança**: 0.41  
   - **Análise**: A frase de Thanos transmite uma ideia de fatalismo e de inevitabilidade, um sentimento que foi classificado como negativo pela IA, possivelmente refletindo o tom sombrio e a certeza de suas ações.

3. **"Com a morte de metade da população, o universo alcançará o equilíbrio."**
   - **Sentimento**: **Muito Positivo**  
   - **Confiança**: 0.41  
   - **Análise**: Embora a frase fale de morte, a perspectiva de Thanos sobre o equilíbrio traz um sentimento positivo, mostrando sua crença de que a morte é um meio para alcançar um fim maior e mais harmonioso.

4. **"O que é um sacrifício, senão um preço a ser pago pela grandeza?"**
   - **Sentimento**: **Neutro**  
   - **Confiança**: 0.24  
   - **Análise**: Essa frase reflete uma filosofia pragmática sobre sacrifícios, sem evocar emoções muito intensas, por isso recebeu uma análise neutra.

5. **"O poder está nas mãos de quem controla a morte."**
   - **Sentimento**: **Muito Positivo**  
   - **Confiança**: 0.23  
   - **Análise**: Thanos associa o poder à morte, refletindo sua visão de domínio absoluto e controle, o que é classificado como muito positivo, provavelmente devido ao tom de força e domínio da frase.

## Insights Obtidos

- **Visão de Thanos sobre equilíbrio e destruição**: Thanos acredita que a destruição e a morte são essenciais para criar equilíbrio no universo, algo que ele considera necessário para a renovação e prosperidade a longo prazo. O modelo de IA reflete isso em sua análise de sentimentos, variando de positivo a muito negativo, dependendo do contexto de cada fala.
  
- **Sacrifício como meio para grandeza**: Ele vê a morte como um sacrifício justificado para alcançar um objetivo maior, reforçando a ideia de que grandes conquistas exigem grandes sacrifícios. Isso é refletido em suas falas, sendo muitas delas vistas de forma neutra ou positiva, dependendo do contexto.

- **Poder e controle**: A frase "o poder está nas mãos de quem controla a morte" pode ser vista como uma crítica à busca pelo controle absoluto, mostrando como a morte e o poder andam de mãos dadas em sua filosofia. Essa frase foi analisada como positiva, o que pode sugerir uma visão de confiança e força.

- **Inevitabilidade de suas ações**: A frase "Eu sou inevitável" reflete a inevitabilidade de suas ações, que ele acredita serem parte de um plano cósmico e universal que não pode ser detido. O sentimento associado a isso foi muito negativo, talvez devido ao tom sombrio da frase.

## Possíveis Melhorias

- **Modelos de análise mais profundos**: Implementar mais modelos de análise de texto para explorar a psicologia por trás das falas dos personagens, como no caso do Thanos, para entender melhor o comportamento de personagens complexos e suas motivações emocionais.

- **Análise de sentimentos mais granular**: Explorar técnicas mais avançadas de PLN, como a análise de sentimentos, para classificar as falas de Thanos em diferentes categorias emocionais (ex.: raiva, desdém, convicção) e identificar o tom emocional por trás de suas palavras.

- **Visualização da evolução emocional**: Criar uma visualização que mostre como o personagem evolui ao longo dos filmes com base nas falas e como seu discurso impacta outros personagens e o público.

## Aprendizados

- **Uso de IA para análise de sentimentos**: Aprendi a utilizar modelos de IA para analisar textos e emoções relevantes. Isso proporcionou uma compreensão mais profunda de como os personagens podem ser analisados através de suas falas.

- **Tratamento e preparação de dados de texto**: Entendi como preparar e tratar dados de texto para análise, além de como implementar pipelines de PLN eficientes.

## Tecnologias Utilizadas
- **Google colab**: Para execução do codigo Python
- **GitHub**: Para versionamento de código e controle do projeto.
- **Ferramentas de PLN**: Como o modelo **nlptown/bert-base-multilingual-uncased-sentiment** da Hugging Face para análise de sentimentos.
