# curso-django-pythonpro

[![Build Status](https://travis-ci.com/lipegomes/curso-django.svg?branch=main)](https://travis-ci.com/lipegomes/curso-django)
[![Updates](https://pyup.io/repos/github/lipegomes/curso-django/shield.svg)](https://pyup.io/repos/github/lipegomes/curso-django/)
[![Python 3](https://pyup.io/repos/github/lipegomes/curso-django//python-3-shield.svg)](https://pyup.io/repos/github/lipegomes/curso-django/)
[![codecov](https://codecov.io/gh/lipegomes/curso-django/branch/main/graph/badge.svg?token=CBWMUTYMRY)](https://codecov.io/gh/lipegomes/curso-django)

Código desenvolvido durante o módulo de Django do Bootcamp DevPro.

Abordado a  construção de projetos utilizando o Framework Django para python no back-end e front-end.

## Aplicação disponível em:
https://pythonprodjangofgomes.herokuapp.com/

## Requerimentos:
- Ter a versão 3.xx do python instalada no notebook ou pc.
- Ter o pipenv instalado.
```console
pip install pipenv
```
- Criar o ambiente virtual na pasta do projeto e instalar os requirements:
  
  Criar o .venv, instalar as dependências e ativar o shell do ambiente virtual:
    ```console
    pipenv sync
    pipenv shell
    ```
    Instalar somente as dependências de desenvolvimento:
    ```console
    pipenv sync -d
    ```
## Verificar qualidade de código:
```console
flake8
```

## Ferramentas utilizadas:

Ambiente virtual:
1. [Pipenv](https://pipenv.pypa.io/en/latest/)

Frameworks:
1. [Django](https://www.djangoproject.com/)
2. [Bootstrap](https://getbootstrap.com/)

Deploy:
1. [Git](https://git-scm.com/)
2. [Travis CLI](https://www.travis-ci.com/)
3. [Heroku](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)
4. [AWS](https://aws.amazon.com/)
5. [django-s3-folder-storage](https://github.com/jamstooks/django-s3-folder-storage)
6. [Collectfast](https://github.com/antonagestam/collectfast)

Testes e qualidade do código:
1. [PyTest](https://docs.pytest.org/en/stable/)
2. [PyTest-Cov](https://pytest-cov.readthedocs.io/en/latest/readme.html#installation)
3. [Pytest-Mock](https://github.com/pytest-dev/pytest-mock/)
4. [Pytest-Django](https://pytest-django.readthedocs.io/en/latest/index.html)
5. [Django-Debug-Toolbar](https://django-debug-toolbar.readthedocs.io/en/latest/)

Gestão da atualização de dependências:
1. [PyUp](https://pyup.io/)

Monitoramento de erros:
1. [Sentry](https://sentry.io/)

## Licença

Este projeto é licenciado sobre a licença MIT - veja [LICENSE](https://github.com/lipegomes/curso-django/blob/main/LICENSE) para mais informações.

## Acknowledgments

- Renzo Nuccitelli [LinkedIn](https://www.linkedin.com/in/renzonuccitelli/)

- Este módulo foi construído durante o Bootcamp DevPro do [PythonPro](https://www.python.pro.br/).