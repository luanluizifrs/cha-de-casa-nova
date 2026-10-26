# 🏡 Lista Interativa — Chá de Casa Nova

Aplicação web desenvolvida sob medida para gerenciamento de lista de presentes de **Chá de Casa Nova** em tempo real, evitando presentes repetidos e facilitando a contribuição dos convidados via PIX ou links diretos.

![Demonstração da Página](./demo-cha-casa-nova.gif)

## ✨ Funcionalidades

- **Reserva em Tempo Real:** Assim que um convidado reserva um item, ele é bloqueado instantaneamente para todos os outros acessos utilizando o **Firebase Realtime Database (`onValue`)**.
- **Busca e Filtros Inteligentes:** Pesquisa rápida por nome do item e filtros dinâmicos (*Todos*, *Disponíveis* e *Reservados*) com contador atualizado ao vivo.
- **PIX Integrado com 1 Clique:** Botão *Copy to Clipboard* com feedback visual imediato.
- **Design Personalizado e Responsivo:** Interface inspirada na identidade visual e paleta botânica do convite do evento, otimizada para celulares e desktops.

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3 (Variáveis CSS, Flexbox, Grid, SVG) e JavaScript Vanilla (ES Modules)
- **Banco de Dados em Tempo Real:** Firebase Realtime Database (SDK Modular v10.8.1)
- **Hospedagem / Deploy:** Netlify / GitHub Pages
