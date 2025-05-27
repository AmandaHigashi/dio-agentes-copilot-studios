# Speech Studio e Language Studio da Microsoft: Visão Geral

As plataformas **Speech Studio** e **Language Studio** da Microsoft Azure são ferramentas poderosas que fornecem uma interface unificada e amigável para explorar, criar e gerenciar recursos de inteligência artificial focados em fala e linguagem. Elas simplificam o desenvolvimento de aplicações inteligentes que interagem com o mundo através de texto e voz.

---

## Microsoft Speech Studio

O **Speech Studio** é um portal baseado na web que centraliza as ferramentas e serviços relacionados à **voz e fala** da Microsoft Azure AI. Ele permite que desenvolvedores e cientistas de dados:

* **Sintetizem fala (Text-to-Speech):** Converta texto em áudio natural com diversas vozes pré-construídas ou crie vozes personalizadas.
* **Reconheçam fala (Speech-to-Text):** Transcreva áudio para texto, com suporte a transcrição em tempo real e em lote, além de modelos personalizáveis para domínios específicos.
* **Traduzam fala:** Ofereça tradução automática de fala para fala ou fala para texto.
* **Gerenciem endpoints e modelos de fala:** Configure e monitore os recursos de fala para suas aplicações.

**Uso Principal:** Ideal para assistentes virtuais, call centers, legendagem de vídeos, ditado e qualquer aplicação que necessite interagir por voz.

---

## Microsoft Language Studio

O **Language Studio** é o portal baseado na web para explorar e construir funcionalidades de **compreensão e processamento de linguagem natural (PLN)** dos serviços de Linguagem de IA do Azure. Ele oferece acesso fácil a recursos como:

* **Análise de Sentimentos:** Identifique o tom e a polaridade do texto (positivo, negativo, neutro).
* **Extração de Entidades Nomeadas (NER):** Detecte e classifique entidades como pessoas, locais, organizações e datas em textos.
* **Mineração de Ideias (Key Phrase Extraction):** Identifique os conceitos principais em um documento.
* **Compreensão de Linguagem Conversacional:** Desenvolva modelos para entender intenções e extrair entidades de conversas naturais.
* **Geração de Respostas para Perguntas (Question Answering):** Crie bases de conhecimento para responder a perguntas em linguagem natural.
* **Resumo e Geração de Texto:** Ferramentas para resumir documentos extensos ou gerar novo texto.

---

**Em Resumo:**

* **Speech Studio:** Foco na **interação por voz** (transformar texto em fala e fala em texto).
* **Language Studio:** Foco na **compreensão e processamento de texto** (analisar, entender e gerar linguagem escrita).

Ambas as plataformas são essenciais para construir soluções de IA robustas, permitindo que as empresas e desenvolvedores criem experiências mais intuitivas e inteligentes para os usuários.

---

# Desenvolvendo o Desafio

Escolheu-se a plataforma do Speech Studio para testar a transcrição automática de áudio para texto. Com isso, pegou-se a letra de uma música e foram feitos os seguintes testes:

* **Etapa 1:** Leitura normal do texto em inglês, realizando pausas e falando calmamente.
* **Etapa 2:** A leitura do texto foi realizada conforme o ritmo da música.

Com base nisso, analisou-se os dois outputs:

* **Etapa 1:** Texto foi digitado corretamento com praticamente 100% de acerto, apenas algumas falhas em relação a pontuação.
* **Etapa 2:** Texto teve alta taxa de erro, sendo os principais em identificação das palavras.

Ambos *outputs* podem ser visualizados [aqui!](imagens/)

### Conclusão
Percebe-se que aplicação falhou com a entrada de uma voz mais ritmada. Contudo, podem ser realizados mais treinos com a música em específico para que o agente entenda melhor a dinâmica e assim consiga atingir uma assertividade maior.
Um questionamento que fica, será que com a alteração de ritmo, o agente treinado seria capaz de identificar os textos corretamente? Ou ele funcionaria apenas para aquele determinado ritmo?
