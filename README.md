# fastapi-do-zero-exercicios

Implementação do [curso de FastAPI](https://fastapidozero.dunossauro.com/) do [Eduardo Mendes](https://github.com/dunossauro/fastapi-do-zero) do canal [Live de Python](https://www.youtube.com/@Dunossauro) e os **exercícios propostos**.

Playlist completa

<a href="https://youtube.com/playlist?list=PLOQgLBuj2-3IuFbt-wJw2p2NiV9WTRzIP&si=K_9UbtB-WKjSwYT6">
    <img src="img/youtube.png">
</a>



## Descrição do Projeto

Este projeto contém implementações e exercícios do [curso de FastAPI](https://fastapidozero.dunossauro.com/) ministrado por [Eduardo Mendes](https://github.com/dunossauro/fastapi-do-zero) do canal [Live de Python](https://www.youtube.com/@Dunossauro). O objetivo é praticar os conceitos aprendidos no curso e construir APIs robustas utilizando [FastAPI](https://fastapi.tiangolo.com/).

## Estrutura do Projeto

O repositório está organizado da seguinte maneira:

TODO

## Requisitos

Para executar este projeto, você precisará ter instalado:

- Python 3.11 ou superior
- [Poetry](https://python-poetry.org/) (gerenciador de pacotes do Python)

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/rg3915/fastapi-do-zero-exercicios.git
cd fastapi-do-zero-exercicios
```

2. Crie um ambiente virtual:

```bash
poetry shell
```

3. Instale as dependências:

```bash
poetry install
```

## Uso

Para iniciar o servidor FastAPI, execute:

```bash
uvicorn src.main:app --reload
```

A aplicação estará disponível em `http://127.0.0.1:8000`.


## Troubleshooting

### Erro na instalação do pyenv 3.12.4 no Linux.

```bash
regis@pop-os:~$ pyenv install 3.12:latest
Downloading Python-3.12.4.tar.xz...
-> https://www.python.org/ftp/python/3.12.4/Python-3.12.4.tar.xz
Installing Python-3.12.4...
Traceback (most recent call last):
  File "<string>", line 1, in <module>
  File "/home/regis/.pyenv/versions/3.12.4/lib/python3.12/tkinter/__init__.py", line 38, in <module>
    import _tkinter # If this fails your Python may not be configured for Tk
    ^^^^^^^^^^^^^^^
ModuleNotFoundError: No module named '_tkinter'
WARNING: The Python tkinter extension was not compiled and GUI subsystem has been detected. Missing the Tk toolkit?
Installed Python-3.12.4 to /home/regis/.pyenv/versions/3.12.4
```

**Solução:** https://github.com/pyenv/pyenv/wiki#suggested-build-environment


## Passo a passo de como começar um projeto do zero

```bash
poetry new fast_zero
cd fast_zero
```


### Rodando a aplicação

```bash
fastapi dev fast_zero/app.py
```

ou

```bash
uvicorn fast_zero.app:app
```

#### Email

Quando for rodar os testes com email vai precisar instalar o seguinte pacote:

```bash
poetry add "pydantic[email]"
```

#### Testando o schemas

Podemos testar o schemas rodando o shell iterativo

```bash
python -i fast_zero/schemas.py
```

E depois

```python
UserSchema(username='rg3915', email='rg3915@email.com', password='1234')
```

[SQLAlchemy: conceitos básicos, uma introdução a versão 2 | Live de Python #258](https://www.youtube.com/watch?v=t4C1c62Z4Ag)

[Migrações, bancos de dados evolutivos (Alembic e SQLAlchemy) | Live de Python #211](https://www.youtube.com/watch?v=yQtqkq9UkDA)




## Agradecimentos

- [Eduardo Mendes](https://github.com/dunossauro/fastapi-do-zero), pelo excelente [curso de FastAPI](https://fastapidozero.dunossauro.com/).
- Comunidade [FastAPI](https://fastapi.tiangolo.com/), pelas contribuições e suporte.

