# Conceitos Básicos de Git e GitHub

<!-- Este arquivo introduz os conceitos fundamentais de controle de versão, Git e GitHub -->

## 📋 Objetivos de Aprendizagem

<!-- Liste aqui os objetivos de aprendizagem deste capítulo -->
<!-- Exemplo: "Ao final deste capítulo, você será capaz de..." -->

<!-- TODO: Adicione 3-5 objetivos de aprendizagem -->

## 🎯 Introdução

<!-- Escreva uma introdução geral sobre controle de versão e sua importância -->
<!-- Por que aprender Git? Onde é usado? -->
<!-- Mantenha entre 100-200 palavras -->

## O que é Controle de Versão?

<!-- TODO: Explique o que é controle de versão -->
<!-- Dicas:
- Por que precisamos de controle de versão?
- Quais problemas ele resolve?
- Exemplos do dia a dia (Google Docs histórico, Ctrl+Z, etc.)
- Diferença entre controle de versão local vs distribuído
-->

### Benefícios do Controle de Versão

<!-- TODO: Liste os principais benefícios -->
<!-- Exemplos: histórico completo, colaboração, backup, experimentação segura, etc. -->

## O que é Git?

<!-- TODO: Explique o que é Git -->
<!-- Dicas:
- Sistema de controle de versão distribuído
- Criado por Linus Torvalds em 2005
- Usado por milhões de desenvolvedores
- Software livre e open source
-->

### Características Principais do Git

<!-- TODO: Liste as características que tornam o Git especial -->
<!-- Exemplos: distribuído, rápido, integridade de dados, branching, etc. -->

### Como o Git Funciona?

<!-- TODO: Explique o modelo básico de funcionamento do Git -->
<!-- Dicas:
- Snapshots (não diferenças)
- Estados dos arquivos (working directory, staging area, repository)
- Commits como pontos na história
- Use diagramas ou exemplos visuais se possível
-->

## O que é GitHub?

O GitHub é uma **plataforma web** que hospeda repositórios Git na nuvem, adicionando ferramentas de colaboração, revisão de código e automação por cima do Git. Foi fundado em abril de 2008 por Tom Preston-Werner, Chris Wanstrath e PJ Hyett, o GitHub cresceu rapidamente e se tornou o lar da maioria dos projetos open source do mundo. Em junho de 2018, a Microsoft adquiriu o GitHub por US$ 7,5 bilhões, mantendo-o operando de forma independente e expandindo os recursos gratuitos, incluindo repositórios privados ilimitados para contas gratuitas.

### Recursos do GitHub

- **Repositórios remotos**: Hospeda seu código na nuvem, servindo como fonte de verdade compartilhada para toda a equipe
- **Pull Requests (PRs)**: Mecanismo para propor, revisar e discutir alterações antes de incorporá-las ao código principal
- **Issues**: Sistema integrado para rastrear bugs, tarefas e sugestões
- **GitHub Actions**: Plataforma de automação e CI/CD nativa, que roda testes e deploys automaticamente a cada push ou PR
- **GitHub Pages**: Hospedagem gratuita de sites estáticos direto de um repositório

## Diferença entre Git e GitHub

É importante entender que **Git e GitHub não são a mesma coisa.** Git é a ferramenta de controle de versão, enquanto GitHub é a plataforma que usa Git por baixo dos panos, você pode usar Git sem o GitHub, mas não pode usar o GitHub sem Git. De forma resumida, **Git é a ferramenta, GitHub é a plataforma.**

| Aspecto | Git | GitHub |
|---|---|---|
| O que é | Ferramenta de linha de comando | Plataforma web |
| Onde roda | Localmente, na sua máquina | Na nuvem |
| Criado por | Linus Torvalds (2005) | Preston-Werner, Wanstrath, Hyett (2008) |
| Necessita internet | Não | Sim |
| Custo | Gratuito e open source | Gratuito (com planos pagos) |

### Analogia Útil

Podemos pensar da seguinte forma, **o Git é como o Word e o GitHub é como o Google Drive.**

