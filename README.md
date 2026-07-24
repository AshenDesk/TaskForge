# 🗂 TASKFORGE - Gerenciador de Produtividade e Agenda (CLI)

Um **gerenciador de tarefas em linha de comando**, escrito em Python, projetado para organizar atividades pessoais e profissionais com foco em produtividade, disciplina e acompanhamento de tempo.

O sistema funciona em **arquivo único**, com **persistência automática em JSON**, suporte a **cronômetro por tarefa**, **remoção automática de tarefas vencidas** e categorização por tipo de atividade.

---

## ✨ Funcionalidades

- 📌 Criação, edição e exclusão de tarefas  
- ⏱ Cronômetro por tarefa  
  - Último tempo registrado  
  - Tempo total acumulado  
- 📅 Definição de prazo (data e hora)  
- 🗑 Remoção automática de tarefas vencidas  
- 🔁 Checagem periódica em thread daemon  
- 💾 Persistência local em arquivo `tarefas.json`  
- 🔍 Busca por ID parcial ou título  
- 📋 Listagem separada entre tarefas pendentes e concluídas  

---

## 🖥 Interface

Interface totalmente **interativa via terminal**, com menus simples e navegação direta.

---

## 📦 Requisitos

- Python **3.8 ou superior**
- Sistema operacional Linux, macOS ou Windows
- Não utiliza bibliotecas externas (somente biblioteca padrão)
- Permissão root

---

## 🚀 Instalação (via GitHub)

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/AshenDesk/taskforge.git

2. Acesse o diretório do projeto:

    cd taskforge

3. (Opcional) Torne o arquivo executável:

    chmod +x taskforge.py 
    
---

## ▶ Uso

Execute diretamente pelo Python:

    python3 taskforge.py


Ou, se estiver executável:

    ./taskforge.py


Na primeira execução, o arquivo `tarefas.json` será criado automaticamente no mesmo diretório para persistência dos dados.

---

## 🗂 Estrutura do Projeto

- `gerenciador.py` — aplicação principal (CLI)
- `tarefas.json` — base de dados local (gerada automaticamente)

> ⚠ **Atenção:** evite editar manualmente o arquivo `tarefas.json` enquanto o programa estiver em execução, para não causar inconsistências.

---

## 🔐 Privacidade e Armazenamento

- Todos os dados são armazenados **localmente**
- Nenhuma informação é enviada para a internet
- Ideal para uso pessoal, estudo ou ambientes offline

---

## 📜 Licença

Este projeto é distribuído sob a **GNU General Public License v3.0 (GPLv3)**.

Você tem permissão para:
- ✅ Usar o software
- ✅ Estudar o código-fonte
- ✅ Modificar
- ✅ Redistribuir versões originais ou modificadas

Desde que:
- 📄 A licença GPLv3 seja mantida
- 🔓 O código continue aberto
- ✍ A autoria original seja preservada

Este software é fornecido **sem qualquer garantia**, conforme descrito na licença.

Consulte o arquivo `LICENSE` para o texto completo da GPLv3.

---

## 👤 Autor

**Código e concepção:** Bandeirinha  
**Projeto:** TASKFORGE  
**Versão:** 1.0.0

