# MIND — O Desafio da Inteligência Artificial

Projeto final da disciplina de Introdução a Algoritmos/Programação, desenvolvido com Python e Pygame.

MIND é um jogo educativo que aborda a Inteligência Artificial no cotidiano, apresentando desafios sobre tecnologia, privacidade, segurança digital e uso responsável da IA.

## Integrantes do grupo

- Pedro Henrique Rocha de Souza
- Crystian Marcondes Oliveira Nascimento

## Estrutura do projeto

- `main.py`: ponto de entrada da aplicação.
- `src/`: código-fonte principal do jogo.
- `assets/`: imagens, fontes e sons.
- `data/`: arquivos persistentes, como recordes.
- `tests/`: testes unitários com pytest.
- `docs/`: documentação do projeto e proposta inicial.

## Descrição do jogo

MIND é um jogo de perguntas e respostas em que o jogador precisa enfrentar desafios relacionados à Inteligência Artificial.

Durante a partida, serão apresentadas situações inspiradas no cotidiano, envolvendo redes sociais, educação, segurança digital, privacidade e geração de conteúdo por IA.

O jogador deverá analisar cada situação e escolher a alternativa mais adequada. Após cada resposta, receberá uma explicação educativa sobre o assunto.

## Objetivo do jogador

Acertar o maior número possível de perguntas, acumular pontos e demonstrar conhecimento sobre o uso consciente e responsável da Inteligência Artificial.

## Regras do jogo

- O jogador começa na tela inicial.
- Cada rodada apresenta uma situação e três alternativas.
- Cada resposta correta aumenta a pontuação.
- Cada resposta incorreta reduz uma vida.
- O jogador começa com três vidas.
- Após cada resposta, uma explicação é apresentada.
- A partida termina quando todas as perguntas forem respondidas ou quando as vidas acabarem.
- Ao final, o jogo apresenta a pontuação conquistada.
- O recorde é armazenado localmente.

## Controles

- Mouse: selecionar alternativas e interagir com os botões.
- ENTER ou ESPAÇO: iniciar ou avançar.
- ESC: sair do jogo.

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone LINK_DO_REPOSITORIO
cd NOME_DA_PASTA
```

### 2. Criar o ambiente virtual

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Executar o jogo

```bash
python main.py
```

## Como executar os testes

```bash
python -m pytest -v
```

## Checklist para entrega

- [x] Definição do nome do jogo.
- [x] Definição dos integrantes.
- [x] Descrição da proposta.
- [x] Definição do objetivo e das regras.
- [x] Documentação dos controles.
- [ ] Atualizar `docs/proposta.md`.
- [ ] Integrar o projeto ao template oficial da disciplina.
- [ ] Testar a execução do jogo.
- [ ] Executar os testes automatizados.
- [ ] Revisar a documentação final.

## Observações

O projeto tem como objetivo estimular o pensamento crítico sobre a Inteligência Artificial, mostrando suas aplicações, limitações e a importância de utilizá-la com responsabilidade.

O código será organizado em módulos, separando a interface, as regras, as perguntas, a pontuação e o armazenamento de dados.
