🎄 Maratona de Natal • O Chalé dos Filmes 🎬❄️

Pegue uma xícara de chocolate quente, vista seu suéter favorito e puxe uma cadeira perto da lareira! Este é o painel interativo oficial da nossa Maratona de Natal, um espacinho mágico construído para organizar, descobrir e acompanhar todos os filmes clássicos e aconchegantes que vão aquecer o nosso mês de dezembro.

✨ Acesse o Chalé e viva a magia: https://nossonatal.vercel.app ✨

🎅 O que é o projeto?

A Maratona de Natal é uma aplicação web imersiva nascida da vontade de transformar o ato de assistir filmes numa verdadeira tradição festiva.

Em vez de planilhas chatas ou listas perdidas no bloco de notas, criamos um "Chalé" digital. Com uma paleta de cores cozy winter (azul noite, verde pinheiro e vermelho festivo), o sistema permite cadastrar nossos filmes favoritos, dividi-los por semanas temáticas, marcar o que já foi assistido e acompanhar o progresso geral até o grande dia de Natal!

🎁 Funcionalidades Mágicas

🚪 Acesso ao Chalé (Segurança de Duende)

Lista Exclusiva: Autenticação segura via Firebase. Apenas convidados com nome de Elfo e a senha correta (Magia Protetora) podem entrar.

Validação de Magia: Indicadores visuais ajudam a criar uma senha forte na hora do cadastro (maiúsculas, minúsculas, símbolos e tamanho).

O Guardião da Porta: Se errar a senha... o Papai Noel aparece pessoalmente na tela para dizer um belo "HO HO NO!" e negar a entrada!

📜 A Grande Lista (Gestão de Filmes)

Atualização em Tempo Real: Adicionou ou editou um filme? O Firebase Firestore atualiza a lista de todos os duendes instantaneamente, sem precisar recarregar a página.

Upload Inteligente de Capas: Chega de baixar imagens! Basta copiar o pôster do filme na internet e dar um Ctrl + V direto no formulário. O sistema redimensiona e comprime a imagem automaticamente (usando Canvas) para economizar dados.

Onde Assistir? Etiquetas charmosas indicam exatamente onde o filme está disponível (Netflix 🔴, Max 🟣, Disney+ 🏰, Apple TV+ 🍎 ou nas águas do Torrent 🏴‍☠️).

❄️ Clima Festivo & Organização

Semanas Temáticas: Filmes divididos por categorias como Clássicos & Família ou Animações & Magia.

Progresso Visível: Uma barra mágica acompanha quantos filmes já vimos. Quando a maratona chega a 100%, prepare-se para uma chuva de confetes comemorativos! 🎉

Busca Rápida: Filtro instantâneo por nome do filme, gênero ou semana específica.

🛠️ Tecnologias que movem o Trenó

Este projeto foi construído "na unha" (Vanilla), focando em performance, estética e interatividade direta, sem depender de frameworks pesados:

Front-end: HTML5 Semântico, CSS3 (com CSS Grid, Flexbox, animações customizadas e backdrop-filter).

Lógica & Magia: JavaScript (ES6+), manipulando a DOM e a Clipboard API (para colar imagens).

Back-end & Banco de Dados: Firebase Authentication e Cloud Firestore.

Efeitos Visuais: Biblioteca canvas-confetti para celebrar nossas vitórias.

Hospedagem: Vercel (Rápido, seguro e online 24/7).

🦌 Como rodar na sua própria oficina?

Se você quiser clonar este projeto para fazer a sua própria maratona, é muito simples:

Clone o repositório:

   git clone https://github.com/thaistardys/nossonatal.git
   cd nossonatal


Crie um projeto no Firebase e ative o Authentication (E-mail/Senha) e o Firestore Database.

Pegue suas chaves de configuração do Firebase e substitua o objeto firebaseConfig no topo do arquivo script.js.

Abra o arquivo index.html em seu navegador ou use o Live Server do VS Code.

Crie sua conta na tela inicial e comece a adicionar seus filmes!

💌 Feito com carinho...

Desenvolvido entre xícaras de café e muita empolgação para tornar o mês de dezembro ainda mais inesquecível para mim e para a Vitoria.

Que a nossa maratona seja cheia de risadas, pipoca e espírito natalino! Feliz Natal! 🎄🍿
