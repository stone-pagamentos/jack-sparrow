# Contribui��o

## Workflow de contribui��o

O padr�o de contribui��o conhecido como _gitflow_. Em algums momentos _pull requests_ s�o mandatorios, abaixo o fluxo detalhado:

![Gitflow modificado](image_02.png)

## Padr�o de mensagem de commit

- Usar modo imperativo ("Adiciona feature" n�o "Adicionando feature" ou "Adicionada feature")
- Primeira linha deve ter no m�ximo 72 caracteres
- Considere descrever com detalhes no corpo do commit
- Considere usar um emoji no in�cio da mensagem de commit

Emoji | Code | Commit Type
------------ | ------------- | -------------
:tada: | `:tada:` | commit inical
:art: | `:art:` | quando melhorar a estrutura/formato do c�digo
:racehorse: | `:racehorse:` | quando melhorar a performance
:memo: | `:memo:` | quando escrever alguma documenta��o
:bug: | `:bug:` | quando corrigir um bug
:fire: | `:fire:` | quando remover c�digos ou arquivos
:green_heart: | `:green_heart:` | quando corrigir uma build no CI
:white_check_mark: | `:white_check_mark:` | quando adicionar testes
:lock: | `:lock:` | quando melhorar a seguran�a
:arrow_up: | `:arrow_up:` | quando der upgrade em depend�ncias
:arrow_down: | `:arrow_down:` | quando der downgrade em depend�ncias
:poop: | `:poop:` | obsoleto
:construction: | `:construction:` | em constru��o
:rocket: | `:rocket:` | nova funcionalidade
:see_no_evil: | `:see_no_evil:` | gambiarra
:gift: | `:gift:` | nova vers�o
:lipstick: | `:lipstick:` | quando modifica a interface gr�fica
:wrench: | `:wrench:` | quando modifica arquivo de configura��o

### Exemplo
```bash
git commit -m ":memo: Adiciona instru��es de contribui��o.
>
> Foi criado o arquivo CONTRIBUTING.md com as instru��es de
> como fazer um bom commit"
``` 