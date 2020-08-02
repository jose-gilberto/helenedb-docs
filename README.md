# Primeiros Passos

> O HeleneDB é um sistema de gerenciamento de banco de dados assíncrono que implementa os conceitos básicos de um SGBD. Sua implementação foi realizada para estudos e não para uso em produção.

## Sobre

O HeleneDB foi feito para auxiliar no ensino e estudo sobre sistemas de gerenciamento de banco de dados, disponibilizando uma GUI para facilitar o entendimento dos procedimentos internos de um SGBD.

Todos os algoritmos implementados são somente para estudos, não aconselhamos seu uso em produção. Todas as especificações podem ser encontradas em sua documentação, bem como demais detalhes.

## Instalando o Projeto

No momento o projeto só pode ser executado em modo de desenvolvimento, posteriormente será incluida uma seção para a execução do SGBD em produção (nome dado apenas para diferencias os modos de execução, ressaltamos que não deve ser utilizado em ambientes produção real).

### Pré requisitos

- Git
- Nodejs
- Npm

#### Clonando o Projeto

Para clonar o projeto basta executar:

```shell
git clone https://github.com/jose-gilberto/helenedb.git
```

Logo após o download do projeto basta entrar no diretório do projeto:

```shell
cd helenedb
```

Instalar as dependências:

```shell
npm install
```

E executar qualquer comando do npm listado no `package.json` ou na documentação.

## Modos de Execução

### Linha de Comando

O HeleneDB pode ser executado por linha de comando chamando o console a partir do npm:

```shell
npm run console
```

A saída obtida será algo do tipo:
```
helenedb> 
```
A partir daí podemos utilizar de queries normalmente, ou dos comandos de console para o interpretador, sendo estes listados posteriormente.

### Arquivos

### GUI
