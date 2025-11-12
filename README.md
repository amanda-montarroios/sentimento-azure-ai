# Análise de Sentimentos com Language Studio no Azure AI
## Análise de Texto e Respostas a Perguntas 🧾
**Extração de Informações:** Ferramentas como o reconhecimento de entidades nomeadas (NER) permitem identificar e categorizar entidades em um texto, como nomes de pessoas, locais, organizações e datas. Isso é crucial para organizar dados não estruturados e facilitar a busca por informações específicas.

**Análise de Sentimento:** A capacidade de determinar o sentimento (positivo, negativo ou neutro) expresso em um texto é vital para monitoramento de marca, análise de feedback de clientes e compreensão da opinião pública.

**Extração de Frases-Chave:** Identificar os principais pontos de discussão em um documento por meio da extração de frases-chave ajuda a resumir o conteúdo e a entender rapidamente os tópicos abordados.

**Respostas a Perguntas (Question Answering):** Essa funcionalidade permite que os usuários façam perguntas em linguagem natural e recebam respostas precisas extraídas de um conjunto de documentos ou de uma base de conhecimento. Isso é a base para a criação de assistentes virtuais e sistemas de busca inteligentes.

**Resumo de Texto:** A sumarização de documentos, tanto extrativa (selecionando as sentenças mais importantes) quanto abstrativa (gerando um resumo conciso com novas frases), é uma ferramenta poderosa para lidar com grandes volumes de informação.

## Serviço de Bot do Azure (Azure Bot Service) 💻
**Desenvolvimento Integrado:** O serviço se integra perfeitamente com o Bot Framework SDK, oferecendo aos desenvolvedores as ferramentas necessárias para criar lógicas de conversação complexas.

**Canais de Comunicação:** Um dos grandes diferenciais do Azure Bot Service é a facilidade de conectar um bot a múltiplos canais de comunicação, como Microsoft Teams, Slack, Facebook Messenger e até mesmo canais de voz, com mínimas alterações no código.

**Inteligência de Conversação:** A verdadeira força dos bots criados com o Azure Bot Service reside na sua capacidade de compreender e responder de forma inteligente. Isso é alcançado através da integração com outros serviços de IA do Azure, como o de Compreensão da Linguagem Coloquial (CLU) e o de Respostas a Perguntas.

**Gerenciamento e Escalabilidade:** A plataforma Azure garante que os bots possam ser gerenciados de forma centralizada, com monitoramento de desempenho e a capacidade de escalar para atender a altas demandas de usuários.

## Compreensão da Linguagem Coloquial (Conversational Language Understanding - CLU) 🤓
**Intenções e Entidades:** O núcleo do CLU é a capacidade de identificar a intenção do usuário (o que ele quer fazer) e as entidades (as informações específicas relacionadas a essa intenção). Por exemplo, em "Quero reservar um voo para Recife amanhã", a intenção é "reservar voo" e as entidades são "Recife" (destino) e "amanhã" (data).

**Modelos Pré-construídos e Personalizados:** O CLU oferece modelos pré-construídos para cenários comuns, mas sua principal vantagem é a capacidade de treinar modelos personalizados com dados específicos de um domínio, o que aumenta significativamente a precisão da compreensão.

**Fluxo de Conversa:** A integração do CLU com o Azure Bot Service permite a criação de fluxos de conversa dinâmicos e inteligentes. O bot pode entender a solicitação do usuário, extrair os parâmetros necessários e tomar as ações apropriadas, como consultar um banco de dados ou chamar uma API.

**Multilinguismo:** O CLU suporta múltiplos idiomas, permitindo que os bots interajam com uma audiência global. teste de commit
