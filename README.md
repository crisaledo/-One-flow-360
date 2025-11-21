 CRM Light com Assistente Gemini Personalizável

Este é um Sistema de Gerenciamento de Relacionamento com o Cliente (CRM) leve e de arquivo único, projetado para pequenas empresas e freelancers. Ele integra funcionalidades básicas de gestão de leads, agendamento e um poderoso assistente de conteúdo alimentado pela API Gemini, que pode ser totalmente personalizado para a voz da sua marca.

🚀 Funcionalidades Principais

Gestão de Leads: Adicione, visualize e gerencie clientes potenciais em tempo real com status (Novo, Contatado, Agendado, Ganho, Perdido) através do Firestore.

Gestão de Agendamentos: Adicione compromissos com detalhes de serviço e notas.

Automação (Gatilho): Ao agendar um serviço, o sistema procura o lead e automaticamente atualiza seu status para 'Agendado'.

Assistente de Conteúdo Gemini Personalizável:

Persona Customizável: Defina a voz, o tom e as regras do seu assistente de IA através de uma Instrução de Sistema, salvando-a no Firestore.

Geração Inteligente: Use a IA para gerar e-mails, posts de mídia social ou mensagens de acompanhamento, com a opção de personalizar o conteúdo para um lead específico (nome e serviço de interesse).

Ações Rápidas: Copie o conteúdo gerado ou envie-o diretamente para o WhatsApp do lead.

Conexões: Salve seus links de contato (WhatsApp, Instagram, Email) para acesso rápido.

🛠️ Tecnologias Utilizadas

Frontend: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN)

Backend/Dados: Google Firestore (para persistência de Leads, Agendamentos e Configurações de IA)

Inteligência Artificial: Gemini API (gemini-2.5-flash-preview-09-2025) para geração de conteúdo.

⚙️ Instalação e Uso

Este projeto é um aplicativo de página única (SPA) e pode ser implantado facilmente usando o GitHub Pages. Você precisará de um ambiente que forneça as configurações do Firebase e a chave da API Gemini em tempo de execução para que todas as funcionalidades de persistência de dados e IA funcionem.
