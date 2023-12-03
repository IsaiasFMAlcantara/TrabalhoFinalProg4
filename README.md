# Escola de Música
### Alunos
- Gabriel Nascimento
- Isaías Félix
- Murilo José
- Thauan Felipe
***
### Requisitos trabalho final `programação IV`
O trabalho consiste em criar uma aplicação web utilizando o framework Django e deverá conter os seguintes itens:
1. [x] O sistema deverá ter no mínimo dois níveis de usuários e deverá haver páginas que vão ser acessíveis a um determinado tipo de usuário.
1. [ ] O sistema deverá gerar pelo menos uma relação em PDF.
1. [ ] O sistema deverá gerar pelo menos uma aplicação de AJAX.
1. [x] O sistema deverá ter um visual agradável para os usuários.
1. [ ] O sistema deve estar disponível em pelo menos mais um idioma.
1. [x] O sistema deve permitir interação dos usuários, seja para se cadastrar no site, seja para mudar o visual do sistema, ou outra interação pertinente.
1. [ ] O sistema deve se preocupar com a acessibilidade (principalmente para deficientes visuais).
***
### Sobre a atividade
Este é um projeto de um sistema web desenvolvido em Django e Bootstrap/HTML, criado para gerenciar orquestras, músicos, instrumentos, apresentações, sinfonias e suas respectivas associações.
### Funcionalidades
- Adicionar, visualizar, editar e excluir instrumentos musicais, atribuindo um músico para utiliza-lo temporariamente.
- Gerenciar músicos, incluindo a associação com um instrumento específico.
- Registrar e gerenciar apresentações musicais, incluindo a data e hora.
- Criar sinfonias e associá-las ao seu compositor.
- Gerenciar orquestras, incluindo a adição e remoção de músicos, apresentações e sinfonias.
***
### Tecnologias Utilizadas
- Django: Framework web em Python para o desenvolvimento do backend.
- Bootstrap/HTML: Utilizados para criar o frontend responsivo e amigável ao usuário.
***
### Permissões
- O sistema foi planejado com algumas permissões específicas para cada usuário.
***
### Super usuário
Usuário: admin  
Senha: admin
### Usuario de teste
Usuário: teste-usuario  
Senha: alunoifro
### Usuario de professor
Usuário: teste-professor  
Senha: alunoifro
### Usuário comum
O usuário comum é aquele que cria sua conta pela inteface de login do site. Todo usuário criado pela interface do site por padrão possui as permissões de usuário comum.   
Este usuário tem permissão para realizar o CRUD completo nas seguintes models:

- Apresentação
- Instrumento
- Orquestra

Para as outras duas models (Músicos e Sinfonias), este usuário só tem permissão de visualização.
***
### Configuração do Ambiente
1. Criar virtual env 
```sh
python -m venv env
```
2. Criar virtual env 
```sh
pip install -r requirements.txt
```
3. Arquivo requirements
```txt
asgiref==3.7.2
Django==4.2.2
django-crispy-forms==2.0
django-jazzmin==2.6.0
sqlparse==0.4.4
tzdata==2023.3
```
4. Criar virtual env 
```sh
python manage.py runserver
```
Acesse o sistema através do URL [http://localhost:8000/](http://localhost:8000/).
***
### Desenvolvimento - Atividades a serem realizadas
- Models
    - [x] Criar o modelo Instrumento.
    - [x] Criar o modelo Musico.
    - [x] Criar o modelo Apresentacao.
    - [x] Criar o modelo Sinfonia.
    - [x] Criar o modelo Orquestra.
- Instrumentos
    - [x] Implementar views para adicionar, visualizar, editar e excluir instrumentos.
    - [x] Configurar as URLs correspondentes para as views de instrumentos.
- Músicos
    - [x] Implementar views para adicionar, visualizar, editar e excluir músicos.
    - [x] Configurar as URLs correspondentes para as views de músicos.
- Apresentações
    - [x] Implementar views para adicionar, visualizar, editar e excluir apresentações.
    - [x] Configurar as URLs correspondentes para as views de apresentações.
- Sinfonias
    - [x] Implementar views para adicionar, visualizar, editar e excluir sinfonias.
    - [x] Configurar as URLs correspondentes para as views de sinfonias.
- Orquestras
    - [x] Implementar views para adicionar, visualizar, editar e excluir orquestras.
    - [x] Configurar as URLs correspondentes para as views de orquestras.
***
### Contribuição
Se você deseja contribuir para o projeto, siga as etapas abaixo:
1. Faça um fork do repositório.
2. Crie uma branch para a sua feature (`git checkout -b feature/nome-da-feature`).
3. Implemente as alterações.
4. Faça o commit das suas alterações (`git commit -m 'Adiciona uma nova feature'`).
5. Faça o push para a branch (`git push origin feature/nome-da-feature`).
6. Abra um Pull Request.
