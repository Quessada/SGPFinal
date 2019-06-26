# SGPFinal
Pré-requisitos para a instalação deste projeto


<ul>
  <li>Servidor Apache ou Nginx em suas versões mais recentes;</li>
  <li>PHP versão 7.*;</li>
  <li>MySQL versão 5,7;</li>
  <li>Composer versão mais recente;</li>
  <li>Git versão mais recente.</li>
</ul>

Passo a passo para instalação deste projeto.

<ol>
  <li>Clone o repositório em um ambiente com Apache|Nginx/PHP/MySQL/Composer;</li>
  <li>No diretório raiz do projeto, digite o comando no terminal: composer-install</li>
  <li>Digite o comando: cp .env.example .env</li>
  <li>Digite o comando: php artisan key:generate</li>
  <li>Altere as conexões de banco de dados no arquivo .env</li>
  <li>Crie um banco de dados para o projeto com a collection utf8mb4_unicode_ci</li>
  <li>Digite o comando: php artisan migrate --seed</li>
  <li>Digite o comando: php artisan serve</li>
</ol>

Após isso, o projeto estará roando no seu servidor local na porta 8000 http://localhost:8000/
