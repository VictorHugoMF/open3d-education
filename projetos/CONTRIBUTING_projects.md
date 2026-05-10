# Como contribuir com o repositório `open3d-education`

Este repositório é usado para organizar os projetos da disciplina/atividade relacionados a modelagem, impressão 3D, arquivos STL, documentação técnica e registros visuais dos trabalhos desenvolvidos pelos alunos.

O repositório principal é: `observatorio-oceanografico/open3d-education`

Os projetos dos alunos devem ser colocados no seu semestre correspondente, por exemplo `projetos/2026-1/`

Cada grupo ou aluno deve criar uma pasta própria dentro desse diretório.

---

## Regra principal

Você **não deve editar diretamente** o repositório principal.

O fluxo correto é:

```text
Fork → editar no GitHub Web → enviar Pull Request
```

Você não precisa usar terminal, Git local ou VS Code para fazer esta contribuição básica. Pode fazer tudo pelo GitHub Web.

---

## O que cada projeto deve conter

Cada projeto deve ter uma pasta própria dentro de:

```text
projetos/2026-1/
```

Exemplo:

```text
projetos/2026-1/nome-do-projeto/
```

Dentro da pasta do projeto, inclua preferencialmente:

```text
projetos/2026-1/nome-do-projeto/
├── README.md
├── modelos/
│   └── arquivo.stl
├── imagens/
│   └── foto-ou-render.png
└── documentos/
    └── anotacoes-ou-relatorio.pdf
```

A estrutura pode ser simples, mas deve ser organizada.

---

## Nomes de pastas e arquivos

Use nomes simples, sem acentos, sem espaços e sem caracteres especiais.

Prefira:

```text
projetos/2026-1/mapa-batimetrico-baia/
modelo-final.stl
vista-superior.png
relatorio-projeto.pdf
```

Evite:

```text
Projeto João FINAL!!!/
modelo versão boa.stl
imagem da peça (nova).png
relatório finalíssimo.pdf
```

Regras recomendadas:

- use letras minúsculas;
- use hífen `-` para separar palavras;
- não use acentos;
- não use espaços;
- não use nomes genéricos como `final`, `novo`, `teste`, `versao2` sem explicação;
- não envie arquivos duplicados sem necessidade.

---

## Tamanho dos arquivos

Arquivos STL, imagens e PDFs podem ficar grandes.

Antes de enviar:

- remova arquivos temporários;
- não envie versões repetidas do mesmo modelo;
- reduza imagens muito grandes quando possível;
- envie apenas o que é necessário para entender e reproduzir o projeto.

Não envie:

```text
.zip
.rar
.7z
```

salvo se isso for explicitamente autorizado.

O ideal é que os arquivos fiquem visíveis diretamente no GitHub.

---

## Como criar seu fork

1. Acesse o repositório principal:

```text
https://github.com/observatorio-oceanografico/open3d-education
```

2. Clique em **Fork**, no canto superior direito.

3. Crie uma cópia do repositório na sua própria conta.

Depois disso, você terá um repositório parecido com:

```text
https://github.com/SEU-USUARIO/open3d-education
```

Esse é o seu fork.

É nele que você deve fazer as alterações.

---

## Como criar a pasta do seu projeto pelo GitHub Web

No seu fork:

1. Entre na pasta:

```text
projetos/2026-1/
```

2. Clique em **Add file**.

3. Clique em **Create new file**.

4. No campo do nome do arquivo, digite o caminho completo da sua nova pasta e do arquivo `README.md`.

Exemplo:

```text
projetos/2026-1/mapa-batimetrico-baia/README.md
```

O GitHub criará automaticamente a pasta `mapa-batimetrico-baia`.

5. Escreva o conteúdo inicial do `README.md`.

6. Ao final da página, clique em **Commit changes**.

---

## Modelo básico de `README.md` do projeto

Copie e adapte o modelo abaixo dentro da pasta do seu projeto.

