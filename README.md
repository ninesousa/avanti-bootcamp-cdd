# < Data palmerpenguins >

<picture>
  <img src="https://github.com/allisonhorst/palmerpenguins/raw/main/man/figures/lter_penguins.png" 
       alt="Os Pinguins da pesquisa palmerpenguins" 
       width="600" 
       style="display: block; margin: auto;">
</picture>


## Analise e Predição de Dados

O pacote **palmerpenguins** oferece uma alternativa ao famoso conjunto de dados `iris` para exploração e visualização de dados, com informações sobre pinguins do Arquipélago Palmer, na Antártica.

Os dados foram coletados pela Dra. Kristen Gorman e pela Palmer Station, Antártica LTER, um membro da Long Term Ecological Research Network.

O pacote **palmerpenguins** contém dois conjuntos de dados:

- **penguins** - Uma versão simplificada dos dados originais.
- **penguins_raw** - O conjunto de dados completo com todas as variáveis originais.

Ambos os conjuntos contêm medições de 344 pinguins, pertencentes a três espécies, coletados em três ilhas diferentes no Arquipélago Palmer.

### Conjunto de Dados `penguins`

O conjunto `penguins` fornece 8 variáveis:

- **Espécie** (Adelie, Chinstrap, Gentoo)
- **Ilha** (Biscoe, Dream, Torgersen)
- **Comprimento do bico** (mm)
- **Profundidade do bico** (mm)
- **Comprimento da nadadeira** (mm)
- **Massa corporal** (g)
- **Sexo** (feminino/masculino)

## Metodologia

A metodologia que será adotada para a análise e predição de pinguins do Arquipélago Palmer, segue o ciclo CRISP-DM (Cross Industry Standard Process for Data Mining), um processo estruturado amplamente utilizado em projetos de mineração de dados e análise preditiva. O CRISP-DM é composto por:
1. Entendimento de negócio
2. Entendimento de dados
3. Preparação dos dados
4. Modelagem


## Resultados Esperados

Espero descrever algumas das principais variáveis dos pinguins e desenvolver um modelo preditivo com base nos dados fornecidos. O projeto incluirá a geração de gráficos, proporcionando uma visão mais clara das relações entre diferentes fatores.



### Requisitos

Para utilizar este template, você precisará de um ambiente com os seguintes softwares:
 - git
 - Python 3.8
 - Poetry `1.1.13` ou superior

É aconselhável o uso do `pyenv` para o gerenciamento de versões do Python.


### Contribuindo com um repositório já criado

Depois de criar o repositório, para começar a modificá-lo e/ou contribuir com repositórios já criados,  você precisa cloná-lo. Para isso, siga os seguintes passos:

1. Acima da lista de arquivos, clique no botão **Code** (em verde).
2. Copie a URL para o repositório.
    - Tente clonar utilizando uma chave **SSH**. Para isso, clique na aba **SSH** e em seguida clique no ícone de cópia.
3. Abra o terminal.
4. Altere o diretório de trabalho atual para o local que deseja ter o diretório clonado.
5. Digite `git clone` e cole a URL que você copiou anteriormente:
```
git clone git@github.com:NOME-DE-USUARIO/REPOSITORIO.git
```
6. Pressione **Enter** para criar seu clone local.

Proto, com isso você acaba de clonar um repositório. Para mais informações sobre a clonagem de arquivos, acesse a [documentação oficial](https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository).

Com o repositório clonado, você precisa navegar até a pasta local, usando o comando :
```
cd REPOSITORIO
```

Estando na pasta do repositório, basta instalar as dependências do projeto utilizando o comando:
```
poetry install
```

Ele irá instalar todas as dependências contidas no arquivo `pyproject.toml`. Depois disso basta ativar o ambiente virtual criado pelo Poetry utilizando o comando:
```
poetry shell
```