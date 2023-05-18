<h1>Conhecendo o Projeto Spring Data JPA na Prática </h1>

<p> Sejam bem-vindos ao projeto meu primeit <strong> Docker Composer</strong>.<br>

<h2>🎯 Objetivo do Projeto</h2>
<p>Construir um arquivo <strong>docker-composer.yml</strong> Para criar uma container com apache/php utilizando a imagem <strong>webdevops/php-apache:alpine-php7</strong> 
e enviar um arquivo <strong>index.php</strong> para pasta /app do container e o arquivo de configuracao uploads.ini
<h2>Conteúdo do projeto</h2>
<p>Docker e Docker Composer instalados</p>
</p>
<h2>Conteúdo do projeto</h2>
<p>Arquivos:</p>
<p>/compose/php-apache/docker-compose.yml  -  Arquivo de configuração</p>
<p>/data/php-d/index.php  -  Arquivo para apresentar as informações do servidor php</p>
<p>/data/php-d/admin/uploads.ini  -  Arquivo de configuraçao para aumentar o tamanho máximo de uploads</p>
</p>
<h2>Configurando e subindo seu docker-composer.yml</h2>
<p> - Copiar os arquivos docker-compose.yml,index.php e uploads.ini para os caminhos apresentados na sessão conteúdo do projeto </p>
<p> - Entrar na pasta /compose/php-apache</p>
<p> - Entrar na pasta executar o comando </strong>docker-compose up -d<strong></p>