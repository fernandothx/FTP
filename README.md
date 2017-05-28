Online FTP / Amazon S3 Filebrowser

Status da compilação

Navegador de arquivos simples construído com Laravel e Vue.

Instalação

Clone este repositório para a sua máquina.
composer install
yarn or npm install
gulp or gulp --production

Certifique-se de restringir o tamanho máximo de upload em sua configuração php, bem como no arquivo .env.

Limpeza do sistema de arquivos

Configurar um cronjob para remover arquivos antigos de seu sistema de arquivos ou acioná-lo manualmente.

Php artisan onlineftp: limpeza
Consulte https://laravel.com/docs/5.3/scheduling#introduction sobre como configurar o agendador de tarefas cronjob.
