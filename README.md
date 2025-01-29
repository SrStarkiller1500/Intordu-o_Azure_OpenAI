

# Introdução ao Azure OpenAI 🤖

Neste repositório, decidi montar um resumo dos conteúdos apresentados nos primeiros módulos do curso, pois não consegui o acesso grátis ao portal do Azure OpenAI.



## Azure OpenAI Service

O **Azure OpenAI Service** é uma plataforma que permite aos desenvolvedores e empresas acessar e utilizar os poderosos modelos de linguagem da OpenAI, como GPT-4, GPT-3.5-Turbo e DALL-E, através da infraestrutura da Microsoft Azure.

### Modelos Avançados

O Azure OpenAI oferece acesso a modelos de linguagem de última geração, incluindo:
- **GPT-4**
- **GPT-3.5-Turbo**
- **DALL-E**

Esses modelos são ideais para tarefas complexas como geração de código, resolução de problemas e criação de conteúdo.

### Integração com Azure

O serviço é integrado à plataforma Azure, permitindo fácil implementação e escalabilidade. Você pode combinar o Azure OpenAI com outros serviços da Azure para criar soluções abrangentes e avançadas.

### Exemplos de Uso e àreas que podemos usar a aplicação 

O Azure OpenAI pode ser aplicado em várias áreas, como:
- **Automação de Atendimento ao Cliente**: Automatizar suporte ao cliente, resumir conversas e fornecer coaching em tempo real para agentes.
- **Geração de Conteúdo**: Criar conteúdo personalizado para marketing, descrições de produtos e arte digital.
- **Análise de Dados**: Analisar dados proprietários para obter insights mais inteligentes e melhorar fluxos de trabalho em setores como finanças, saúde e varejo.
- **Automação de Fluxos de Trabalho**: Otimizar operações e cadeias de suprimentos automatizando tarefas rotineiras.

### Segurança e Conformidade

O Azure OpenAI inclui filtros de segurança de conteúdo e segue os princípios de IA responsável da Microsoft, garantindo que o uso dos modelos seja seguro e ético.

### Acesso e Personalização

Os usuários podem acessar o serviço através de:
- **APIs REST**
- **SDKs em Python**
- **Portal Azure AI Foundry**

É possível personalizar os modelos para tarefas específicas e ajustar parâmetros conforme necessário.



## Parâmetros de Modelos de Linguagem

Aqui fica um breve resumo sobre os parâmetros de modelos de linguagem apresentados no início do curso do Azure OpenAI.



### Temperatura

**Definição**: A temperatura é um parâmetro que ajusta a aleatoriedade das previsões do modelo.

**Funcionamento**: 
- Temperatura baixa (ex.: 0.2): O modelo escolhe palavras mais prováveis, resultando em respostas mais previsíveis e conservadoras.
- Temperatura alta (ex.: 0.8): O modelo escolhe palavras menos prováveis com mais frequência, gerando respostas mais variadas e criativas.

**Uso Prático**: Ajusta o tom e a criatividade das respostas, útil para tarefas criativas como escrever poesia.

### Top P (Núcleo de Amostragem)

**Definição**: Top P é um método de amostragem que considera apenas os tokens que, juntos, somam uma certa porcentagem da probabilidade total.

**Funcionamento**: 
- Se Top P = 0.9, o modelo seleciona palavras até que a soma de suas probabilidades atinja 90%, excluindo palavras menos prováveis.

**Uso Prático**: Controla a qualidade e a relevância das respostas, evitando incoerências.

### Tokens Máximos

**Definição**: Define o número máximo de tokens que o modelo pode gerar em uma resposta.

**Funcionamento**: Limita a duração das respostas, garantindo concisão.

**Uso Prático**: Essencial para aplicações que requerem respostas rápidas e curtas, como chatbots.

### Penalidades

#### Penalidade de Repetição

**Definição**: Reduz a probabilidade de o modelo repetir as mesmas palavras ou frases.

**Uso Prático**: Evita redundâncias e melhora a fluidez do texto.

#### Penalidade de Comprimento

**Definição**: Ajusta a probabilidade de gerar respostas mais longas ou mais curtas.

**Uso Prático**: Controla a extensão das respostas, garantindo que o texto não seja nem muito curto nem excessivamente longo.

### Sistema de Mensagens

**Definição**: Refere-se à estrutura e ao fluxo de comunicação entre o usuário e o modelo.

**Funcionamento**: Inclui como as mensagens são enviadas, processadas e respondidas pelo modelo, garantindo uma interação fluida.

**Uso Prático**: Essencial para criar uma experiência de usuário eficiente e intuitiva, permitindo que o modelo entenda e responda adequadamente às solicitações.