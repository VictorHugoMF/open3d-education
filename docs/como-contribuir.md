# Como Contribuir

Este guia detalha como submeter projetos ao repositorio da disciplina.

## 1. Escolha do semestre e criacao da pasta

Crie sua pasta em `projetos/<semestre>/<nome-do-projeto>/`, seguindo o padrao do periodo letivo (ex.: `2026-1`).

## 2. Estrutura minima recomendada

- `README.md`
- `modelos/`
- `slicer/`
- `imagens/`
- `referencias/`
- `LICENSE`

## 3. Documentacao obrigatoria

Preencha os templates em `templates/` e adapte ao contexto do seu projeto.

Registro minimo obrigatorio:

- versao do modelo;
- escala;
- unidade de medida;
- licenca;
- parametros centrais de impressao;
- aplicacao pedagogica prevista.

## 4. Controle de qualidade antes do PR

Checklist de revisao:

- arquivos abrem corretamente em ferramentas comuns;
- nomes de arquivos estao consistentes e legiveis;
- imagens estao claras e com boa relacao com o texto;
- justificativa pedagogica esta coerente com objetivo e publico-alvo;
- licenciamento esta explicito.

## 5. Arquivos grandes

Nao envie arquivos excessivamente grandes sem necessidade.

Antes do envio:

- confirme se o arquivo e indispensavel para reproducao;
- prefira formatos otimizados;
- remova duplicatas e exportacoes intermediarias;
- quando um arquivo externo for necessario, documente o acesso no `README.md`.

## 6. Submissao

Abra um Pull Request com:

- resumo do projeto;
- contexto educacional de uso;
- principais especificacoes tecnicas;
- dificuldades encontradas e melhorias propostas.
