### **Método MoSCoW: Guia Completo de Aplicação**

#### **O que é o Método MoSCoW?**
Técnica de priorização criada por Dai Clegg na década de 1990 para o framework DSDM (Dynamic Systems Development Method). O acrônimo representa:

| Categoria    | Descrição                                                                 | Exemplo (App E-commerce)        |
|--------------|---------------------------------------------------------------------------|----------------------------------|
| **Must have** | Essencial para o sucesso - se não entregue, o projeto falha               | Login de usuário, Checkout       |
| **Should have** | Importante mas não crítico - pode ser adiado sem comprometer o core       | Histórico de pedidos             |
| **Could have** | Desejável - melhoria que pode ser incluída se houver recursos             | Recomendações personalizadas     |
| **Won't have** | Excluído do escopo atual - pode ser reconsiderado no futuro              | Integração com redes sociais     |

---

#### **Passo a Passo para Aplicação**

1. **Listagem de Requisitos**
   - Exemplo para app de delivery:
     - Cadastro de restaurantes
     - Rastreamento de entregas
     - Sistema de avaliações
     - Programa de fidelidade

2. **Classificação**
   ```markdown
   | Requisito               | Classificação | Justificativa                          |
   |-------------------------|---------------|----------------------------------------|
   | Cadastro restaurantes   | Must have     | Sem isso, não há produto               |
   | Rastreamento            | Should have   | Importante para UX mas não essencial   |
   | Avaliações              | Could have    | Melhoria secundária                    |
   | Fidelidade              | Won't have    | Complexo para MVP                      |
   ```

3. **Validação**
   - Realizar workshop com stakeholders
   - Limitar Must haves a ≤30% do total
   - Documentar critérios de decisão

4. **Gestão Contínua**
   - Revisões quinzenais
   - Matriz de acompanhamento:
   ```markdown
   | Requisito       | Sprint | Status   | Mudanças |
   |-----------------|--------|----------|----------|
   | Cadastro        | 1      | Done     | -        |
   | Rastreamento    | 2      | Doing    | ↑Should→Must |
   ```

---

#### **Melhores Práticas**
✅ **Combine com:**
   - Matriz RICE (Reach, Impact, Confidence, Effort)
   - Framework ICE (Impact, Confidence, Ease)

⚠️ **Cuidados:**
   - Evitar "Must creep" (tudo vira essencial)
   - Considerar dependências técnicas
   - Balancear visões de negócio vs. técnica

---

#### **Template Prático**
```markdown
# Backlog Priorizado - [Nome do Projeto]

**Data:** [DD/MM/AAAA]  
**Responsável:** [Nome]

| ID | Requisito          | Categoria  | Sprint | Justificativa                  |
|----|--------------------|------------|--------|--------------------------------|
| 1  | Login de usuário   | Must have  | 1      | Core functionality             |
| 2  | Carrinho           | Must have  | 1      | Essencial para conversão       |
| 3  | Filtros avançados  | Should have| 2      | Melhoria de usabilidade        |
```

---

#### **Ferramentas Recomendadas**
- **Visualização:** Miro, Trello (com labels coloridas)
- **Gestão:** Jira (usando campos customizados)
- **Documentação:** Confluence (com templates)