O Word (Git) é a ferramenta onde o trabalho acontece, você escreve, edita e mantém o histórico das versões. Enquanto o Google Drive (GitHub) é onde você armazena e compartilha esse trabalho com outras pessoas. Você pode usar o Word sem o Google Drive, mas o arquivo fica preso na sua máquina. Com o Drive, qualquer pessoa da equipe pode acessar, comentar e colaborar, e é exatamente isso que o GitHub faz pelo seu código.

## Conceitos Fundamentais

### Repositório (Repository)

<!-- TODO: O que é um repositório? -->
<!-- Tipos: local vs remoto -->

### Commit

<!-- TODO: O que é um commit? -->
<!-- Por que commits são importantes? -->
<!-- Estrutura de um commit: snapshot, mensagem, autor, timestamp -->

### Branch

<!-- TODO: Introdução básica ao conceito de branch -->
<!-- (Explicação detalhada virá no capítulo 03) -->

### Histórico

<!-- TODO: O que é o histórico do Git? -->
<!-- Como visualizar? Para que serve? -->

### Clone vs Fork

<!-- TODO: Explique a diferença entre clone e fork -->

## Instalação do Git

### Windows

<!-- TODO: Como instalar Git no Windows -->
<!-- Link para download: https://git-scm.com/download/win -->

### macOS

<!-- TODO: Como instalar Git no macOS -->
<!-- Homebrew, Xcode, download direto -->

### Linux

<!-- TODO: Como instalar Git no Linux -->
<!-- Comandos para Ubuntu/Debian, Fedora, Arch -->

### Verificando a Instalação

<!-- TODO: Como verificar se o Git foi instalado corretamente -->

```bash
# TODO: Adicione o comando para verificar versão do Git
```

## Configuração Inicial

<!-- TODO: Configure Git pela primeira vez -->

```bash
# TODO: Adicione comandos para configurar nome e email
# git config --global user.name "Seu Nome"
# git config --global user.email "seu@email.com"
```

### Por que Configurar Nome e Email?

<!-- TODO: Explique a importância dessas configurações -->

## Criando uma Conta no GitHub

<!-- TODO: Passo a passo para criar conta no GitHub -->

1. <!-- Passo 1 -->
2. <!-- Passo 2 -->
3. <!-- Passo 3 -->

## Exemplos Práticos

### Exemplo 1: Cenário sem Controle de Versão

<!-- TODO: Descreva um cenário caótico sem controle de versão -->
<!-- Exemplo: múltiplas cópias de arquivo, versões conflitantes, etc. -->

### Exemplo 2: Mesmo Cenário com Git

<!-- TODO: Mostre como Git resolve o problema do Exemplo 1 -->

## Erros Comuns

<!-- TODO: Liste erros comuns de iniciantes -->

### Erro 1: Confundir Git com GitHub

<!-- TODO: Como evitar essa confusão -->

### Erro 2: Não configurar nome e email

<!-- TODO: O que acontece e como corrigir -->

## Exercícios

<!-- TODO: Crie 3-5 exercícios práticos -->

1. <!-- Exercício 1: Instalar Git e verificar versão -->
2. <!-- Exercício 2: Configurar Git com seu nome e email -->
3. <!-- Exercício 3: Criar conta no GitHub -->

## Recursos Adicionais

<!-- TODO: Adicione links úteis para aprofundamento -->

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- <!-- Adicione mais recursos -->

## Glossário

<!-- TODO: Defina termos importantes usados neste capítulo -->

- **Commit**: <!-- Definição -->
- **Repository**: <!-- Definição -->
- **Clone**: <!-- Definição -->
- **Fork**: <!-- Definição -->

## Resumo

<!-- TODO: Faça um resumo dos pontos principais do capítulo -->
<!-- Lista de 5-8 pontos-chave que os alunos devem lembrar -->

---

## 👥 Contribuidores

<!-- Este conteúdo é colaborativo. Contribuidores deste arquivo: -->
<!-- Adicione seu nome quando contribuir:
- [@seu-usuario](https://github.com/seu-usuario) - Seção X
-->
