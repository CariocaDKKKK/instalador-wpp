# instalador-wpp

```markdown

## Atualização do Servidor

```bash
apt update
apt upgrade
```

## AAPANEL

```bash
wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh aapanel
```

## Instalador (atualizado)

```bash
git clone https://github.com/CariocaDKKKK/instalador-wpp.git
```

## Permissão root

```bash
chmod -R 777 instalador-wpp
```

## Código-fonte (atualizado)

[https://github.com/CariocaDKKKK/wppmulti-project.git](https://github.com/CariocaDKKKK/wppmulti-project.git)

## Comandos extras após instalação

```bash
npx sequelize db:migrate
su deploy
pm2 restart all
```
```

Se precisar de mais alguma coisa, é só avisar! 😊
