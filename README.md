# Open3D Education

Repositório colaborativo da disciplina universitária de criacao de elementos educacionais com impressao 3D.

## Objetivo do repositorio

O `open3d-education` organiza, documenta e compartilha projetos desenvolvidos por estudantes ao longo dos semestres, com foco na producao de recursos didaticos fisicos por meio de modelagem e impressao 3D.

A proposta e construir um acervo vivo: cada turma contribui com novos materiais, melhora projetos existentes e registra aprendizados tecnicos e pedagogicos para as proximas edicoes da disciplina.

## Proposta educacional

A disciplina integra tres eixos:

- projeto de objetos educacionais com intencao pedagogica explicita;
- fundamentos de fabricacao digital e preparo para impressao 3D;
- documentacao tecnica e reflexao sobre uso em contextos reais de ensino.

Os projetos devem ser pensados para uso didatico em escolas, laboratorios, projetos de extensao ou ambientes de formacao docente, considerando acessibilidade, seguranca, custo e reprodutibilidade.

## Organizacao por semestre

Os projetos sao organizados na pasta `projetos/` por semestre letivo:

- `projetos/2026-1/`
- `projetos/2026-2/`

Cada projeto deve ter uma pasta propria com nome claro e padronizado (ex.: `modelo-celula-ampliada`, `kit-fracoes-modular`) contendo arquivos tecnicos, documentacao e licenciamento.

## Tipos de arquivos esperados

Cada projeto deve incluir, quando aplicavel:

- modelos 3D editaveis e/ou finais (ex.: `.stl`, `.3mf`, `.step`, `.obj`);
- arquivos de fatiamento e perfis de impressao (ex.: `.3mf`, `.curaprofile`, configuracoes equivalentes);
- documentacao em Markdown (`README.md`, ficha tecnica, plano pedagogico);
- imagens e diagramas de montagem/uso;
- referencias bibliograficas, tecnicas e curriculares;
- licenca do projeto.

## Como documentar projetos

Use os modelos da pasta `templates/` para manter consistencia minima entre as entregas.

Toda submissao deve registrar claramente:

- versao do modelo (ex.: `v1.0`, `v1.1`);
- escala utilizada (ex.: `1:1`, `2:1`);
- unidade de medida do arquivo (mm, cm etc.);
- licenca adotada para reutilizacao.

Tambem e obrigatorio indicar parametros principais de impressao, tempo estimado, consumo aproximado de filamento e orientacoes de aplicacao pedagogica.

## Boas praticas para arquivos grandes

Este repositorio prioriza reprodutibilidade sem excesso de armazenamento. Antes de enviar arquivos muito grandes:

- verifique se o arquivo e realmente necessario para reproducao do projeto;
- prefira formatos otimizados e exportacoes finais em vez de historicos intermediarios;
- compacte imagens e materiais brutos quando possivel;
- descreva, no `README` do projeto, como obter arquivos externos quando o upload direto nao for recomendado.

## Recurso educacional aberto e em crescimento

O `open3d-education` e um Recurso Educacional Aberto (REA) em construcao continua. O valor do repositorio depende da qualidade da documentacao, da clareza pedagogica e da colaboracao entre turmas.

Contribuicoes sao bem-vindas de estudantes, docentes, monitores e parceiros externos, respeitando as diretrizes de conduta, autoria e licenciamento.

## Licenca do repositorio

Este repositorio adota a licenca MIT (ver arquivo `LICENSE`).

Em projetos de semestre, quando houver necessidade pedagogica ou de compatibilidade com recursos externos, pode ser utilizada outra licenca, desde que:

- esteja explicitamente declarada na pasta do projeto;
- seja compativel com os materiais incluidos;
- preserve a atribuicao correta de autoria e fontes.

## Leitura recomendada no repositorio

- `docs/index.md`
- `docs/como-contribuir.md`
- `docs/guia-impressao-3d.md`
- `docs/boas-praticas-documentacao.md`
- `CONTRIBUTING.md`
