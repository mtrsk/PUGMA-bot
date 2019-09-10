# PUGMA bot

[![Build Status](https://travis-ci.org/pug-ma/PUGMA-bot.svg?branch=master)](https://travis-ci.org/pug-ma/PUGMA-bot)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/07e9dfb47a564ffa8395b83d3d44658f)](https://www.codacy.com/manual/mtrsk/PUGMA-bot?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pug-ma/PUGMA-bot&amp;utm_campaign=Badge_Grade)
[![GitHub contributors](https://img.shields.io/github/contributors/pug-ma/PUGMA-bot)](https://github.com/pug-ma/PUGMA-bot/graphs/contributors)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

Um bot para o Python User Group - MA.

Pull requests são sempre bem vindos na Branch `dev`.

## Contribuindo

Antes the utilizar esse bot é necessário que você possua seu próprio ID e HASH no Telegram, adicionalmente é necessário possuir um `TOKEN` para usar a api de bots. Você pode conseguí-los seguindo estes passos:

  1. Faça seu login com sua conta no Telegram [neste endereço](https://my.telegram.org/).
  2. Clique em **API Development tools**.
  3. Cria uma nova aplicação, não é necessário fornecer todos os detalhes (como `URL`), apenas `APP title` e `Short Name`.
  4. Clique em **Create Application** e você obterá seu HASH e ID. Evite postar esses dados publicamente.
  5. Use o `Botfather` para conseguir um `TOKEN` pro seu bot.
  6. Rode o script `string_session.py` e coloque o `TOKEN` do seu bot quando for pedido.
  7. Copie o `.env.sample` como `.env` e preencha com seus dados:
  ```sh
    $ cp .env.sample .env
  ```

## Rodando

  * Docker
  ```sh
  $ docker-compose up
  ```

  * Nix
  ```sh
  $ nix-shell
  ```

  * Python
  ```sh
  $ python app.py
  ```
