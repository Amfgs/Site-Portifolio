# Meu Portfólio

Este é um site simples de portfólio pessoal com três páginas principais: **Início**, **Sobre Mim** e **Projetos**.

---

## Estrutura do Site

### 1. Página Início (`index.html`)
- Página principal do portfólio (não fornecida aqui, mas mencionada nos links).
- Contém uma introdução ao portfólio e navegação para as outras seções.

### 2. Página Sobre Mim (`sobremim.html`)
- Apresenta informações pessoais e profissionais.
- Seções principais:
  - **Interesses Profissionais:** Listagem de preferências para estágios presenciais e remotos, além das áreas de interesse.
  - **O que me inspira?:** Texto motivacional e fontes de inspiração.
  - **Habilidades:** Lista de tecnologias e competências técnicas.
- Layout responsivo e estilizado por `sobre.css` e `index2.css`.
- Navegação e menu mobile controlados por `script.js`.

### 3. Página Projetos (`projeto.html`)
- Mostra projetos desenvolvidos com destaque para o "Gaita Hero".
- Estrutura dividida em:
  - **Projeto em destaque:** Descrição detalhada do projeto.
  - **Galeria de imagens:** Imagens relacionadas ao projeto, organizadas em grid responsivo.
- Estilos aplicados via `index2.css` e `projeto.css`.
- Menu com navegação responsiva ativada pelo `script.js`.

---

## Arquivos Principais

- **HTML**
  - `index.html` (não fornecido, mas previsto)
  - `sobremim.html` — Página Sobre Mim
  - `projeto.html` — Página de Projetos

- **CSS**
  - `index2.css` — Estilos gerais do site (tipografia, cores, layout base, menu)
  - `sobre.css` — Estilos específicos da página Sobre Mim
  - `projeto.css` — Estilos específicos da página Projetos

- **JavaScript**
  - `script.js` — Controle do menu responsivo (toggle do menu em telas menores e fechamento ao clicar em links)

---

## Funcionamento do Menu

- No desktop, o menu aparece como uma barra horizontal no topo.
- Em telas menores (até 768px), o menu é ocultado e pode ser aberto clicando no botão ☰.
- Quando aberto no mobile, o menu é exibido verticalmente.
- Ao clicar em qualquer link do menu no mobile, o menu é automaticamente fechado.

---

## Como usar

1. Coloque todos os arquivos (`.html`, `.css`, `.js` e imagens) na mesma pasta ou estrutura adequada.
2. Abra os arquivos HTML no navegador.
3. Navegue pelas páginas usando o menu no topo.
4. O site é responsivo e se adapta a diferentes tamanhos de tela.
