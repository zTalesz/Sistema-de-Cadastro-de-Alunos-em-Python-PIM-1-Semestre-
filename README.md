
# 📘 Sistema de Cadastro de Alunos – PIM (1º Semestre)

Este projeto foi desenvolvido como parte do **PIM – Projeto Integrado Multidisciplinar** do 1º semestre do curso de Análise e Desenvolvimento de Sistemas.

O objetivo do sistema é realizar o **cadastro estruturado de alunos**, aplicando conhecimentos de lógica de programação, manipulação de arquivos, validações, entrada de dados e armazenamento persistente utilizando **JSON**.

---

## 🚀 Funcionalidades do Sistema

✔ **Cadastro completo do aluno**, incluindo:  
- Nome  
- CPF  
- Sexo  
- Data de nascimento  
- Idade (calculada automaticamente)  
- Estado (UF)  
- Cidade  
- E-mail  
- Telefone  
- Escolaridade atual  
- Experiência prévia com programação  
- Curso de interesse  
- Data de cadastro  
- Tempo de uso (iniciado em 0 dias)

✔ **Validações implementadas**:
- CPF com exatamente 11 dígitos  
- E-mail no formato correto  
- Data válida com cálculo automático da idade  
- UF com duas letras  
- Curso deve estar na lista pré-definida  
- Campos obrigatórios não podem ficar vazios  

✔ **Persistência de dados com JSON**:
- O sistema cria (ou atualiza) um arquivo `usuarios.json`
- Cada novo cadastro é adicionado ao final da lista existente
- Os dados são armazenados de forma organizada e legível para consultas futuras

✔ **Lista de Cursos Disponíveis**:
- JAVA  
- PYTHON  
- CSS  
- HTML  
- C  
- SQL  

---

## 🧠 Tecnologias Utilizadas

- **Python 3**
- Módulo `json` para armazenamento de dados  
- Módulo `datetime` para cálculo da idade e registro de data  
- Módulo `re` para validação de e-mail  
- Manipulação de arquivos `.json`

---

## 📂 Estrutura do Projeto

📁 Projeto_PIM/
│── main.py # Código principal do sistema
│── usuarios.json # Banco de dados dos alunos cadastrados
│── README.md # Documentação do projeto

---

## 🏗️ Fluxo do Sistema

1. O usuário inicia o programa  
2. Informa seus dados um por um  
3. O sistema valida cada informação  
4. A idade é calculada automaticamente  
5. O JSON é carregado (ou criado se não existir)  
6. Os novos dados são adicionados ao histórico  
7. O arquivo `usuarios.json` é atualizado  
8. O programa exibe uma mensagem confirmando o cadastro  

---

## 🎯 Objetivo Educacional

Este projeto demonstra:

- Lógica de programação  
- Boas práticas de validação de entrada  
- Estruturas de dados em Python  
- Manipulação de arquivos JSON  
- Programação procedural  
- Aplicação prática dos conceitos estudados no semestre

---

## 👨‍💻 Desenvolvido por

**Tales Lima** – Estudante de Análise e Desenvolvimento de Sistemas  
Projeto realizado para o **PIM – 1º Semestre / UNIP**

---

## 📄 Como Executar

1. Instale o Python 3  
2. Baixe ou clone este repositório  
3. Execute no terminal:

```bash
python main.py
