<div align="center">
  <img src="images/Aesthetic%20Twitter%20Header.png" alt="UnBeatables Header" width="100%">
</div>

# UnBeatables 2025

Bem-vindo(a), integrante da equipe UnBeatables!

Este repositório contém todo o código de competição, simulação, infraestrutura e documentação desenvolvidos pela equipe. 

## Integrantes

### Professor
* Roberto Baptista

### Doutorando
* Gabriel Tambara

### Mestranda
* Fernanda Diniz

### Graduandos
* Clarisse Ribeiro
* Igor Terêncio
* Isabel Andrade
* Iuri Costa
* João Pedro Martins
* Mariana Reis
* Ryuji

## Estrutura do Repositório

Para facilitar a organização e transferência de conhecimento, centralizamos nossos projetos antigos na seguinte estrutura:

* **`docs/`**: Site de documentação da equipe (desenvolvido com Docsify). Contém guias de instalação, tutoriais e regras.
* **`images/`**: Imagens e banners utilizados na documentação e neste README.
* **`infra/`**: Ferramentas de infraestrutura e preparo de ambiente.
    * `docker/`: Ambientes em containers (ex: alvim-docker, dependências do NAOqi, Choregraphe, etc.).
    * `templates/`: Templates iniciais (como o template C++ do NAOqi configurado com CMake).
* **`src/`**: Onde o código-fonte principal de execução reside.
    * `competition/`: Código fonte V6 da competição (ação, comportamento, percepção, comunicação).
    * `tools/`: Ferramentas criadas pela equipe (ex: frednator).
* **`simulation/`**: Cenas e scripts para rodar o robô virtualmente usando o simulador (V-Rep / CoppeliaSim).