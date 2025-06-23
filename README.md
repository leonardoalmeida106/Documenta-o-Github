# Documenta-o-Github

**Documentação Final do Projeto - MedFlux (Sprint 3)**

---

### 1. Contexto do Problema

O sistema público e privado de saúde no Brasil enfrenta desafios recorrentes relacionados à gestão de filas de atendimento, organização de pacientes e agilidade na coleta de dados. Muitos pacientes aguardam horas por um atendimento médico devido à falta de um controle eficiente de fluxo. Essa ineficiência afeta especialmente idosos, pacientes com doenças crônicas e profissionais de saúde, resultando em atrasos, estresse e comprometimento do atendimento. De acordo com dados do IBGE (2023), mais de 30% da população depende exclusivamente do SUS, o que agrava o problema em regiões com alta demanda e pouca infraestrutura.

---

### 2. Objetivo do Projeto

**Objetivo Geral:**
Desenvolver uma solução web para gerenciar filas de atendimento médico, organizando o fluxo entre pacientes, profissionais de saúde e unidades hospitalares.

**Objetivos Específicos:**

* Permitir o cadastro e login de pacientes e profissionais.
* Disponibilizar a visualização de hospitais conveniados e suas filas.
* Gerenciar fichas de atendimento com inserção de dados clínicos.
* Emitir relatórios de evolução e atendimento.
* Oferecer uma interface intuitiva e responsiva.

---

### 3. Justificativa

A ausência de um sistema de triagem digital compromete a eficiência do atendimento médico. Questionários realizados com 20 pacientes em uma UBS local revelaram que 80% deles consideram o processo de espera confuso e demorado. Além disso, profissionais relataram dificuldades na recuperação de informações médicas básicas dos pacientes. Por isso, propomos uma solução integrada e automatizada.

---

### 4. Público-Alvo

* **Pacientes** entre 18 e 70 anos, com dificuldade de acesso a informações de atendimento, especialmente os que dependem do SUS.
* **Profissionais de saúde**, como médicos e enfermeiros, atuando em hospitais públicos e privados.
* **Localização**: Regiões urbanas com alta demanda de atendimentos.
* **Escolaridade**: Ensino médio ou superior completo.

---

### 5. Processo de Design Thinking

**Empatia:** Realizamos entrevistas com pacientes e profissionais.

**Definição:** Criamos um mapa de empatia e identificamos as principais dores dos usuários.

**Ideia:** Brainstorm para listar soluções. Selecionamos o gerenciamento de filas online com relatórios automatizados.

**Protótipo:** Desenvolvemos wireframes das principais telas.

**Validação:** Feedback dos usuários orientou ajustes na interface.

---

### 6. Histórias de Usuários

1. Como paciente, quero ver os hospitais conveniados para saber onde posso ser atendido.
2. Como paciente, quero me cadastrar e logar no sistema para acessar meu histórico.
3. Como profissional de saúde, quero cadastrar uma ficha de atendimento para registrar o caso do paciente.
4. Como administrador, quero cadastrar hospitais para manter a base de dados atualizada.
5. Como médico, quero visualizar relatórios de pacientes para acompanhar sua evolução.
6. Como paciente, quero consultar minha posição na fila online para evitar espera excessiva.

---

### 7. Requisitos

**Funcionais:**

* RF01: Cadastro de pacientes
* RF02: Login de usuários
* RF03: Cadastro de hospitais
* RF04: Visualização de filas por hospital
* RF05: Cadastro de ficha de atendimento
* RF06: Consulta de relatórios
* RF07: Atualização de dados do paciente
* RF08: Consulta à evolução clínica
* RF09: Visualização de relatório estatístico
* RF10: Remoção de pacientes da fila

**Não Funcionais:**

* RNF01: Sistema responsivo para dispositivos móveis
* RNF02: Dados criptografados para segurança

**Restrições:**

* REST01: A solução deverá funcionar com base em arquivos JSON
* REST02: Interface desenvolvida em HTML, CSS e JS puro

---

### 8. Wireframes

Wireframes desenvolvidos no Figma mostrando:

* Tela de login
* Tela de cadastro
* Dashboard do profissional
* Consulta de hospitais
* Cadastro de fichas

---

### 9. Protótipo Interativo

Protótipo navegável hospedado no Figma com fluxo entre todas as telas citadas acima.

---

### 10. Metodologia

* **Metodologia ágil SCRUM** com entregas em sprints.
* Divisão de tarefas em Kanban (GitHub Projects).
* Ferramentas: GitHub, Figma, VSCode, Trello, Google Docs.
* Papéis: Devs, Designer, Documentador, Scrum Master.

---

### 11. Solução Implementada

* Sistema web com login de usuário.
* Cadastro de hospitais e visualização de filas.
* Cadastro de fichas de atendimento com JSON.
* Relatórios em HTML com dados dos atendimentos.

---

### 12. Plano de Testes

**Testes Funcionais:**

1. Cadastro de paciente com dados válidos
2. Login com credenciais corretas
3. Cadastro de hospital
4. Visualização de hospitais
5. Cadastro de ficha médica
6. Visualização de relatório
7. Remoção de paciente da fila
8. Atualização de dados do paciente

**Testes Não Funcionais:**

1. Verificar responsividade em diferentes resoluções
2. Verificar armazenamento seguro dos dados no JSON

---

### 13. Registro de Testes

* Screenshots dos testes funcionais
* Relatório com resultado de cada caso
* Problemas encontrados e respectivas soluções

---

### 14. Qualidade e Linguagem

Todo o texto foi escrito com linguagem clara, objetiva, uso apropriado de termos técnicos e sem informalismos. Foram utilizadas referências confiáveis na construção da justificativa e objetivos.

---

### 15. Conclusão

O projeto MedFlux demonstra uma solução viável, funcional e alinhada com as necessidades reais do sistema de saúde. A implementação da ferramenta permite maior eficiência, controle de dados e agilidade no atendimento, promovendo inovação no setor público e privado de saúde.
