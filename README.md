# BankMarketing

O setor bancário está em constante evolução, e uma das principais estratégias para impulsionar os negócios é a utilização de campanhas de marketing direcionadas. Neste contexto, entender o comportamento dos clientes e identificar os fatores que influenciam suas decisões é essencial para otimizar os resultados dessas campanhas.

Neste projeto, trabalhamos com um dataset de Bank Marketing , que contém informações detalhadas sobre clientes abordados durante uma campanha de marketing de um banco. A variável alvo, denominada y , indica se o cliente adquiriu ou não o produto oferecido (neste caso, um depósito a prazo).

Nosso objetivo é realizar uma análise exploratória completa do dataset, respondendo perguntas relevantes e extraindo insights valiosos que possam orientar decisões estratégicas. Ao longo deste trabalho, investigaremos padrões, correlações e tendências nos dados, além de explorar como diferentes atributos dos clientes impactam a probabilidade de aceitação do produto.

Este estudo não apenas contribui para uma compreensão mais profunda do comportamento dos clientes, mas também serve como base para o desenvolvimento de modelos preditivos e estratégias de marketing mais eficazes.

Fonte: https://archive.ics.uci.edu/dataset/222/bank+marketing

**age**: Idade do cliente

**job**: Tipo de trabalho do cliente

**marital**: Estado civil do cliente

**education**: Nível de educação do cliente

**default**: Indica se o cliente é inadimplente ou não

**balance**: Saldo médio anual na conta do cliente

**housing**: Indica se o cliente possui um empréstimo de habitação

**loan**: Indica se o cliente possui um empréstimo pessoal

**contact**: Meio de contato com o cliente

**day**: Dia do mês que o cliente foi contatado pela última vez

**month**: Mês em que o cliente foi contatado pela última vez

**duration**: Duração do último contato com o cliente, em segundos.

**campaing**: Número de contatos realizados durante esta campanha para este cliente.

**pdays**: Número de dias que se passaram desde o último contato com o cliente em uma campanha anterior. Um valor de -1 significa que o cliente não foi contatado anteriormente.

**previous**: Número de contatos realizados antes desta campanha para este cliente.

**poutcome**: Resultado da campanha de marketing anterior 

**y**: Variável alvo: indica se o cliente subscreveu ao produto (depósito a prazo) ("yes" ou "no").

### Visualização dos dados da Analise Univariada:

