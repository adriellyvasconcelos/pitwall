# pitwall
🏁 PitWall — GP de São Paulo 2026
Projeto desenvolvido na disciplina de Linguagem de Marcação (LIMA), do Curso Técnico em Desenvolvimento de Sistemas — SENAI, com o objetivo de reproduzir, utilizando apenas HTML5 e CSS3, uma página inspirada no Grande Prêmio de São Paulo de Fórmula 1, em Interlagos.

A atividade foi realizada com base no layout de referência e nas orientações do Desafio Pit Wall.
🖥️ Sobre o projeto
O PitWall é uma página estática com visual inspirado em transmissões de automobilismo. O site apresenta informações ilustrativas sobre o GP de São Paulo, pilotos e equipes, uma tabela de classificação e uma área de ingressos.

O layout foi construído para se adaptar a telas de computador, tablet e celular.
✨ Funcionalidades visuais
- Cabeçalho: logotipo PitWall, menu de navegação e botão de ingresso.
- Destaque principal (hero): título do GP, imagem de carro de Fórmula 1, faixa diagonal vermelha e informações da pista.
- Grid de pilotos: cards com números, nomes, equipes e cores características.
- Classificação: tabela com posições, pilotos, equipes, vitórias, diferenças e pontos.
- Filtros visuais: campo de busca, seleção de equipe e botão para filtrar.
- Ingressos: informações de setores e formulário com dados pessoais, data, quantidade de ingressos, perfil, foto e recado.
- Rodapé: créditos do projeto e identificação do autor.
Atenção: os dados de classificação, preços e disponibilidade são ilustrativos. O formulário e os filtros são demonstrativos, pois a atividade utiliza somente HTML e CSS, sem JavaScript ou backend.

🛠️ Tecnologias utilizadas
- HTML5: estrutura e elementos semânticos da página.
- CSS3: estilos, animações de hover, posicionamento e responsividade.
- Google Fonts: fonte Titillium Web.
Conceitos praticados
- Variáveis CSS com :root e var();
- Flexbox para o cabeçalho, o destaque principal e os filtros;
- CSS Grid com repeat(auto-fit, minmax(...)) para os cards;
- Formulário com .form-grid e campos que ocupam duas colunas;
- Tabela HTML com <thead> e <tbody>;
- Imagem de fundo, gradientes e faixa diagonal;
- Faixa de zebra com repeating-linear-gradient();
- Estados :hover e transition;
- Media queries com @media para telas menores.
📁 Estrutura de arquivos
pit-wall/
├── index.html       # Estrutura do site
├── styles.css       # Estilos e responsividade
├── README.md        # Documentação do projeto
└── img/
    └── piloto.jpg   # Imagem utilizada no destaque principal
🚀 Como executar
1. Baixe ou clone este repositório.
2. Abra a pasta pit-wall.
3. Abra o arquivo index.html no navegador.
4. Para editar, abra a pasta no Visual Studio Code.
Não é necessário instalar dependências. A conexão com a internet é usada para carregar a fonte do Google Fonts; se ela não estiver disponível, o CSS utiliza uma fonte alternativa.
📱 Responsividade
O projeto utiliza regras @media para adaptar o menu, o destaque, os cards, a classificação e o formulário a diferentes larguras de tela. Em dispositivos pequenos, a tabela pode ser rolada horizontalmente.
🎓 Informações acadêmicas
Instituição: SENAI
Curso: Técnico em Desenvolvimento de Sistemas
Disciplina: Linguagem de Marcação (LIMA)
Atividade: Desafio Pit Wall
Professores: André Denani e Raul Lopes
Ano: 2026
👨‍💻 Autor
Adrielly Vasconcelos de souza
Projeto acadêmico para prática de HTML e CSS. Não é um site oficial da Fórmula 1 ou do GP de São Paulo.
