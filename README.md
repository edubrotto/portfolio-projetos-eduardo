# 💻 Portfólio de Projetos – Eduardo Brotto

Repositório desenvolvido como parte da disciplina **Bootcamp**  
O objetivo é aplicar boas práticas de versionamento com **Git e GitHub**, colaboração em equipe e integração com ferramentas profissionais como o **LinkedIn**.

---

## 🧩 1. Planejamento do Repositório

### 🎯 Objetivo
Organizar e versionar projetos acadêmicos e pessoais, utilizando uma estrutura clara e padronizada que facilite a manutenção, colaboração e apresentação profissional dos trabalhos.

### 📁 Estrutura Proposta
O repositório é dividido em seções específicas para diferentes tipos de projetos e materiais:

```
portfolio-projetos-eduardo/
│
├── projetos-academicos/
│   ├── automacao-n8n/
│   │   ├── codigo/
│   │   ├── imagens/
│   │   └── README.md
│   ├── plataforma-ecommerce/
│   │   ├── requisitos.md
│   │   ├── diagramas/
│   │   └── README.md
│
├── projetos-pessoais/
│   ├── calculadora-web/
│   │   ├── index.html
│   │   ├── script.js
│   │   └── README.md
│
├── documentacao/
│   ├── guia-git.md
│   └── anotacoes.md
│
└── README.md

---

## 🧠 2. Criação e Versionamento de Projetos

### 🧰 Projeto Inicial: Calculadora Web
Um pequeno projeto desenvolvido em HTML, CSS e JavaScript para praticar versionamento com Git e publicação no GitHub.

### 🔧 Etapas Realizadas
1. Criação do repositório no GitHub:  
   ```bash
   git init
   git remote add origin https://github.com/SEU_USUARIO/portfolio-projetos-eduardo.git
   ```
2. Adição dos arquivos do projeto:  
   ```bash
   git add .
   git commit -m
   ```
3. Envio ao GitHub:  
   ```bash
   git push origin main
   ```
4. Alterações posteriores versionadas com commits descritivos, como:
   ```bash
   git commit -m "Melhora design da calculadora e adiciona modo escuro"
   ```

---

## 📂 3. Organização e Documentação do Repositório

Cada projeto possui seu próprio diretório com um arquivo `README.md` específico, contendo:
- Descrição do projeto  
- Tecnologias utilizadas  
- Instruções de uso  
- Prints ou diagramas

Exemplo de estrutura de documentação (`projetos-academicos/automacao-n8n/README.md`):
```markdown
# Automação com n8n

Projeto desenvolvido para automatizar o envio de mensagens utilizando o **n8n**.

## 🧩 Tecnologias
- n8n
- APIs REST
- JavaScript

## 🧪 Como executar
1. Importar o fluxo no n8n.
2. Configurar as variáveis de ambiente.
3. Executar o fluxo e validar as respostas.


```

---

## 🤝 4. Colaboração e Pull Requests

### 🌍 Contribuição em Repositórios Públicos
Foi realizado um **fork** de um repositório público, seguido de:
- Criação de uma branch de trabalho:
  ```bash
  git checkout -b ajuste-documentacao
  ```
- Adição de um novo arquivo `README.md` explicativo;
- Envio de um **Pull Request** para o projeto original.

Exemplo:
```bash
git checkout -b nova-funcionalidade
git push origin nova-funcionalidade
# Pull Request aberto no GitHub


## 5. Revisão Final e Apresentação

### 📹 Apresentação em Vídeo (YouTube)
Será criada uma breve apresentação explicando:
- Estrutura e objetivos do repositório;
- Principais projetos desenvolvidos;
- Demonstração prática do uso do Git e GitHub.
---

## 📜 Licença

Este repositório está sob a [Licença MIT](./LICENSE), permitindo o uso e modificação livre mediante atribuição ao autor.

---

## 📬 Contato

- 👤 **Autor:** Eduardo Brotto 
- 💾 [GitHub](https://github.com/edubrotto)  
- ✉️ **E-mail:** eduardo.ocastro@sempreceub.com


