Sin City Website
Bem-vindo ao repositório do site Sin City, um projeto web que apresenta conteúdo relacionado às histórias em quadrinhos e adaptações de Sin City. Este site utiliza HTML, SCSS, JavaScript e ferramentas de automação como Gulp para criar uma experiência visualmente rica e responsiva.
Sobre o Projeto
O site promove os quadrinhos de Sin City, incluindo informações sobre volumes adaptados e não adaptados, bem como detalhes sobre o universo da série. Ele é projetado para ser acessível em múltiplos dispositivos (celular, computador, TV, videogames) e inclui recursos como:

Seção de herói com imagens promocionais
Galeria de quadrinhos com thumbnails
Informações sobre dispositivos compatíveis
Estilização moderna com fontes personalizadas (Avenir) e ícones SVG

Estrutura do Projeto
Abaixo está a estrutura de diretórios do projeto:
├── dist/                   
│   ├── css/                
│   ├── imagens/             
│   │   ├── dispositivos/    
│   │   └── icones/          
│   └── js/                  
├── node_modules/            
├── src/                   
│   ├── fonts/              
│   ├── images/             
│   │   ├── dispositivos/    
│   │   └── icones/         
│   ├── scripts/            
│   └── styles/             
├── .gitignore              
├── gulpfile.js              
├── index.html              
├── package.json            
└── package-lock.json        
               

Pré-requisitos
Para executar o projeto localmente, você precisa ter instalado:

Node.js (versão 14 ou superior recomendada)
npm (gerenciador de pacotes do Node.js)
Gulp CLI (npm install -g gulp-cli)

Instalação

Clone o repositório:
git clone https://github.com/seu-usuario/sincity.git
cd sincity


Instale as dependências:
npm install


Execute o build para compilar os arquivos:
gulp

Isso gerará a pasta dist/ com os arquivos prontos para produção.

Para desenvolvimento com live reload, use:
gulp watch



Scripts Disponíveis
No arquivo package.json, você encontrará os seguintes scripts:

npm run build: Executa o Gulp para compilar os arquivos
npm run watch: Inicia o modo de desenvolvimento com live reload

Estrutura dos Arquivos SCSS
Os arquivos SCSS estão organizados em módulos para facilitar a manutenção:

_variaveis.scss: Definições de cores, tamanhos, etc.
_header.scss, _hero.scss, _hqs.scss, _shows.scss, _descricao.scss, _avaliable-devices.scss, _faq.scss, _footer.scss: Estilos para seções específicas
main.scss: Arquivo principal que importa todos os módulos

Tecnologias Utilizadas

HTML5: Estrutura do site
SCSS: Estilização com suporte a variáveis e modularização
JavaScript: Interatividade no frontend
Gulp: Automação de tarefas (minificação, compilação, etc.)
Node.js: Gerenciamento de dependências
Fontes: Avenir (Bold e Regular)
Imagens: PNGs otimizados e ícones SVG

Contribuição

Faça um fork do repositório
Crie uma branch para sua feature (git checkout -b feature/nova-feature)
Commit suas alterações (git commit -m 'Adiciona nova feature')
Push para a branch (git push origin feature/nova-feature)
Abra um Pull Request

Licença
Este projeto está licenciado sob a MIT License.
Contato
Para dúvidas ou sugestões, entre em contato via email@example.com.
