#FAZENDO AUTENTICAÇÃO COM OAUTH 2.0

<p>1- Para começar a autenticação utilizando o OAuth primeiramente temos que criar as nossas credenciais no cloud https://console.cloud.google.com/</p>
2- Depois das credenciais criadas, criei um novo projeto no pycharm, instalei as bibliotecas necessárias:

*pip install django-allauth*

3- Instalei o django, criei uma virtual venv e depois dei início ao meu projeto fazendo as configurações necessárias, 
criei um index.html e um login.html bem simples só para facilitar o entendimento utilizando html e interface de bootstrap.

4- Depois são necessárias algumas configurações no /admin e em social accounts, onde adicionamos uma nova conta e inserimos as credencias que foram 
criadas no cloud, assim por fim criei uma aplicação web para poder realizar a autenticação do usuário utilizando o gmail pela API do OAuth2.

5- E Para melhor entendimento seguem imagens da tela do projeto:


not login
![naologado](https://github.com/karendiz/DesenvCompDist/blob/main/OAuth2.0/naologado1.jpg)

config social account 
![configaccount](https://github.com/karendiz/DesenvCompDist/blob/main/OAuth2.0/configaccount.jpg)

login page
![loginpage](https://github.com/karendiz/DesenvCompDist/blob/main/OAuth2.0/loginpage.jpg)

loging sucess with gmail
![logadogmail](https://github.com/karendiz/DesenvCompDist/blob/main/OAuth2.0/logadogmail.jpg)
