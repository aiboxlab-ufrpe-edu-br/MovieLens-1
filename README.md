# MovieLens

Projeto 01 da disciplina CPS833 do PESC da Coppe. O objetivo do projeto é achar regras associativas na base do projeto [Movie Lens](https://movielens.org/) que faz sugestões de de filmes aos seus usuários a partir de filmees por eles já vistos.

<!-- ## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. -->

### Prerequisites

Neste projeto utilizei bibliotecas em Python para fazer a exploração e limpeza dos dados. o arquivo [proj-environment.yml](./proj-environment.yml) tem a definição de um ambiente Anaconda utilizado no projeto. 

### Installing

#### Setup do ambiente utilizando Anaconda

No **Anaconda Prompt** na raiz do projeto

```bash
REM create conda environment from Yaml file
conda env create -f proj-environment.yml

REM activate environment
conda activate movielens_env
```

#### Download dos dados

Por hora manual. No futuro podemos adicionar um script para fazer o dowload.

#### Rodando os códigos

Para rodar os notebooks jupyter (.ipynb)

```bash
jupyter lab
```

Para rodar os ().py)

```bash
python
```

### Sobre a Estrutura do Projeto

O projeto segue a ideia, na medida do possível do procesos MicrosoftTDSP para projetos de ciencia de dados. As pastas do projeto seguem as fases do projeto

* DataUnderstanding - visualização e limpeza de dados
* Modeling - Aplicaçãpo de ML
* RawData - local para os dados originais, não versionados para diminuir o peso do repositório.

## Authors

* **Thiago S.**

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

Meu desejp é que possa servir a outros. Aproveite.

[LICENSE.md](LICENSE.md) file for details

<!-- ## Acknowledgments -->