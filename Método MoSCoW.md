### **Método MoSCoW: Resumo Completo com Aplicação Prática**  

O **Método MoSCoW** é uma técnica de priorização amplamente utilizada em gestão de projetos, desenvolvimento ágil e análise de negócios. Criado por **Dai Clegg** na década de 1990, ele foi originalmente desenvolvido para o **DSDM (Dynamic Systems Development Method)**, um framework ágil.  

O nome **MoSCoW** é um acrônimo para:  
- **M**ust have (**Deve ter**) → Essencial para o sucesso do projeto.  
- **S**hould have (**Deveria ter**) → Importante, mas não crítico.  
- **C**ould have (**Poderia ter**) → Desejável, mas não prioritário.  
- **W**on’t have (**Não terá agora**) → Excluído do escopo atual (pode ser revisitado no futuro).  

---

## **Quando Usar o MoSCoW?**  
✔ **Definição de MVP** (Produto Mínimo Viável).  
✔ **Priorização de backlog** em metodologias ágeis (Scrum, Kanban).  
✔ **Alinhamento entre stakeholders** sobre o que é crítico vs. opcional.  
✔ **Controle de escopo** para evitar *scope creep* (expansão descontrolada).  

---

## **Como Aplicar o MoSCoW? (Passo a Passo)**  

### **1. Liste Todos os Requisitos**  
Exemplo para um app de e-commerce:  
- Login de usuário  
- Carrinho de compras  
- Recomendações personalizadas  
- Integração com redes sociais  

### **2. Classifique Cada Item**  
| Requisito               | Classificação MoSCoW | Justificativa                          |  
|-------------------------|----------------------|----------------------------------------|  
| Login de usuário        | **Must have**        | Sem login, não há venda.               |  
| Carrinho de compras     | **Must have**        | Essencial para transações.             |  
| Pagamento com PIX       | **Should have**      | Importante, mas pode ser v2.           |  
| Recomendações           | **Could have**       | Melhoria de UX, mas não crítica.       |  
| Integração com Instagram| **Won’t have**       | Baixo impacto no MVP.                  |  

### **3. Valide com a Equipe e Stakeholders**  
- Garanta consenso sobre o que é **Must have**.  
- Evite inflar a categoria "Must" (risco de sobrecarga).  

### **4. Revise Iterativamente**  
- Reclassifique itens conforme mudanças no projeto.  

---

## **Vantagens do MoSCoW**  
✅ **Simplicidade**: Fácil de entender e aplicar.  
✅ **Foco no MVP**: Evita desperdício de recursos em funcionalidades não essenciais.  
✅ **Comunicação Clara**: Alinha expectativas entre equipe e stakeholders.  

## **Desvantagens do MoSCoW**  
❌ **Subjetividade**: Depende da interpretação de cada stakeholder.  
❌ **Risco de "Must Have" Inflado**: Se tudo for "essencial", nada é prioritário.  
❌ **Não Considera Dependências**: Pode ignorar tarefas que são pré-requisitos para outras.  

---

## **Dicas Práticas para Usar o MoSCoW**  
🔹 **Combine com Outras Técnicas**: Use junto com **Matriz de Eisenhower** ou **Value vs. Effort** para decisões mais estratégicas.  
🔹 **Limite os "Must Have"**: Idealmente, menos de 30% do backlog.  
🔹 **Documente as Decisões**: Registre por que um item foi classificado como "Won’t have" para evitar retrabalho.  

---

### **Exemplo Prático (App de Delivery)**  
| Requisito               | Classificação |  
|-------------------------|---------------|  
| Cadastro de restaurantes| Must have     |  
| Rastreamento de entrega | Should have   |  
| Cupons de desconto      | Could have    |  
| Chat com entregador     | Won’t have    |  

**Resultado**: O MVP terá cadastro de restaurantes e pedidos, enquanto rastreamento será priorizado na próxima sprint.  

# Como Aplicar o Método MoSCoW - Passo a Passo

## 1️⃣ Identifique todos os requisitos
Faça uma lista completa de todos os requisitos e funcionalidades do seu projeto/produto.

**Exemplo:**
- Sistema de login
- Carrinho de compras
- Histórico de pedidos
- Recomendações personalizadas

## 2️⃣ Classifique os requisitos
Atribua cada item a uma das categorias:

| Categoria       | Descrição                          |
|-----------------|------------------------------------|
| **Must have**   | Essa classificação compreende os requisitos que são indispensáveis para a entrega. Elas são aquelas tarefas que vão agregar valor ao produto final, ao atendimento de requisitos, ou ainda, garantir o complianceda empresa.

Ainda, esses itens são os que, se forem atrasados, todo o produto final atrasará em consequência disso |
| **Should have** |Os itens que recebem esse rótulo são os que são importantes, mas não são vitais do ponto de vista estratégico para o produto final. Isso significa dizer que eles não são críticos e que as necessidades do cliente podem ser atendidas de outra maneira, ou ainda, que se pode esperar um pouco mais para fazer essa entrega.  |
| **Could have**  | As tarefas desse tipo são as desejáveis, mas também não são essenciais do ponto de vista estratégico da entrega e da satisfação do cliente. Então, essas tarefas são as que podem ser atendidas quando houver tempo e também quando houver recursos disponíveis para poder finalizá-la.  |
| **Won't have**  | Os itens que recebem essa classificação são aqueles que ficam acordados entre o time e os stakeholders que são do tipo menos críticos, com menor retorno do investimento do produto final.

Além disso, podem ser também vistas como não sendo adequadas para serem realizadas por algum tempo. Por meio dessa classificação, é possível evitar o crescimento desorganizado do escopo do projeto, o que confunde os desenvolvedores.

Você pode perceber como esse método possui foco na entrega por meio de priorização? É realmente incrível e te ajudará com entregas de valor que atenderão as expectativas do seu cliente!

Ainda na dúvida se deve, ou não, usar essa técnica? Confira algumas vantagens e desvantagens a seguir!          |

## 3️⃣ Priorize os Must Have
- Coloque no topo da lista
- Devem ser implementados primeiro
- Limite a ~30% do total de requisitos

**Exemplo Must Have:**
1. Autenticação de usuário
2. Processo de checkout

## 4️⃣ Foque nos Should Have
- Implemente após os Must Have
- Representam ~40-50% dos requisitos

**Exemplo Should Have:**
- Filtros de busca avançada
- Notificações por e-mail

## 5️⃣ Avalie os Could Have
- Implemente apenas se sobrar recursos
- Máximo de ~20% dos requisitos

**Exemplo Could Have:**
- Integração com redes sociais
- Temas personalizáveis

## 6️⃣ Descarte os Won't Have
- Documente os motivos da exclusão
- Pode reconsiderar em versões futuras

**Exemplo Won't Have:**
- Chatbot de atendimento (para v1.0)

## 7️⃣ Revise a classificação
✔ Valide com stakeholders  
✔ Verifique consistência  
✔ Ajuste se necessário  

## 8️⃣ Compartilhe a lista
- Comunique a toda equipe
- Use ferramentas visuais (Trello, Jira)
- Mantenha acessível

## 9️⃣ Gerencie mudanças
- Estabeleça processo para novas demandas
- Reclassifique requisitos periodicamente
- Documente todas as alterações




