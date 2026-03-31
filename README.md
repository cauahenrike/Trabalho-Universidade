# 📚 Sistema Escolar Completo (Python + C)

Este projeto é um sistema acadêmico dividido em duas partes:

* 🧠 **Back-end (Python):** responsável pelo gerenciamento completo de alunos, disciplinas e notas
* 💻 **Front-end (C):** responsável pela leitura e exibição dos relatórios

---

## 🚀 Funcionalidades

### 🧠 Back-end (Python)

* 🔐 Sistema de login com PIN do professor
* 👨‍🎓 Cadastro de alunos (nome, RA e turma)
* ✏️ Edição e exclusão de alunos
* 📁 Organização automática em pastas
* 📚 Criação e gerenciamento de disciplinas
* 🧮 Lançamento de notas por bimestre
* 📊 Cálculo automático de médias
* 🛠️ Edição e exclusão de notas
* 🔍 Busca de alunos por RA

---

### 💻 Front-end (C)

* 📄 Exibição de relatório completo por disciplina
* 🔍 Busca de aluno por RA
* 📊 Cálculo de média
* ✅ Status: aprovado ou reprovado

---

## 🛠️ Tecnologias utilizadas

* Python (lógica principal do sistema)
* C (visualização de dados)
* Manipulação de arquivos `.txt`
* Estrutura de diretórios automatizada
* Git e GitHub

---

## 📂 Estrutura do Projeto

O sistema cria automaticamente a seguinte estrutura na Área de Trabalho:

```
Desktop/
└── Sistema_Escola/
    ├── Cadastro de Alunos/
    │   ├── cadastro.txt
    │   └── [RA_NomeAluno]/
    │       └── informacoes.txt
    │
    ├── Cadastro de Disciplinas/
    │   ├── Matematica/
    │   │   └── notas.txt
    │   ├── Historia/
    │   ├── Portugues/
    │   ├── Artes/
    │   ├── Geografia/
    │   ├── Fisica/
    │   └── Algoritmo/
    │
    └── pin.txt
```

---

## 🧠 Como funciona

1. O sistema em Python:

   * Cria automaticamente as pastas
   * Gerencia alunos e disciplinas
   * Salva todas as informações em arquivos `.txt`

2. O sistema em C:

   * Lê os arquivos gerados pelo Python
   * Exibe relatórios organizados
   * Permite buscar alunos rapidamente

---

## ▶️ Como executar

### 🐍 Back-end (Python)

1. Execute o sistema:

```
python sistema.py
```

2. Configure o PIN na primeira execução
3. Utilize o menu para gerenciar alunos, disciplinas e notas

---

### 💻 Front-end (C)

1. Compile o código:

```
gcc sistema.c -o sistema
```

2. Execute:

```
./sistema
```

> 💡 No Windows:

```
sistema.exe
```

---

## 📌 Exemplo de dados

```
Aluno: João Silva; RA: 12345; Turma: A; Bimestre 1: 7.0; Bimestre 2: 6.5; Bimestre 3: 8.0; Bimestre 4: 7.5
```

---

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido com foco em:

* Lógica de programação
* Manipulação de arquivos
* Integração entre linguagens (Python + C)
* Organização de sistemas reais
* Prática de back-end e estrutura de dados

---

## 🚀 Possíveis melhorias

* Integração com banco de dados (SQL)
* Interface gráfica (GUI)
* API para comunicação entre módulos
* Sistema web completo

---

## 👨‍💻 Autor

Cauã Messias
Estudante de Análise e Desenvolvimento de Sistemas 🚀

---

💡 Projeto em evolução — focado em aprendizado prático e construção de portfólio.
