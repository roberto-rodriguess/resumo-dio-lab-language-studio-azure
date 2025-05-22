# resumo-dio-lab-language-studio-azure

Esta sessão explora as ferramentas de processamento de linguagem natural da Microsoft Azure, com foco no Language Studio e nos serviços de fala e bot. A apresentação inclui demonstrações práticas e casos de uso para estes serviços.

### Language Studio

O Language Studio é um conjunto de ferramentas baseadas em interface do usuário que permite explorar e criar recursos de linguagem. Suas principais funcionalidades incluem:

- Identificação do idioma predominante em textos
- Análise de sentimento (positivo, negativo, neutro)
- Extração de frases-chave e palavras-chave
- Identificação de entidades (como localizações)
- Classificação personalizada de textos

Estas ferramentas são particularmente úteis para análise de grandes volumes de dados textuais, como feedbacks de clientes, onde seria impossível processar manualmente.

### Serviço de Bot do Azure

O serviço de bot evoluiu significativamente e agora oferece:

- Capacidade de compreender linguagem natural mesmo com erros
- Integração com inteligência artificial para melhorar respostas
- Conectividade através de múltiplos canais (aplicativos, sites, e-mail, telefone, Microsoft Teams)
- Criação de funis de atendimento para otimizar recursos humanos

A eficiência do bot depende diretamente da qualidade da base de dados disponível, sendo fundamental testar e retestar continuamente as implementações.

### Compreensão da Linguagem Coloquial

A capacidade de entender linguagem cotidiana é composta por três componentes principais:

- Declaração: o que está sendo solicitado
- Entidade: o item específico (como um dispositivo)
- Intenção: a ação desejada

Estes elementos são fundamentais para sistemas de comando por voz e automação residencial.

### Reconhecimento e Síntese de Fala

Estes serviços permitem:

- Converter texto em fala e vice-versa
- Suporte a mais de 60 idiomas
- Aplicações para acessibilidade (auxiliando pessoas com problemas de visão)
- Uso prático em situações como direção (mensagens mãos-livres)

### Demonstrações Práticas

A sessão incluiu dois laboratórios práticos:

**Speech Studio:**

- Acesso ao portal através de [speech.microsoft.com](http://speech.microsoft.com/)
- Demonstração de conversão de fala em texto em tempo real
- Exemplos de aplicação e análise de código no GitHub

**Language Studio:**

- Criação de recursos de idioma no Azure
- Análise de sentimento em avaliações de hotel
- Demonstração de como o sistema identifica sentimentos negativos (96% negativo em um exemplo)
- Aplicação para análise de feedback de clientes em larga escala