```markdown
# Nome do projeto

## Integrantes

- Nome do aluno 1
- Nome do aluno 2
- Nome do aluno 3

## Resumo

Escreva um parágrafo curto explicando o que é o projeto, qual problema ele resolve ou o que ele representa.

## Objetivo

Descreva o objetivo principal do projeto.

## Descrição do modelo 3D

Explique o que foi modelado, quais partes compõem o objeto e qual a lógica do modelo.

## Arquivos do projeto

- `modelos/nome-do-arquivo.stl`: modelo 3D principal.
- `imagens/nome-da-imagem.png`: imagem, render ou fotografia do projeto.
- `documentos/nome-do-documento.pdf`: relatório, roteiro ou anotação complementar.

## Como visualizar ou imprimir

Explique brevemente como o arquivo pode ser aberto, visualizado ou preparado para impressão 3D.

Exemplo:

O arquivo `.stl` pode ser aberto em softwares como Cura, PrusaSlicer, Blender, FreeCAD ou outro visualizador de modelos 3D.

## Imagens

Inclua imagens do modelo, renderizações ou fotos do protótipo.

Exemplo:

![Vista do modelo](imagens/vista-do-modelo.png)

## Observações

Inclua aqui limitações, problemas encontrados, decisões de projeto ou melhorias futuras.

## Licença e uso

Este material foi produzido para fins educacionais no contexto do repositório `open3d-education`.
```

---

## Como enviar arquivos STL, imagens e documentos

No seu fork, dentro da pasta do seu projeto:

1. Clique em **Add file**.
2. Clique em **Upload files**.
3. Arraste os arquivos para a janela do GitHub.
4. Confira se os arquivos estão na pasta correta.
5. Escreva uma mensagem curta em **Commit changes**.

Exemplos de mensagens:

```text
Adiciona modelo STL inicial
Adiciona imagens do projeto
Atualiza documentação do projeto
```

6. Clique em **Commit changes**.

---

## Como organizar os arquivos dentro do projeto

Use subpastas quando houver mais de um tipo de arquivo.

Sugestão:

```text
modelos/      arquivos STL, OBJ ou similares
imagens/      fotos, renders, esquemas e capturas de tela
documentos/   PDFs, relatórios, roteiros e materiais complementares
codigo/       scripts, notebooks ou arquivos de programação, se existirem
```

Exemplo:

```text
projetos/2026-1/mapa-batimetrico-baia/
├── README.md
├── modelos/
│   ├── mapa-batimetrico-v1.stl
│   └── mapa-batimetrico-final.stl
├── imagens/
│   ├── render-frontal.png
│   └── foto-prototipo.jpg
└── documentos/
    └── descricao-do-projeto.pdf
```

---

## Como abrir o Pull Request

Depois de fazer as alterações no seu fork:

1. Acesse o seu fork no GitHub.
2. O GitHub normalmente mostrará um botão chamado **Compare & pull request**.
3. Clique nesse botão.
4. Confira se o Pull Request está indo:

```text
do seu fork
para observatorio-oceanografico/open3d-education
```

O destino correto deve ser:

```text
base repository: observatorio-oceanografico/open3d-education
base branch: main
```

5. No título do Pull Request, escreva algo claro.

Exemplos:

```text
Adiciona projeto mapa batimétrico da Baía
Adiciona projeto de modelo 3D do grupo 2
Atualiza documentação do projeto de protótipo costeiro
```

6. Na descrição, explique brevemente o que foi enviado.

Exemplo:

```text
Este Pull Request adiciona a pasta do projeto do grupo, incluindo o README, arquivos STL, imagens do modelo e documentação complementar.
```

7. Clique em **Create Pull Request**.

---

## O que escrever na descrição do Pull Request

Use este modelo:

```markdown
## O que foi feito

- Criação da pasta do projeto em `projetos/2026-1/`.
- Adição do arquivo `README.md`.
- Adição dos arquivos STL.
- Adição de imagens e/ou documentação complementar.

## Integrantes

- Nome do aluno 1
- Nome do aluno 2
- Nome do aluno 3

## Observações

Inclua aqui qualquer informação importante para a revisão.
```

---

## Depois de abrir o Pull Request

Aguarde a revisão.

O responsável pelo repositório poderá:

- aprovar o Pull Request;
- solicitar ajustes;
- comentar nomes de arquivos;
- pedir melhor organização;
- pedir complementação do `README.md`;
- pedir remoção de arquivos desnecessários.

Se forem solicitadas mudanças, faça as correções no seu fork. O Pull Request será atualizado automaticamente.

