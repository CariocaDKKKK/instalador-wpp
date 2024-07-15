# instalador-wpp

```markdown
# Documento de Instalação

Siga as aulas para aprender a usar essa documentação, não pule nenhuma etapa. (Só use essa documentação seguindo as aulas)

**Atenção:** Esses links abaixo NÃO são clicáveis, eles são utilizados apenas durante o processo de instalação. O código fonte e instalador você encontra no módulo bônus para download.

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
