# Aula de Git 2

![Git](https://img.shields.io/badge/Git-pratica-F05032?style=for-the-badge&logo=git&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-pagina%20estatica-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-estilizacao-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Documentação](https://img.shields.io/badge/README-contexto%20tecnico-0A66C2?style=for-the-badge)

Repositório de prática complementar em Git, HTML e CSS. O objetivo é reforçar o fluxo de alteração incremental, organização de arquivos e manutenção de uma documentação clara desde os primeiros exercícios.

Esta versão também substitui anotações informais por uma apresentação profissional, porque um repositório público faz parte da comunicação técnica de quem o mantém. Mesmo em exercícios simples, clareza e tom importam.

## Objetivo do projeto

O projeto foi usado para praticar conceitos iniciais de versionamento e estrutura de arquivos. Ele trabalha um cenário pequeno, mas comum: ter múltiplos arquivos em um repositório e precisar controlar mudanças com Git.

Objetivos principais:

- reforçar comandos básicos de Git;
- organizar arquivos HTML, CSS e textos de apoio;
- publicar mudanças no GitHub;
- exercitar README como documentação viva;
- manter o repositório compreensível para revisão futura.

## O que este projeto demonstra

| Competência | Como aparece | Impacto técnico |
| --- | --- | --- |
| Controle de versão | Alterações registradas em um projeto simples | Permite acompanhar evolução do exercício |
| Base web | Estrutura mínima com `index.html` e `styles.css` | Ajuda a entender separação entre conteúdo e estilo |
| Organização | Arquivos de exemplo separados do código web | Facilita leitura e manutenção |
| Disciplina profissional | README com tom técnico e objetivo | Melhora a percepção pública do repositório |
| Aprendizado progressivo | Exercício pequeno tratado como parte de uma trilha maior | Mostra constância e evolução técnica |

## Estrutura do repositório

```text
.
├── exemplo.txt      # Arquivo auxiliar para prática
├── exemplo2.txt     # Segundo arquivo auxiliar
├── index.html       # Página HTML estática
├── readme.md        # Documentação do projeto
└── styles.css       # Arquivo de estilos
```

## Como visualizar

Clone o projeto:

```bash
git clone https://github.com/DouglasAntoni0/aula-de-git2.git
cd aula-de-git2
```

Abra `index.html` no navegador.

## Fluxo Git sugerido

Para praticar uma alteração completa:

```bash
git status
git add .
git commit -m "Atualiza pratica de git e html"
git push
```

Em um contexto mais profissional, o ideal é evitar `git add .` sem revisar. Uma prática mais cuidadosa seria:

```bash
git status
git diff
git add index.html styles.css readme.md
git commit -m "Documenta estrutura da aula de git"
git push
```

## Leitura de QA sobre o exercício

Para QA, Git não é apenas ferramenta de desenvolvedor. Ele aparece em várias atividades:

- revisar alterações antes de testar;
- identificar commits relacionados a falhas;
- comparar versões de uma aplicação;
- documentar evidências e scripts de teste;
- organizar automações em branches;
- manter histórico confiável de correções.

Este repositório mostra o início dessa base.

## Resultado técnico

O projeto mostra atenção a fundamentos: versionar, organizar, documentar e comunicar. Essas práticas são a base para projetos de QA mais complexos, nos quais rastreabilidade e clareza fazem diferença na manutenção dos testes.

## Competências evidenciadas

- Git básico e fluxo de commit.
- Estrutura inicial de projeto web.
- Leitura de HTML e CSS.
- Documentação com contexto.
- Evolução de tom informal para apresentação profissional.

## Próximos passos possíveis

- Publicar a página com GitHub Pages.
- Criar uma checklist simples de validação visual.
- Melhorar o HTML com marcação semântica.
- Criar uma versão com CSS mais organizado.
- Usar a página como alvo de automação inicial com Cypress ou Playwright.

## Conclusão

Este repositório é pequeno, mas cumpre um papel claro: registrar uma etapa de base na evolução técnica. O valor está no hábito de tratar até exercícios simples com organização, rastreabilidade e documentação adequada.
