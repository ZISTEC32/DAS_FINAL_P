# Página Colaborativa de Receitas

## Objetivo

Este projeto foi desenvolvido para a disciplina de **Desenvolvimento de Aplicações e Sistemas (DAS)** e tem como objetivo criar uma página colaborativa de receitas, utilizando Git e GitHub para praticar trabalho em equipa, gestão de branches, commits, Issues e Pull Requests.

## Disciplina

Desenvolvimento de Aplicações e Sistemas (DAS)

## Participantes

- Paulo Veiga
- Emilio Manuel
- Zawany BumBa

## Lista de Receitas

- Receita Tradicional
- Receita Vegetariana
- Receita Vegana

## Como clonar o projeto

```bash
git clone https://github.com/ZISTEC32/DAS_FINAL_P.git
cd DAS_FINAL_P
```

## Como trabalhar numa branch

```bash
git fetch origin
git switch nome-da-branch
git pull origin nome-da-branch
```

Depois de realizar as alterações:

```bash
git add .
git commit -m "Descrição das alterações"
git push origin nome-da-branch
```

## Como criar um Pull Request

1. Fazer push da branch para o GitHub.
2. Abrir o repositório no GitHub.
3. Selecionar **Compare & pull request**.
4. Confirmar que o destino é a branch `main`.
5. Adicionar um título e uma descrição.
6. Referenciar a Issue correspondente utilizando:

```
Closes #NÚMERO_DA_ISSUE
```

7. Criar o Pull Request.

## Fluxo de contribuição

1. Criar ou mudar para a branch atribuída.
2. Atualizar a branch com `git pull`.
3. Fazer as alterações necessárias.
4. Criar commits com mensagens descritivas.
5. Enviar a branch para o GitHub com `git push`.
6. Criar um Pull Request para a branch `main`.
7. Associar o Pull Request à respetiva Issue utilizando:

```
Closes #NÚMERO_DA_ISSUE
```

8. Aguardar a revisão de outro elemento da equipa antes do merge.

## Relatório

Após a conclusão do projeto, preencher o ficheiro:

`docs/relatorio.md`