# DdmProject

[EN](README.md) | PT-BR

Este projeto foi gerado usando [Angular CLI](https://github.com/angular/angular-cli) versão 21.0.4.

## Servidor de desenvolvimento

Para iniciar o servidor local, execute:

```bash
ng serve
```

Com o servidor em execução, acesse `http://localhost:4200/`. A aplicação recarrega automaticamente ao salvar alterações.

## Code scaffolding

Para gerar um novo componente:

```bash
ng generate component component-name
```

Para ver todos os schematics disponíveis:

```bash
ng generate --help
```

## Build

Para compilar o projeto:

```bash
ng build
```

Os artefatos são gerados em `dist/`, com otimizações para produção.

## Testes unitários

Para executar testes com [Vitest](https://vitest.dev/):

```bash
ng test
```

## Testes end-to-end

Para testes e2e:

```bash
ng e2e
```

O Angular CLI não inclui um framework e2e por padrão. Escolha o que fizer mais sentido para o projeto.

## Qualidade de codigo

Rodar lint:

```bash
ng lint
```

Formatar com Prettier:

```bash
prettier --write .
```

No pre-commit, o Husky executa `lint-staged` para lint e formatacao dos arquivos staged.

## Conventional Commits

Este repositorio valida Conventional Commits com commitlint (hook `commit-msg`).
Use o assistente de commit:

```bash
npm run commit
```

## Recursos adicionais

Mais informacoes sobre o Angular CLI: [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli).
