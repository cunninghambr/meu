SEMPRE FAÇA BACKUP Antes!:

--------------

Esta versão necessita da Versão 20 do Node.

Atualize Rodando este comando:

curl -sL https://deb.nodesource.com/setup_20.x | bash -

apt install -y nodejs

--------------

Depois só trocar os arquivos do Back e Front, recompilar normalmente.

--------------

Se sua versão foi antiga rode esses comandos no BACKEND, lembre-se de reiniciar pm2 depois.

npx sequelize db:migrate
npx sequelize db:seed:all

--------------
