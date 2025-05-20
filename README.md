# fastapi-do-zero-exercicios

Implementação do [curso de FastAPI](https://fastapidozero.dunossauro.com/estavel/) do [Eduardo Mendes](https://github.com/dunossauro/fastapi-do-zero) do canal [Live de Python](https://www.youtube.com/@Dunossauro) e os **exercícios propostos**.

Playlist completa

<a href="https://www.youtube.com/watch?v=ImhYlISeWPQ&list=PLOQgLBuj2-3KT9ZWvPmaGFQ0KjIez0403">
    <img src="img/youtube.png">
</a>



## Descrição do Projeto

Este projeto contém implementações e exercícios do [curso de FastAPI](https://fastapidozero.dunossauro.com/estavel/) ministrado por [Eduardo Mendes](https://github.com/dunossauro/fastapi-do-zero) do canal [Live de Python](https://www.youtube.com/@Dunossauro). O objetivo é praticar os conceitos aprendidos no curso e construir APIs robustas utilizando [FastAPI](https://fastapi.tiangolo.com/).

## Estrutura do Projeto

O repositório está organizado da seguinte maneira:

TODO

## Requisitos

Para executar este projeto, você precisará ter instalado:

- Python 3.13+
- [Poetry](https://python-poetry.org/) (gerenciador de pacotes do Python)

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/rg3915/fastapi-do-zero-exercicios.git
cd fastapi-do-zero-exercicios/fast_zero
```

2. Instale o pipx

Caso já tenha feito isso antes, então pule para a etapa 5.

```bash
pip install --user pipx
pipx ensurepath
```

3. Instale o poetry

Caso já tenha feito isso antes, então pule para a etapa 5.

```bash
pipx install poetry
pipx inject poetry poetry-plugin-shell
```

4. Instalando uma versão do Python

Caso já tenha feito isso antes, então pule para a etapa 5.

```bash
poetry python install 3.13.3
```

5. Instale as dependências:

```bash
poetry install --no-root
```

## Uso

Para iniciar o servidor FastAPI, execute:

```bash
fastapi dev fast_zero/app.py
```

A aplicação estará disponível em `http://127.0.0.1:8000`.


## Passo a passo de como começar um projeto do zero

```bash
poetry new --flat fast_zero
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

[SQLAlchemy: conceitos básicos, uma introdução a versão 2 | Live de Python #258](https://www.youtube.com/watch?v=t4C1c62Z4Ag)

[Migrações, bancos de dados evolutivos (Alembic e SQLAlchemy) | Live de Python #211](https://www.youtube.com/watch?v=yQtqkq9UkDA)




## Agradecimentos

- [Eduardo Mendes](https://github.com/dunossauro/fastapi-do-zero), pelo excelente [curso de FastAPI](https://fastapidozero.dunossauro.com/estavel/).
- Comunidade [FastAPI](https://fastapi.tiangolo.com/), pelas contribuições e suporte.