![image](https://github.com/user-attachments/assets/0fdee041-6abf-4013-8f2e-845097f6b928)

![image](https://github.com/user-attachments/assets/ac429b10-731d-46f0-a8e8-686308ada563)

![image](https://github.com/user-attachments/assets/31aef00c-9f0d-432e-851b-5d7fde6f5096)

![image](https://github.com/user-attachments/assets/8a1a7e4c-2d4e-4f36-8198-2412beab8f99)


### **Relatório da Análise Univariada**

A análise univariada permitiu mapear o perfil demográfico e comportamental dos clientes do banco, revelando padrões essenciais para entender o público-alvo da campanha. Os principais insights são:

#### **1. Distribuição de Idade**  
- **Faixa etária predominante**: 86.6% dos clientes estão entre **26 e 55 anos**, com mediana de 42 anos.  
- **Observações**:  
  - A distribuição é ligeiramente assimétrica à direita, indicando maior concentração de clientes na fase adulta economicamente ativa.  
  - A menor representatividade está na faixa acima de 65 anos, sugerindo menor engajamento com clientes mais velhos.

#### **2. Profissão**  
- **Principais categorias**:
  - **Management**: 21.4% (cargos de liderança ou alta responsabilidade).  
  - **Blue Collar**: 20.9% (profissionais com empregos manuais ou operários).  
  - **Technician**: 16.9% (profissionais técnicos ou especializados).  
- **Observações**:  
  - Esses três grupos somam **59.2% do total**, indicando um público majoritariamente composto por trabalhadores estáveis e com renda regular.  
  - A categoria "Unknown" (10%) aponta para falhas na coleta de dados, o que pode comprometer análises futuras.

#### **3. Meio de Contato**  
- **Principais canais**:  
  - **Celular**: 64% dos contatos.
  - **Dados faltantes**: 29.3% (indicados como "Unknown").  
  - **Telefone fixo**: 6.7%.  
- **Observações**:  
  - O alto percentual de dados não registrados sugere **falhas operacionais** no registro das interações.  
  - O celular é o canal preferencial, alinhado com tendências de digitalização dos serviços bancários.

#### **4. Estado Civil**  
- **Distribuição**:  
  - **Casados**: 61.9% (maioria significativa).  
  - **Solteiros**: 26.5%.  
  - **Divorciados/Viúvos**: 11.7%.  
- **Observações**:  
  - Clientes casados são o grupo mais abordado, possivelmente devido à percepção de maior estabilidade financeira.  
  - Estratégias específicas podem ser necessárias para engajar solteiros.

---

### **Perfil do Cliente Típico**  
| **Característica**       | **Descrição**                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Idade**                | Adulto entre 26 e 55 anos, economicamente ativo.                           |
| **Profissão**            | Trabalhador com ocupação estável (Blue Collar, Management ou Technician).  |
| **Estado Civil**         | Casado, sugerindo responsabilidades familiares.                            |
| **Canal de Contato**     | Majoritariamente por celular, mas com gaps nos registros.                  |

---

### **Recomendações Iniciais**  
1. **Melhorar a qualidade dos dados**: Investigar a causa dos registros "Unknown".  
2. **Segmentação estratégica**: Criar campanhas direcionadas para grupos sub-representados (ex.: clientes acima de 65 anos).  
3. **Otimizar canais digitais**: Priorizar o contato via celular, mas diversificar estratégias para reduzir dependência.  

---

**Próximos passos**:  
Na análise bivariada, investigaremos como algumas variáveis se relacionam com o saldo médio e a target (y)

### Visualização dos Dados da Analise Bivariada:

![image](https://github.com/user-attachments/assets/92e1f1a8-d5ec-4df1-a61a-0aafad081b1a)

![image](https://github.com/user-attachments/assets/9c8058de-e31f-4eee-982b-506e6c9d81d5)

![image](https://github.com/user-attachments/assets/4c9998ca-29ce-480e-a079-f4357fac671a)

![image](https://github.com/user-attachments/assets/0833415d-bcd8-4871-8400-3904af08f6e7)

![image](https://github.com/user-attachments/assets/d53e034b-9620-47ac-8252-fca40732c939)


### **Relatório de Análise Bivariada: Saldo Médio e Comportamento de Aquisição**

#### **Objetivo da Análise**  
Investigar a relação entre o **saldo médio na conta (balance)** e a probabilidade de clientes adquirirem produtos financeiros (empréstimo pessoal e financiamento habitacional), identificando padrões e anomalias nos dados.

---

#### **1. Análise por Empréstimo Pessoal (`loan`)**  
- **Saldo Médio por Grupo**:  
  - **Clientes que não adquiriram empréstimo**: Média de saldo significativamente maior (1513.86)  
  - **Clientes que adquiriram empréstimo**: Média de saldo menor (917.16)
- **Insights**:  
  - Clientes com **menor saldo médio** estão mais propensos a contratar empréstimos, possivelmente devido a necessidades financeiras imediatas.  
  - A diferença entre os grupos é **acentuada** (redução de ~39.42% no saldo médio para quem adquiriu o produto).  

---

#### **2. Análise por Financiamento Habitacional (`housing`)**  
- **Saldo Médio por Grupo**:  
  - **Clientes sem financiamento**: Média de saldo ligeiramente maior (1595.28).  
  - **Clientes com financiamento**: Média de saldo menor (1290.31).  
- **Insights**:  
  - A diferença é **menos pronunciada** comparada aos empréstimos pessoais (redução de 19.12%).  
  - Indica que o financiamento habitacional pode atrair clientes com perfis financeiros **mais estáveis**, mesmo com saldo moderado.  

---

#### **3. Padrão Observado**  
- **Tendência geral**:  
  Clientes com **saldo médio mais baixo** têm maior probabilidade de adquirir produtos financeiros (empréstimos/financiamentos).  
- **Hipóteses**:  
  - Necessidade de liquidez imediata para cobrir dívidas ou investimentos.  
  - Ofertas de crédito podem ser direcionadas a clientes com menor capacidade de poupança.  

---

#### **4. Recomendações Estratégicas**  
1. **Segmentação de clientes**:  
   - Priorizar clientes com saldo médio menor para campanhas de empréstimo.  
   - Oferecer financiamento habitacional para clientes com saldo moderado.  
2. **Revisão de critérios de crédito**:  
   - Avaliar alinhamento entre concessão de crédito para saldos baixos e perfil de risco.  
3. **Coleta de dados complementares**:  
   - Incluir histórico de crédito, renda mensal e *score* de crédito.

---

### Visualização dos Dados Outliers

![image](https://github.com/user-attachments/assets/81bbc4fb-10c0-4673-86ff-1afe07d08580)


#### **Relatório de Investigação de Outliers**

- **Observações críticas**:  
  - **Outliers no grupo de não contratação**: Identificamos clientes com saldos extremamente altos que optaram por **não contratar** empréstimos pessoais ou financiamentos habitacionais. Esses valores não parecem ser erros, mas sim reflexos de indivíduos com maior poder aquisitivo, que podem preferir manter reservas financeiras elevadas e evitar comprometimentos de crédito.  
  - **Outliers no grupo de contratação**: Também encontramos clientes com saldos muito altos que **contrataram** esses produtos. Isso sugere que, mesmo entre indivíduos com maior poder aquisitivo, há perfis dispostos a aproveitar oportunidades únicas, como taxas de juros baixas, ofertas personalizadas ou investimentos de longo prazo.  

- **Hipóteses iniciais**:  
  1. Os outliers altos no grupo de **não contratação** indicam uma tendência de **conservadorismo financeiro** entre pessoas com maior poder aquisitivo, priorizando a segurança financeira e a manutenção de reservas.  
  2. Os outliers altos no grupo de **contratação** refletem estratégias ativas de uso de crédito, mesmo para indivíduos com alto saldo médio, possivelmente para otimizar fluxos de caixa ou aproveitar condições vantajosas.  
  3. A presença desses outliers demonstra que há uma **camada significativa da população com renda elevada**, o que deve ser considerado ao segmentar públicos-alvo para campanhas futuras relacionadas a empréstimos e financiamentos.
 
---

### Visualização dos Dados de Distribuição de Target

![image](https://github.com/user-attachments/assets/ff9407d0-a205-4200-8374-d200373dcc3a)

![image](https://github.com/user-attachments/assets/c89addfc-5189-46bd-b39f-97e13e6efe10)

![image](https://github.com/user-attachments/assets/0efe9f49-234f-4225-aeaa-f0d428924a7d)

![image](https://github.com/user-attachments/assets/78dc1480-4de2-440b-acf6-cccab7db687b)



### **Análise das Relações entre as Variáveis e o Alvo (`y`)**

Após analisarmos a distribuição da variável alvo (`y`, depósito a prazo), identificamos padrões importantes ao relacionar as principais variáveis categóricas e numéricas com o resultado da campanha. Esses insights ajudam a entender o comportamento dos clientes e orientar decisões estratégicas.

#### **1. Financiamento Habitacional (`housing`):**
- Observamos que a **maioria dos clientes que adquiriram o depósito a prazo não possui financiamento habitacional**.
- Especificamente:
  - **90% dos clientes que adquiriram o depósito a prazo** não têm financiamento habitacional.
  - Apenas **10% dos clientes que adquiriram o depósito a prazo** possuem financiamento habitacional.
- Isso sugere que clientes com financiamento habitacional são menos propensos a aderir ao depósito a prazo, possivelmente devido a compromissos financeiros prévios ou menor capacidade de poupança.

#### **2. Empréstimo Pessoal (`loan`):**
- Similar ao financiamento habitacional, a **maior parte dos clientes que adquiriram o depósito a prazo não possui empréstimos pessoais**.
- Este padrão indica que clientes sem dívidas ativas (como empréstimos) estão mais inclinados a investir em produtos financeiros como depósitos a prazo.
- A ausência de compromissos de crédito pode refletir maior estabilidade financeira, tornando esses clientes mais receptivos à oferta do banco.

#### **3. Inadimplência (`default`):**
- Em relação à inadimplência, observamos um **pequeno aumento na proporção de clientes inadimplentes entre aqueles que adquiriram o depósito a prazo**.
- No entanto, essa diferença é **marginal e pouco relevante** para a análise preditiva.
- Isso sugere que a inadimplência não é um fator determinante para a adesão ao depósito a prazo, possivelmente porque os clientes inadimplentes representam uma parcela pequena do dataset.

#### **4. Correlação com a Duração da Chamada (`duration`):**
- A única variável numérica que apresenta correlação significativa com o alvo (`y`) é **`duration`**, que representa a duração da chamada durante o contato com o cliente.
- Observamos que quanto maior a duração da chamada, maior a probabilidade de o cliente adquirir o depósito a prazo.
- **Importante**: Embora exista uma correlação clara entre `duration` e `y`, **correlação não implica causalidade**. Ou seja, a duração da chamada pode ser um indicador de interesse do cliente, mas não necessariamente a causa direta da decisão de adesão.
- Além disso, a variável `duration` é coletada durante a interação com o cliente, o que significa que ela não pode ser usada como preditor em modelos que visam prever o sucesso da campanha antes do contato.

#### **5. Insights Gerais:**
- **Financiamento habitacional e empréstimos pessoais** parecem desempenhar um papel importante no comportamento dos clientes. Clientes sem compromissos financeiros prévios (financiamentos ou empréstimos) são mais propensos a aderir ao depósito a prazo.
- **Inadimplência** não parece ser um fator relevante para explicar a adesão ao produto, indicando que outras variáveis (como saldo médio ou profissão) podem ter maior impacto.
- A **duração da chamada** é um forte indicador de sucesso, mas deve ser interpretada com cautela, considerando sua natureza dependente do contato direto com o cliente.

#### **Próximos Passos:**
- Investigar outras variáveis potencialmente relevantes, como **saldo médio (`balance`)**, **idade (`age`)** e **profissão (`job`)**, para identificar padrões mais robustos.
- Desenvolver modelos preditivos que considerem as variáveis independentes do contato com o cliente (ex.: dados demográficos e financeiros) para prever a probabilidade de adesão ao depósito a prazo.
- Explorar interações entre variáveis, como a combinação de idade e saldo médio, para capturar nuances comportamentais.
