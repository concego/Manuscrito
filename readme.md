# Manuscrito - Estúdio de Publicação Portátil 🚀

O **Manuscrito** é uma ferramenta estática, leve e ultra-acessível desenvolvida para transformar a rotina de escritores, cronistas e estudantes que precisam diagramar textos e imagens diretamente pelo celular, sem a complexidade e os problemas de acessibilidade dos editores de texto tradicionais.

Nascido inteiramente no ambiente mobile, o projeto resolve uma dor real: a dificuldade de posicionar imagens e manter uma formatação estável usando leitores de tela em dispositivos móveis. Tudo funciona localmente em um **único arquivo HTML**, sem dependências externas, sem servidores e com foco total em privacidade e autonomia.

---

## 🔥 Recursos Principais

* **Entrada Flexível de Conteúdo:** Faça o upload de múltiplos arquivos do sistema (`.txt`, `.md`, `.jpg`, `.png`) de uma só vez ou simplesmente cole seu texto copiado direto na caixa de entrada.
* **Mesa de Operação Acessível:** Um sumário interativo com botões totalmente otimizados para leitores de tela, permitindo ordenar os capítulos ("Subir" e "Descer") e excluir elementos com autonomia total e retorno de foco inteligente.
* **Salvamento e Backup Completo (JSON):** Salve todo o estado atual da sua mesa de trabalho (incluindo textos colados e imagens convertidas) em um único arquivo `.json`. Para continuar escrevendo no dia seguinte ou após atualizar a aba do celular, basta carregar o arquivo de backup e o sistema reconstrói tudo instantaneamente.
* **Sumário Dinâmico no PDF:** Se ativado nas configurações, o sistema varre seus textos procurando marcações de capítulo (linhas iniciadas com `#`) e gera automaticamente uma página de "Índice" perfeitamente diagramada no topo do documento impresso.
* **Descrição Acessível de Imagens (Texto Alt):** Pensado para a acessibilidade de ponta a ponta, cada imagem carregada ganha um campo de texto dedicado para que o autor insira a descrição da ilustração. Esse texto é injetado diretamente no atributo `alt` das tags na hora de exportar.
* **Posicionamento Inteligente de Imagens:** Esqueça o pesadelo de arrastar imagens na tela do celular. Escolha o alinhamento (Bloco inteiro, deslocado à esquerda ou à direita) por meio de menus semânticos simples.
* **Templates de Estilo Prontos:** 
    * *Crônicas e Histórias:* Letra serifada elegante e parágrafos com recuo clássico.
    * *Trabalho Acadêmico:* Estruturado sob as diretrizes gerais das normas ABNT (Times New Roman, espaçamento 1.5 e texto justificado).
    * *Poesia:* Fonte monoespaçada com blocos de texto centralizados na folha.
    * *Carta / Documento Geral:* Visual limpo em Arial com linhas bem espaçadas.
    * *Relatório Técnico:* Fonte Calibri com títulos marcados e cabeçalhos destacados.
* **Exportação Multiformato:** Além de compilar para PDF através da API nativa de impressão do navegador, exporte sua obra consolidada em formatos universais como Texto Puro (`.txt`), Markdown (`.md`) ou como uma Página Web Completa (`.html`).

---

## 🛠️ Como Executar o Projeto

Por ser um *Single-File Application* (aplicação de arquivo único), você não precisa instalar nada:

1. Baixe o arquivo `index.html` deste repositório.
2. Abra o arquivo diretamente em qualquer navegador do seu computador ou celular.
3. Se preferir, ele também está hospedado e pronto para uso no **GitHub Pages** deste repositório.

---

## 🤝 Filosofia de Desenvolvimento & Acessibilidade

Este software foi construído seguindo rigorosos padrões de acessibilidade web. Elementos semânticos, gerenciamento de foco nativo e marcações de acessibilidade dinâmica (`aria-live` para anúncios textuais imediatos) garantem que usuários ceguinhos ou com baixa visão que utilizam leitores de tela tenham uma experiência fluida, estável e independente, longe do capacitismo estrutural presente em grandes ferramentas de mercado.

---

## 📬 Contato e Feedback

Gostou do projeto, encontrou algum bug ou quer sugerir uma melhoria? Esse projeto faz parte do meu portfólio de soluções independentes e eu adoraria ouvir sua opinião!

* **E-mail:** [euconcego@gmail.com](mailto:euconcego@gmail.com)

---

Desenvolvido com 💻 por **Anderson Carvalho**
