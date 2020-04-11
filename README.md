# POO

Esse é o projeto da última unidade da disciplina de Progração orientada a objetos que fizemos em aproximadamente 2 semanas, sem conhecimento algum do Django. Trata-se de uma tentativa de fazer um mensageiro. Ainda que não muito funcional e com muitos bugs, foi essencial para o meu aprendizado com o framework Django, e o uso da linguagem Python.

## Começando

Essas instruções farão com que você consiga ter uma cópia funcional desse projeto na sua máquina, para ver como ele funciona.

### Pre-requisitos

O que você precisará para fazer o servidor local funcionar

```
[Python](https://www.python.org/) - Linguagem de programação
```

### Instalando

Primeiro, baixe o [Python](https://www.python.org/) do seu site oficial e instale-o em sua máquina (SELECIONE A CAIXA "ADD TO PATH" NO COMEÇO DA INSTALAÇÃO, CASO CONTRÁRIO NÃO FUNCIONARÁ).

Após a instalaçao do python, você terá acesso ao comando "pip" no cmd, utilize ele para instalar a aplicação de criação de maquinas virtuais (é importante para que você organize o funcionamento do programa e não misture com o resto do seu computador)

```
pip install virtualenv
```

Agora, extraia os arquivos desse projeto em alguma pasta de sua preferencia e, nessa pasta raiz inicie o cmd digitando cmd na caixa de local da pasta e pressionando ENTER.
Crie e ative um ambiente virtual.

```
virtualenv env
cd env/Scripts
activate
cd ../../POO
#navegando até a pasta do projeto(pode ser diferente no seu computador, se você tiver colocado as pastas em lugares diferentes)
```

Instale as bibliotecas necessárias

```
pip install django
pip install django-bootstrap-form
pip install Pillow
```

Em seguida inicie o servidor com:

```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

E acesse o site em algum navegador pelo ip/porta/login/

## O site

Você pode criar uma conta e logar nela para ver a tela de inicio, com todos os seus contatos e conversas.
Contudo, de forma bem triste, você pode adicionar como amigo qualquer pessoa no servidor(sem o consentimento dela). Além disso, você não consegue enviar a mesma mensagem duas vezes (tentei corrigir isso nas últimas horas da entrega do projeto, mas sem sucesso).

## Feito com

* [Python](https://www.python.org/) - Linguagem de programação
* [Django](https://www.djangoproject.com/) - O framework Web
* [Bootstrap](https://getbootstrap.com/) - Toolkit para CSS, HTML e JS

## Autores

* **João Pedro Betanza** - *Trabalho conjunto* - [jpbetanza](https://github.com/jpbetanza)
* **Gabriel Vinicius** - *Trabalho conjunto* - [Gabrielvss](https://github.com/Gabrielvss)
