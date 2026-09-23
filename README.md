# ⚽ Sticker's Market FIFA® World Cup 2026 | Gerenciador de Figurinhas

Sistema completo em C++ desenvolvido via console (CLI) para gerenciamento de um catálogo, estoque e ponto de vendas de figurinhas da Copa do Mundo FIFA 2026.

---

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte dos estudos de programação e algoritmos, aplicando estruturas de dados em C++ (`std::vector`, `structs`, ponteiros/referências lógicas) e lógica de menus interativos com validações robustas de entrada de dados.

### 🎯 Funcionalidades Principais

- **Cadastro de Figurinhas:** Cadastro com verificação automática de duplicidade de código, validação de estoque e definição de preços.
- **Listagem Dinâmica:** Opção para filtrar e visualizar apenas as figurinhas *Ativas*, *Inativas* ou o catálogo *Completo*.
- **Consulta Avançada:** Busca rápida de figurinhas diretamente pelo código numérico ou pelo nome do jogador.
- **Alteração de Cadastros:** Submenu interativo para atualizar dados individuais (Código, Nome, Valor ou Estoque) sem perder a consistência do array.
- **Gestão de Estoque (Entrada):** Adição de quantidades ao estoque com reativação automática de figurinhas que estavam esgotadas.
- **Carrinho e Lançamentos de Vendas:** Sistema de carrinho de compras com verificação de estoque em tempo real, cálculo de subtotais, resumo e emissão de comprovante final.
- **Inativação e Reativação Manual:** Controle de status das figurinhas de forma interativa.

---

## 💻 Aos amigos Devs

Sintam-se livres para usar a base do código, fazer modificações ou propor melhorias! O projeto foi estruturado com foco em boas práticas de programação procedimental e modularização por menus em C++.

---

## 🧠 Contexto de Desenvolvimento

Este projeto foi desenvolvido inteiramente do zero, sem o auxílio de ferramentas de Inteligência Artificial, com o propósito fundamental de servir como base de estudos práticos de sintaxe, lógica de programação e manipulação de estruturas de dados em C++. Cada lógica de menu, validação e fluxo de caixa foi implementada manualmente para consolidação do aprendizado acadêmico.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
| :--- | :--- |
| **Linguagem** | C++ (Moderno / Padrão ISO) |
| **Biblioteca Padrão** | `<iostream>`, `<vector>`, `<string>`, `<locale>`, `<cstdlib>` |
| **Interface** | CLI (Command Line Interface / Console) |
| **Controle de Versão** | Git & GitHub |

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Você precisará ter um compilador de C++ instalado na sua máquina (como *GCC/G++* no Linux/Windows via MinGW, *Clang* ou Visual Studio).

1. Clone o repositório:
   ```bash
   git clone [https://github.com/jlcsmartines/projetoFigurinhas.git](https://github.com/jlcsmartines/projetoFigurinhas.git)
