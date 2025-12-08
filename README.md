# Trabalho de Banco de Dados

## 📄 Cenário
Este projeto foi desenvolvido como parte da disciplina de Banco de Dados. O objetivo é aplicar os conceitos de modelagem e manipulação de dados em um cenário fictício de uma **empresa de vendas**, com controle de **Lojas, Clientes, Marcas, Produtos, Compras e Funcionarios**.  

O projeto busca simular um ambiente real de banco de dados, permitindo criar, ler, atualizar e deletar informações (CRUD) e gerar relatórios para análise.

---

## 🏗 Modelagem Conceitual
A modelagem conceitual foi realizada através de um **Diagrama de Entidade-Relacionamento (DER)**, representando as entidades do sistema, seus atributos e os relacionamentos entre elas.  

- **Entidades principais**: Lojas, Clientes, Marcas, Produtos, Compras e Funcionarios 
- **Atributos**: simples, compostos, multivalorados e derivados  
- **Chaves primárias e estrangeiras** definidas para garantir integridade do banco  

<img width="562" height="511" alt="Trabalho final" src="https://github.com/user-attachments/assets/3e356de7-0522-464f-a359-06e84e833010" />


---

## 📝 Modelagem Lógica
A modelagem lógica traduz o DER em **tabelas relacionais** com todos os atributos e tipos de dados definidos.  
- Normalização aplicada para reduzir redundâncias  
- Relacionamentos transformados em **chaves estrangeiras**

<img width="627" height="444" alt="image" src="https://github.com/user-attachments/assets/f7f05483-7959-40a5-87f8-a5a27fa5e644" />


---

## 💾 Modelagem Física
A modelagem física consiste na implementação real do banco de dados no PostgreSQL/Supabase, incluindo:  
- Criação das tabelas com tipos de dados corretos  
- Definição de chaves primárias e estrangeiras  
- Restrições de integridade  

---

## 📊 Dados
O banco de dados foi populado com **dados fictícios** para simular operações reais:  
- 500 clientes  
- 500 Lojas
- 500 Marcas
- 500 Produtos
- 500 Compras
- 500 Funcionarios   

---

## ⚙️ CRUD
Foram realizados **exemplos de operações CRUD** em todas as tabelas:  

- **Create**: inserção de novas Lojas, Clientes, Marcas, Produtos, Compras e Funcionarios 
  <h1>Inserção de dados (INSERT)</h1>
  
  <img width="1349" height="620" alt="img Inserção de dados (INSERT)" src="https://github.com/user-attachments/assets/c8d88ab2-4859-40a5-8e99-c3d2b82be5e1" />

- **Read**: consultas para visualizar dados
  <h1>Leitura de dados (SELECT)</h1>
  
  <img width="1341" height="589" alt="img Leitura de dados (SELECT)" src="https://github.com/user-attachments/assets/4e09a5c0-5bdb-4000-82f3-0d5a29f4cfa3" />

- **Update**: atualização de informações, como preço de produtos e endereço de clientes
 <h1> Atualização de dados (UPDATE)</h1>
  
  <img width="1354" height="626" alt="img Atualização de dados (UPDATE)" src="https://github.com/user-attachments/assets/c62c69ba-ee25-41ff-ace6-d29f7e1a1ace" />

- **Delete**: remoção de registros específicos
 <h1>Exclusão de dados (DELETE)</h1>
  
  <img width="1365" height="631" alt="img Exclusão de dados (DELETE)" src="https://github.com/user-attachments/assets/009ec50f-9875-41a1-b33d-66ba1d96d2fd" />


---

## 📑 Relatórios
Foram criados 10 relatórios básicos utilizando consultas SQL:  



<h1>1:</h1>
<img width="1363" height="600" alt="consulta 1" src="https://github.com/user-attachments/assets/49cfa91b-6756-41b4-a51f-764e1bda89ee" />

<h1>2:</h1>
<img width="1360" height="620" alt="consulta 2" src="https://github.com/user-attachments/assets/ec534153-3568-4362-a039-d960b71dd9e9" />

<h1>3:</h1>
<img width="1365" height="625" alt="consulta 3" src="https://github.com/user-attachments/assets/b3c3fea4-bf85-457c-b740-2516e468c09e" />

<h1>4:</h1>
<img width="1351" height="622" alt="consulta 4" src="https://github.com/user-attachments/assets/09f7b83b-e685-42dd-b5ea-b2557f50b595" />

<h1>5:</h1>
<img width="1364" height="631" alt="consulta 5" src="https://github.com/user-attachments/assets/462f0235-0320-46c0-b532-a8cad0edd2f6" />

<h1>6:</h1>
<img width="1359" height="628" alt="consulta 6" src="https://github.com/user-attachments/assets/4233d3be-2b13-4077-bbb3-0ae8718f1fef" />

<h1>7:</h1>
<img width="1361" height="628" alt="consulta 7" src="https://github.com/user-attachments/assets/2ddab129-1187-4934-98b4-29eafd43f3cc" />

<h1>8:</h1>
<img width="1352" height="596" alt="consulta 8" src="https://github.com/user-attachments/assets/70f3f4de-f6dd-4215-8877-d832f04f3cda" />

<h1>9:</h1>
<img width="1363" height="625" alt="consulta 9" src="https://github.com/user-attachments/assets/3eb5bf12-467d-4679-8367-2df4eb21eb05" />

<h1>10:</h1>
<img width="1365" height="632" alt="consulta 10" src="https://github.com/user-attachments/assets/140d527e-0321-4061-9043-652f42e32734" />


---