---

## Checklist antes de abrir o Pull Request

Antes de enviar, confira:

- [ ] A pasta do projeto está dentro de `projetos/2026-1/`.
- [ ] O nome da pasta está em letras minúsculas, sem espaços e sem acentos.
- [ ] Existe um `README.md` dentro da pasta do projeto.
- [ ] O `README.md` explica o objetivo do projeto.
- [ ] Os integrantes estão identificados.
- [ ] Os arquivos STL estão em uma pasta adequada, como `modelos/`.
- [ ] As imagens estão em uma pasta adequada, como `imagens/`.
- [ ] Os documentos complementares estão em `documentos/`, se existirem.
- [ ] Os arquivos têm nomes claros.
- [ ] Não há arquivos duplicados ou temporários.
- [ ] O Pull Request está sendo enviado para `observatorio-oceanografico/open3d-education`.

---

## O que não fazer

Não faça:

- editar projetos de outros grupos;
- apagar arquivos de outras pessoas;
- modificar arquivos fora da pasta do seu projeto sem autorização;
- enviar arquivos sem explicação;
- colocar tudo solto diretamente em `projetos/2026-1/`;
- usar nomes de arquivos com espaços, acentos ou caracteres especiais;
- enviar versões duplicadas sem indicar qual é a versão principal;
- abrir vários Pull Requests desnecessários para o mesmo projeto.

---

## Recomendações de boa documentação

Um bom projeto deve permitir que outra pessoa entenda:

- o que foi feito;
- por que foi feito;
- quem fez;
- quais arquivos são importantes;
- qual arquivo STL é o principal;
- como o modelo pode ser visualizado ou impresso;
- quais limitações ou melhorias futuras existem.

A documentação não precisa ser longa, mas precisa ser clara.

---

## Exemplo de estrutura aceitável

```text
projetos/2026-1/estrutura-costeira-didatica/
├── README.md
├── modelos/
│   └── estrutura-costeira.stl
├── imagens/
│   ├── render-modelo.png
│   └── foto-impressao.jpg
└── documentos/
    └── memoria-descritiva.pdf
```

---

## Exemplo de estrutura ruim

```text
projetos/2026-1/
├── trabalho final.zip
├── peça nova.stl
├── foto boa.jpeg
├── documento certo final.pdf
└── README qualquer.md
```

Problemas:

- arquivos soltos;
- nomes pouco claros;
- ausência de pasta própria do projeto;
- uso de espaços e acentos;
- arquivo compactado sem necessidade;
- difícil saber quem fez o quê.

---

## Dúvidas frequentes

### Preciso saber usar Git no terminal?

Não.

Para esta atividade, você pode fazer tudo pelo GitHub Web.

### Posso usar VS Code?

Pode, mas não é obrigatório.

Quem já sabe usar Git, terminal e VS Code pode trabalhar localmente. Para os demais, o GitHub Web é suficiente.

### Posso enviar mais de um STL?

Sim, desde que os arquivos estejam organizados e explicados no `README.md`.

### Posso enviar imagens?

Sim. Imagens ajudam a entender o projeto.

Coloque as imagens na pasta `imagens/`.

### Posso enviar PDF?

Sim, se for necessário.

Coloque PDFs na pasta `documentos/`.

### Posso enviar arquivos compactados?

Evite.

Prefira enviar os arquivos abertos e organizados em pastas.

### Posso editar depois de abrir o Pull Request?

Sim.

Faça novas alterações no seu fork. O Pull Request será atualizado automaticamente.

---

## Fluxo resumido

```text
1. Criar conta no GitHub
2. Acessar observatorio-oceanografico/open3d-education
3. Criar um fork
4. No fork, criar sua pasta em projetos/2026-1/
5. Adicionar README.md
6. Adicionar STL, imagens e documentos
7. Conferir a organização
8. Abrir Pull Request
9. Aguardar revisão
10. Fazer ajustes, se necessário
```

---

## Mensagem final

O objetivo deste repositório é construir um acervo organizado, reutilizável e compreensível de projetos educacionais envolvendo modelagem e impressão 3D.

Contribuições bem organizadas ajudam não apenas na avaliação da atividade, mas também na reutilização futura dos materiais por outros alunos, professores e colaboradores.
