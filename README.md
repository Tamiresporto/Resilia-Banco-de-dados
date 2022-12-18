# Resilia-Banco-de-dados
<h2>Projeto de Modelagem de Banco de dados da empresa Resilia<h2>

<h5><i>Neste projeto está sendo utilizado o modelo Relacional, a imagem mostra várias tabelas ligadas entre si, um banco de dados da Resilia que oferece cursos de Programação para desenvolvimento voltado ao mercado de trabalho.
Representação gráfica de um modelo relacional de dados.<i><h5>

![Projeto-Resilia (1)](https://user-images.githubusercontent.com/112409145/207366723-ef5f80b1-a6f3-4c72-83fe-d962c365ab87.jpg)

  <hr>
<h4>Projeto foi desenvolvido com sete entidades: Alunos, Turmas, Avaliação, Facilitadores, Cursos, Disciplinas e Matrícula.
  
![Projeto-Resilia (10)](https://user-images.githubusercontent.com/112409145/207607901-13f5c931-58b9-48e2-9b6e-c401653367af.jpg)
  
![Projeto-Resilia (11)](https://user-images.githubusercontent.com/112409145/207608111-b3df3ad1-8cbe-45fc-9d6f-d92a1e0a4264.jpg)
  
![Projeto-Resilia (13)](https://user-images.githubusercontent.com/112409145/207608491-3bfdde8d-a71f-4373-ba3c-4cc03501a675.jpg)
  
![Projeto-Resilia (14)](https://user-images.githubusercontent.com/112409145/207608706-f2ae0c09-1cbb-411f-90b4-5030fc72a9fe.jpg)
  
  ![Projeto-Resilia (7)](https://user-images.githubusercontent.com/112409145/207605969-4404be33-45ac-4e7f-9b50-27e61de390ad.jpg)
  
  ![Projeto-Resilia (8)](https://user-images.githubusercontent.com/112409145/207606133-094d87cf-7954-452d-9e6a-6f7fb74f28a5.jpg)
  
  <hr>
  
![Projeto-Resilia (15)](https://user-images.githubusercontent.com/112409145/207608857-36513f62-5a7b-45c3-a64b-b44e5e603e18.jpg)
  
<h4>A entidade alunos teve campos preenchidos com tipos CPF, RG e Email, com o objetivo de identificar os alunos, que também podem ser chaves primárias por ser algo único e trazer autenticação para o banco de dados. <h4>
  
  ![Projeto-Resilia](https://user-images.githubusercontent.com/112409145/207604599-dba53d44-8255-4e2d-8cab-348fa3c37b0d.jpg)
  
  <hr>

  <h4> Quando os atributos de uma entidade formam o atributo de outra, podermos dizer que existem uma referenciação entre as entidades. O mesmo ocorrerá com relação à entidade Alunos. Pelo simples fato de existir esta referência de uma entidade em outra, temos então o que chamamos de RELACIONAMENTO. <h4>
    
    
 ![Projeto-Resilia (16)](https://user-images.githubusercontent.com/112409145/207610200-e7ac42c4-724d-4a23-a4e8-f21713f52b11.jpg)

 <h4>O start da modelagem se dá a partir das ENTIDADES. Uma entidade é uma representação de um conjunto de informações sobre determinado conceito do sistema. Neste começo, temos o nosso Diagrama de Entidade-Relacionamento:
Entidades: Alunos, Avaliações, Turmas
Relacionamentos: Alunos - Avaliações, Avaliação - Turmas. 
   
   ![Projeto-Resilia (17)](https://user-images.githubusercontent.com/112409145/207613240-10bb79c1-db23-43f9-9a50-53db5ea5989e.jpg)

   Determinados os relacionamentos, temos que verificar o número de referências de uma entidade em outra, ou seja, agora vamos verificar a CARDINALIDADE dos relacionamentos. Vejamos as possibilidades:

Relacionamento Um-Para-Um (1:1) - Uma instância da entidade A relaciona-se a uma instância da entidade B <p>
Relacionamento Um-Para-Vários (1:N) - Uma instância da entidade A relaciona-se a várias instâncias da entidade B <p>
Relacionamento Vários-Para-vários (N:M) - Várias instâncias da entidade A relacionam-se a várias instâncias da entidade B <p><h4>
