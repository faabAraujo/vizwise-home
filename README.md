# 🌌 Viz Wise - Painel de Sistemas

O **Viz Wise** é um painel de controlo (dashboard) centralizado que permite o acesso rápido a várias plataformas, hiperligações e sistemas[cite: 1, 2]. Concebido com um design moderno em *Glassmorphism*, o painel foca-se na produtividade, na organização e numa estética minimalista[cite: 1, 2].

## ✨ Funcionalidades Principais

* **Design em Glassmorphism Transparente:** Interface baseada em cartões translúcidos (efeito de vidro) que se adaptam perfeitamente ao plano de fundo dinâmico[cite: 1, 2]. Foi adicionado suporte nativo para alternar entre o **Tema Claro e Tema Escuro**, guardando a preferência do utilizador para futuras visitas.
* **Layout Adaptativo (Sem Scroll Global):** A interface foi otimizada para ocupar exatamente a altura do ecrã (`h-screen`), eliminando as barras de rolagem externas. As listas longas de hiperligações fazem scroll apenas internamente dentro dos seus respetivos cartões.
* **Planos de Fundo Dinâmicos:** As imagens de fundo são geradas de forma dinâmica através de uma API do Google Apps Script[cite: 1, 2]. O sistema inclui ainda uma lista de imagens de alta resolução (Unsplash) como alternativa (fallback) de segurança, com transições suaves (cross-fade) entre cada mudança[cite: 1, 2].
* **Personalização de Layout (Drag & Drop):** Graças à integração da biblioteca SortableJS, é possível arrastar e reordenar livremente os cartões de sistemas[cite: 1, 2]. A disposição escolhida é guardada automaticamente no browser (`localStorage`)[cite: 1, 2].
* **Pesquisa Rápida Inteligente:** Barra de pesquisa central que permite aceder diretamente a URLs ou efetuar pesquisas na web[cite: 1, 2]. Pode ser focada instantaneamente pressionando a tecla `/`[cite: 1, 2].
* **Gestão de Separadores:** Alternância fluida entre a vista principal de "Sistemas" (lista de ligações) e o separador de "Agenda", que integra perfeitamente o Google Calendar num iframe adaptado[cite: 1, 2].
* **Relógio em Tempo Real:** Apresentação elegante da hora atualizada ao segundo e da data no topo da página[cite: 1, 2].
* **Modo Ecrã Inteiro:** Botão dedicado para expandir o painel para todo o ecrã, maximizando o espaço de trabalho[cite: 1, 2].

## 🛠️ Tecnologias Utilizadas

* **HTML5** para a estrutura semântica da página[cite: 1, 2].
* **Tailwind CSS** (via CDN) para uma estilização rápida, responsiva e utilitária[cite: 1, 2].
* **JavaScript (Vanilla)** para a lógica de estado, controlo de temas, chamadas assíncronas à API e atualizações de interface[cite: 1, 2].
* **SortableJS** para a interatividade fluida de arrastar e largar cartões[cite: 1, 2].
* **Font Awesome & Phosphor Icons** para a iconografia vetorial[cite: 1, 2].
* **Google Fonts** (Plus Jakarta Sans e JetBrains Mono) para garantir uma tipografia moderna e legível[cite: 1, 2].

## 📦 Estrutura de Sistemas Integrados

O painel organiza as hiperligações de acesso diário em diferentes módulos organizacionais:
* **Regionais:** Paraná, Mato Grosso, Minas Gerais, Bahia e HMG Bahia (Incluindo os ambientes operacionais de notas, protesto, financeiro, RCPN, SPJ e Imóveis)[cite: 1, 2].
* **Ferramentas Internas e Suporte:** Links Úteis (Google Drive com áreas DEV, Suporte, Planilhas, Manuais e Gravações)[cite: 1, 2].
* **Desenvolvedor:** Acesso direto ao repositório Gitea (Offline)[cite: 1, 2].
* **Sistemas Avulsos:** Atalhos rápidos para o uso do servidor, emissão de certidões, gestão de senhas, WhatsApp Web e comunicação pelo Vizchat[cite: 1, 2].

## 🚀 Como Executar e Utilizar

Como o projeto é construído integralmente com tecnologias front-end estáticas e sem necessidade de compilação (build tools), a sua utilização é extremamente simples:

1. Guarde o código fornecido num ficheiro local com a extensão `.html` (por exemplo, `dashboard.html`).
2. Abra o ficheiro diretamente em qualquer navegador web moderno (Google Chrome, Firefox, Safari ou Edge).
3. **Personalização do Logótipo:** Pode procurar pela zona indicativa de *placeholder* no código HTML e descomentar ou ajustar a tag `<img>` para inserir a sua marca gráfica (SVG ou PNG)[cite: 1, 2].

---
*Nota técnica: A posição reordenada dos cartões, o tema ativo (claro/escuro) e o último separador aberto são persistidos de forma privada na memória local do navegador (`localStorage`) de cada utilizador[cite: 1, 2].*
