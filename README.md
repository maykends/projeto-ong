# Mãos que Transformam

Projeto desenvolvido para a Experiência Prática I da disciplina de Desenvolvimento Front-end.

A proposta consiste na criação de uma plataforma web para uma ONG fictícia, utilizando HTML5 semântico, com foco em acessibilidade, organização da informação e formulários interativos.

## Objetivo

Desenvolver uma estrutura web simples e funcional para apresentar a ONG, seus projetos sociais e permitir o cadastro de doadores e voluntários.

## Estrutura do projeto

```text
projeto-ong/
├── html/
│   ├── index.html
│   ├── projetos.html
│   └── cadastro.html
│
└── imagens/
    ├── ong.jpg
    ├── ong.png
    └── ong.webp
```

## Páginas

### index.html
Página inicial da ONG, contendo:

- Apresentação institucional
- Missão da organização
- Formas de participação
- Informações de contato
- Imagem com atributo `alt` para acessibilidade

### projetos.html
Página destinada à apresentação das iniciativas sociais, contendo:

- Projetos da ONG
- Campanhas de arrecadação
- Informações sobre doações
- Informações sobre voluntariado
- Links para cadastro

### cadastro.html
Página responsável pelo cadastro de participantes, contendo:

- Dados pessoais
- Endereço
- Tipo de participação
- Disponibilidade
- Aceite dos termos

O formulário utiliza recursos nativos do HTML5, como:

- `required`
- `pattern`
- `type="email"`
- `type="date"`
- `type="tel"`
- `radio`
- `checkbox`
- `fieldset`
- `legend`

## Validações

Foram implementadas validações para:

- CPF: `000.000.000-00`
- Telefone: `(00) 00000-0000`
- CEP: `00000-000`
- E-mail
- Campos obrigatórios

## Tecnologias utilizadas

- HTML5
- Semântica HTML
- Validações nativas de formulários
- Acessibilidade web

## Acessibilidade

O projeto utiliza tags semânticas como:

- `header`
- `nav`
- `main`
- `section`
- `article`
- `footer`
- `address`

As imagens possuem atributo `alt`, e os campos de formulário utilizam `label` associado aos respectivos inputs.

## Validação

O código pode
