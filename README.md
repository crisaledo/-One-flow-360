# CRM Light com Assistente Gemini Personalizável

Este é um Sistema de Gerenciamento de Relacionamento com o Cliente (CRM) leve e de arquivo único, projetado para pequenas empresas e freelancers. Ele integra funcionalidades básicas de gestão de leads, agendamentos e automações, além de um assistente de conteúdo baseado na API Gemini.

## 🚀 Funcionalidades Principais

- Gestão de Leads: Adicione, visualize e gerencie clientes potenciais com status (Novo, Contatado, Agendado, Ganho, Perdido).
- Gestão de Agendamentos: Adicione compromissos com detalhes de serviço e notas.
- Automações simples: Ao agendar um serviço, o sistema pode atualizar o status do lead automaticamente.
- Assistente de Conteúdo Gemini Personalizável: configure persona, tom e instruções do assistente e gere e-mails, posts ou mensagens de acompanhamento.
- Ações rápidas: copiar conteúdo gerado ou enviar para WhatsApp do lead.

## 🛠️ Tecnologias

- Frontend: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN)
- Backend/Dados: Google Firestore
- Inteligência Artificial: Gemini API

## ⚙️ Instalação e Uso Rápido

1. Clone o repositório:
   git clone https://github.com/crisaledo/-One-flow-360.git
2. Abra o arquivo index.html em um servidor local (recomendado) ou diretamente no navegador. Para um servidor simples:
   - Python 3: python -m http.server 8000
   - Node (http-server): npx http-server . -p 8000
3. Configure as credenciais do Firebase e da API Gemini conforme seu ambiente (variáveis ou arquivo de configuração). Não suba chaves privadas ao repo.

## ✅ Checklist de Acessibilidade (simples)
Use esta checklist para testar rapidamente aspectos essenciais de acessibilidade antes de publicar.

- [ ] Elementos clicáveis são acessíveis por teclado (Tab/Enter/Space).
  - Como testar: navegue com Tab e ative menu/ações com Enter ou Space.
  - Resultado esperado: foco visível e ação executada.
- [ ] Uso correto de elementos semânticos (buttons, headings, labels).
  - Como testar: inspecione o HTML e confirme botões para ações e labels para inputs.
- [ ] Estados ARIA básicos para tabs/painéis.
  - Como testar: verifique aria-selected e aria-hidden ao navegar entre abas.
- [ ] Contaste de cores suficiente para texto e elementos interativos.
  - Como testar: use https://contrast-ratio.com/ ou a extensão Lighthouse/AXE.
  - Resultado esperado: contraste >= 4.5:1 para texto normal.
- [ ] Inputs têm labels associados (visíveis ou sr-only).
  - Como testar: verifique se cada input tem um label ou aria-label.
- [ ] Foco visível em elementos interativos.
  - Como testar: navegue com teclado e confira outlines ou estilos de foco.
- [ ] Conteúdo legível em diferentes tamanhos de tela (responsividade).
  - Como testar: redimensione a janela ou use as ferramentas do devtools.
- [ ] Navegação por leitores de tela (básico).
  - Como testar: abra um leitor de tela (NVDA/VoiceOver) e confira se a ordem/semântica faz sentido.

## 🧪 Testes de Usabilidade Simples (passos manuais)
Execute estes testes rapidamente para garantir o fluxo principal funciona.

- Teste 1 — Navegação das abas
  1. Abra a página.
  2. Clique em cada item do menu lateral.
  3. Verifique se o painel correspondente é mostrado e o menu recebe o estado ativo.
  4. Resultado esperado: conteúdo muda sem erros e aria-selected/aria-hidden atualizados.

- Teste 2 — Busca de leads (campo de exemplo)
  1. Digite no campo "Buscar lead..." e observe comportamento (se houver filtro implementado).
  2. Resultado esperado: não há erro JS e campo é editável com keyboard.

- Teste 3 — Acessibilidade de formulários
  1. Abra Configurações e navegue até inputs.
  2. Teste preencher nome e email.
  3. Resultado esperado: labels visíveis ou associadas e inputs aceitam entrada.

- Teste 4 — Responsividade rápida
  1. Abra em uma tela pequena (mobile) ou use devtools.
  2. Verifique se layout não quebra e elementos ficam visíveis/acionáveis.

## Como contribuir
- Abra uma issue descrevendo o problema ou a melhoria.
- Faça um fork, crie uma branch com o seu ajuste e envie um Pull Request.

## Segurança
- Nunca inclua chaves de API ou credenciais no repositório público. Use variáveis de ambiente ou um arquivo de configuração que esteja no .gitignore.

## Contato
Para dúvidas, abra uma issue ou contate: crisaledo (GitHub)

----

(Adicionado checklist de acessibilidade e instruções de testes de usabilidade simples.)