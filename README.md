# RedeSocialESN



## BANCO DE DADOS:

### PostgreSQL

Banco de Dados DBRS_USER:
O DBRS_USER é fundamental para o armazenamento e gerenciamento dos dados relacionados aos usuários da nossa rede social. Este banco de dados contém duas tabelas principais:
a. Tabela "usuario": Responsável por armazenar informações cruciais dos usuários, como nome, ID, e outros dados pessoais. Essa tabela é estruturada para garantir a integridade dos dados e otimizar o acesso às informações do usuário.

b. Tabela "amizade": Estabelece as relações entre os usuários, indicando quem são amigos na rede social.
<img width="923" alt="image" src="https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/e9d6f286-e44e-4b3c-ada1-4b6c60b84397">

Banco de Dados DBRS_MSG:
O DBRS_MSG é dedicado ao armazenamento de mensagens recebidas pelos usuários. A abordagem adotada para esse banco de dados visa otimizar o acesso e a recuperação de mensagens específicas para cada usuário. A estrutura envolve:
a. Criação Dinâmica de Tabelas: Logo após o usuário criar uma conta na rede social, o sistema automaticamente cria uma tabela dedicada a esse usuário dentro do DBRS_MSG. Isso permite a segmentação eficiente das mensagens, garantindo um acesso rápido e direto às informações pertinentes a cada usuário.
<img width="472" alt="image" src="https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/b32a9a15-6957-4b8d-a3fd-fd7e32255cd7">




## Diagrama de Classes
<img width="753" alt="image" src="https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/cc1c46cc-5005-4998-888a-8520ab2574ac">

## Testes de imagem do RedeSocial

![image](https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/a5187c0c-c283-4e72-ba31-33f5b352d144)
![image](https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/f7af43ec-b424-4c4d-9750-d6dea0423dea)
![image](https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/5bde0cae-14d0-4648-8544-ead52c3d37d1)
![image](https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/52ec1fbf-7563-470f-a0b8-92fc1433d95b)
![image](https://github.com/NatanaelPimenta/RedeSocialN/assets/143766182/28b43105-d718-4c99-8dd0-feffec6312f2)











