🕹️ Fliperama 98

"Onde a nostalgia encontra a tecnologia. Jogos clássicos direto no seu navegador."

📖 Sobre o Projeto

O Fliperama 98 é uma aplicação web desenvolvida para simular a experiência de uma máquina de arcade dos anos 90. O objetivo é oferecer uma plataforma leve, rápida e acessível onde usuários podem jogar clássicos recriados pela comunidade sem a necessidade de downloads ou instalações complexas.

O design foi inspirado na estética Neo Geo / The King of Fighters, utilizando cores neon, fundo escuro e tipografia retrô.

🚀 Funcionalidades

Design Responsivo: Funciona perfeitamente em computadores e dispositivos móveis.

Tema Arcade: Interface visual imersiva com estilo "Dark Mode" e efeitos neon.

Carregamento Modular: O menu de navegação é carregado dinamicamente via JavaScript (fetch), facilitando a manutenção.

Integração de Jogos: Suporte para jogos via iframe (Modais) e links diretos para tela cheia.

🎮 Lista de Jogos

Atualmente, o projeto conta com os seguintes títulos:

🍄 Mario vs Luigi: Um remake multiplayer caótico do clássico da Nintendo.

🥊 The King of Fighters: Clone web do lendário jogo de luta (KOF 98 vibe).

🐦 Floppy Bird: Teste seus reflexos neste clone desafiador.

🧩 Hextris: Um quebra-cabeça de ritmo rápido inspirado no Tetris.

Em breve mais títulos!!

💻 Tecnologias Utilizadas

HTML5 Semântico: Estrutura das páginas.

CSS3 & Custom Properties: Estilização personalizada (efeitos de scanline, sombras neon).

Bootstrap 5.3: Framework para layout responsivo, cards e modais.

JavaScript (ES6+): Lógica de carregamento de componentes e interatividade.

⚙️ Como Rodar o Projeto

⚠️ Atenção Importante:
Como este projeto utiliza a API fetch() para carregar o menu (menu.html), ele não funcionará se você apenas clicar duas vezes no arquivo index.html (erro de política CORS).

Você precisa rodar o projeto em um Servidor Local. Escolha uma das opções abaixo:

Opção 1: VS Code (Recomendado)

Instale a extensão Live Server no Visual Studio Code.

Abra o arquivo index.html.

Clique com o botão direito e selecione "Open with Live Server".

Opção 2: Python

Se você tem Python instalado, abra o terminal na pasta do projeto e digite:

python -m http.server


Depois, acesse http://localhost:8000 no seu navegador.

📂 Estrutura de Arquivos

/
├── index.html      # Página Inicial (Vitrine de Jogos)
├── jogos.html      # Lista completa de jogos
├── about.html      # Sobre o projeto
├── contato.html    # Página de contato
├── menu.html       # Componente de menu (carregado via JS)
└── css/
    └── custom.css  # Estilos personalizados (Tema Arcade)


ou

Pode Acessar direto  Pelo Link https://fliperama98.netlify.app

👏 Créditos e Agradecimentos

Este projeto utiliza jogos open-source e gratuitos disponibilizados pela comunidade:

Mario vs Luigi por ipodtouch0218

KOF Web por Ritaa Zhang

📝 Licença

Este projeto é de código aberto e destinado a fins educacionais e de portfólio.

<p align="center">
Desenvolvido com 💜 e nostalgia.





<b>INSERT COIN TO CONTINUE</b>
</p>
