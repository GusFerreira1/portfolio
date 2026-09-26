# Processo — Portfólio

## 1. O que eu pedi à IA

Crie uma landing page em um único arquivo `index.html` (HTML, CSS e JavaScript juntos, sem bibliotecas externas) que apresente o meu portfólio pessoal.

### Sobre mim informado no prompt:
- **Nome:** Gustavo Ferreira
- **Apelido / Nick:** Guess
- **Idade e Cidade:** 15 anos, Varginha - MG
- **Curso técnico:** Informática para a Internet
- **Três coisas que me definem:** Automobilismo, Fórmula 1 e Carros
- **Equipe que torço na F1:** Ferrari
- **O que eu quero fazer no futuro:** Trabalhar na área de TI
- **Hobby / Curiosidade:** Sou quieto, gosto de passar a maior parte do tempo jogando videogame (jogar online é um interesse que pouca gente sabe)
- **Música no rodapé:** Highest in the Room

---

## 2. O que a IA me entregou

A IA gerou a primeira versão da página contendo:
- **Cabeçalho:** Nome de exibição e alternador de tema (Claro/Escuro).
- **Hero:** Animação gráfica com carros de corrida em fundo dinâmico, vetor da Ferrari e interatividade de confetes acionada ao clicar no nome.
- **Seção Sobre Mim:** Textos organizados com destaque para as características pessoais e profissionais.
- **Carrossel de Entregas:** Cards interativos em 3D (efeito *tilt* ao passar o mouse e *flip/giro* ao clicar) para apresentar os projetos do curso.
- **Manifesto:** Caixa de texto expansível para o manifesto pessoal.
- **Rodapé:** Links de contato (`gustavoferreira122011@gmail.com` e GitHub) e widget de áudio com equalizador animado.

---

## 3. O que eu pedi para mudar

Durante o desenvolvimento do projeto, fiz os seguintes pedidos de ajustes e correções:

1. **Limpeza e Correção de Código:**
   - Remoção de repetições desnecessárias e acertos na estrutura sintática do HTML/CSS para evitar falhas no deploy.
2. **Compatibilidade com o GitHub Pages:**
   - Padronização do nome do arquivo principal estritamente para `index.html` (em minúsculas e sem sufixos como `(1)`), prevenindo erros de rota 404 ao publicar.
3. **Ajustes Visuais e Responsividade:**
   - Correção na escala da imagem de perfil e tratamento de fallback (inicial "G") caso a foto não carregue.
   - Ajustes de layout para garantir o alinhamento correto das seções em dispositivos móveis.

---

## 4. Aprendizado

Construir este projeto me permitiu entender na prática como funciona o fluxo de desenvolvimento de uma landing page moderna:

- **Estruturação e Semântica:** Aprendi a organizar um arquivo único contendo HTML5, CSS3 e JavaScript sem depender de bibliotecas externas.
- **Interatividade e UX:** Compreendi como aplicar variáveis CSS para controle de temas, animações interativas em Canvas e efeitos 3D de rotação nos cards.
- **Engenharia de Prompt e Refatoração:** Percebi a importância de revisar o código gerado por IA, ajustar partes que não funcionavam como esperado e fazer o deploy correto no GitHub Pages.
