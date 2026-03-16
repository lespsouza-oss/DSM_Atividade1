Atividade 1 - App Web com Express

Tema
Desenvolvimento de uma Aplicação Web utilizando Node.js e Express para servir páginas HTML estáticas.
Requisitos de Avaliação
• Valor: 0,25 pontos na média final da disciplina.
• Forma de entrega: atividade individual. O estudante deverá apresentar a aplicação em funcionamento,
publicada em um serviço de hospedagem em nuvem (por exemplo, Render ou outro serviço equivalente).
• Data de entrega: 20/03/2026.
Objetivos:
• Desenvolver um servidor web utilizando Node.js e o framework Express.
• Criar páginas HTML estruturadas com layout baseado em Flexbox.
• Configurar rotas no servidor Express para servir páginas HTML estáticas.
• Compreender a organização básica de um projeto web com separação entre backend e arquivos estáticos.
Material de Apoio
A explicação sobre a construção da aplicação e o processo de deploy pode ser encontrada nos seguintes vídeos:
• Criação do servidor: https://youtu.be/IicYmh146EA
• Construção da página index: https://youtu.be/4CToPSy7oxc
• Construção das páginas de login, cadastro e Not Found: https://youtu.be/qgmD864STCQ
• Deploy da aplicação no Render: https://youtu.be/EwPElQ9xwmw
Requisitos da Aplicação
Cada aluno deverá desenvolver uma aplicação web utilizando Node.js e Express, capaz de servir páginas HTML
estáticas. A aplicação deverá atender aos seguintes requisitos.
1. Servidor
• O projeto deve utilizar Node.js com o framework Express.
• O servidor deve ser iniciado a partir de um arquivo server.js.
• A porta do servidor deve ser configurada utilizando uma variável de ambiente definida no arquivo .env.
2. Estrutura do Projeto
O projeto deve possuir uma organização de pastas semelhante à seguinte estrutura:
app/
|- server.js
|- package.json
|- .env
|- public/
Atividade 1 - App Web com Express
Desenvolvimento Web I – Prof. Arley
2
| |- assets/
| | |- css/
| | |- img/
| |- pages/
| |- index.html
| |- login.html
| |- cadastro.html
| |- 404.html
A separação entre código do servidor, arquivos estáticos e páginas HTML deve ser respeitada.
3. Páginas da Aplicação
A aplicação deve possuir pelo menos as seguintes páginas HTML:
• Página inicial (index.html)
• Página de login (login.html)
• Página de cadastro (cadastro.html)
• Página de erro 404 (404.html)
As páginas devem possuir estrutura visual básica utilizando CSS e layout com Flexbox.
4. Rotas
O servidor Express deve possuir rotas que retornem as páginas correspondentes:
• / → página inicial
• /login → página de login
• /cadastro → página de cadastro
Qualquer rota inexistente deve redirecionar para a página 404.
5. Arquivos Estáticos
• O servidor deve disponibilizar uma pasta de arquivos estáticos.
• O projeto deve possuir pelo menos um arquivo CSS utilizado pelas páginas.
• Imagens podem ser adicionadas para compor a interface.
6. Deploy
A aplicação deve ser publicada em um serviço de hospedagem na nuvem, como por exemplo:
• Render
• ou outro serviço equivalente.
No momento da entrega, o aluno deverá apresentar a aplicação em funcionamento utilizando o link público do
deploy.
Texto da página index.html
<p>
O curso de DSM tem como objetivo preparar o estudante
para atuar no desenvolvimento de sistemas e aplicações que funcionem
Atividade 1 - App Web com Express
Desenvolvimento Web I – Prof. Arley
