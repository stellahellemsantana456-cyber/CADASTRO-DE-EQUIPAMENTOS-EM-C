# CADASTRO-DE-EQUIPAMENTOS-EM-C
# 🖥️ Sistema de Gerenciamento de Equipamentos de Laboratório

Projeto desenvolvido em linguagem C para automatizar o cadastro e a consulta de equipamentos de um laboratório de informática, com armazenamento persistente em arquivo de texto (`.txt`).

---

## 🛠️ Tecnologias e Conceitos Utilizados
* **Linguagem C** (Manipulação de arquivos, ponteiros, estruturas de controle e repetição)
* **Funções de Arquivo:** `fopen()`, `fprintf()`, `fgets()` e `fclose()`
* **Git & GitHub** (Controlo de versões)

---

## ⚙️ Funcionalidades
1. **Cadastrar Equipamento:** Solicita o nome do equipamento, o código de identificação e a localização. Grava os dados no arquivo `equipamentos.txt` no modo *append* (`a`), preservando todos os registos anteriores.
2. **Listar Equipamentos:** Lê o arquivo `equipamentos.txt` linha por linha usando `fgets()` e exibe todos os equipamentos cadastrados no terminal.
3. **Sair:** Encerra a execução do programa de forma segura.

---

## 📦 Como Compilar e Executar

Siga os passos abaixo no terminal para rodar o projeto:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/stellahellemsantana456-cyber/laboratorio-equipamentos.git](https://github.com/stellahellemsantana456-cyber/laboratorio-equipamentos.git)
