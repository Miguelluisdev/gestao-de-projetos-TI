## 🧠 Cartão de Heurísticas para Testadores

### 🔍 **FEW HICCUPPS** – Guia de Exploração

| Letra | Heurística      | Perguntas para Guiar o Teste                                            |
| ----- | --------------- | ----------------------------------------------------------------------- |
| **F** | Familiaridade   | Isso parece familiar ao usuário? É intuitivo?                           |
| **E** | Expectativas    | Está de acordo com as expectativas do cliente e stakeholders?           |
| **W** | "World" (Mundo) | Reflete o mundo real? Valores, cálculos e comportamentos fazem sentido? |
| **H** | História        | Quais bugs e mudanças passadas afetam essa área?                        |
| **I** | Imagem          | A UI está de acordo com a identidade visual e branding?                 |
| **C** | Comparável      | Pode ser comparado com outra versão, app, sistema ou fluxo?             |
| **C** | Compatibilidade | Funciona em diferentes navegadores, SOs, dispositivos?                  |
| **U** | Usuário         | O comportamento atende às necessidades do usuário final?                |
| **P** | Propósito       | Essa funcionalidade cumpre seu objetivo real?                           |
| **P** | Produto         | Está alinhado com o restante do sistema e integrações?                  |
| **P** | Padrões         | Segue os padrões da empresa, usabilidade, mercado?                      |
| **S** | Surpresa        | Algo foi inesperado, estranho ou confuso?                               |

---

### 🧪 **Oráculos de Teste** – Como saber se algo é um defeito?

* **Consistência com especificações** (documentos, critérios de aceite)
* **Consistência com o esperado pelo usuário**
* **Consistência com o comportamento anterior**
* **Consistência com sistemas semelhantes**
* **Consistência interna entre partes do sistema**
* **Consistência com o mundo real**
* **Consistência com padrões estabelecidos**

---

### 🧰 **SFDIPOT** – Análise do Sistema

| Letra | Elemento   | O que observar?                                       |
| ----- | ---------- | ----------------------------------------------------- |
| **S** | Structure  | Organização do sistema, páginas, módulos, fluxos      |
| **F** | Functions  | Funcionalidades disponíveis e seus objetivos          |
| **D** | Data       | Dados usados, formatos, entradas e saídas             |
| **I** | Interfaces | Interações com o usuário e com sistemas externos      |
| **P** | Platform   | Onde roda? (SO, navegador, mobile, desktop, nuvem...) |
| **O** | Operations | Rotinas comuns, ações esperadas e atípicas            |
| **T** | Time       | Desempenho, resposta, tempo de execução, agendamentos |

---

### 🔄 **CRUD** – Operações básicas para testar

* **C**reate – Criar registros
* **R**ead – Visualizar/exibir dados
* **U**pdate – Alterar dados
* **D**elete – Remover dados

---

### 🧼 **RCRCRC** – Controle e Limpeza

* **Reach** – Posso acessar o recurso?
* **Claim** – Posso controlar ou ativar?
* **Read** – Consigo ler os dados?
* **Change** – Posso modificar ou interagir?
* **Restore** – Posso desfazer ou restaurar o estado anterior?
* **Cleanup** – Posso limpar ou apagar os dados usados?

---

### 🗂 Dica final

> Use essas heurísticas como uma *caixa de ferramentas investigativa* — a cada novo sistema, requisito ou funcionalidade, pense:
> **“Qual heurística pode me ajudar a explorar isso melhor?”**
