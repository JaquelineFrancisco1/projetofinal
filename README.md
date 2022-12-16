# projetofinal
<h1 align="center">
    <br>
    <p align="center">Rede de ajuda: Mães em Ação<p>
</h1.>
<p align="justify"> Bem vindos, ao meu projeto! Sinta-se a vontade para entrar nessa jornada transformadora, ele foi desenvolvido para a conclusão do curso "Todas em Tech" da {reprograma}.

#  🔐JUSTIFICATIVA:

<p align="justificar">
Baseado na minha realidade atual,ser mãe solo, me fez perceber que precisamos de apoio e acolimento, pois todos os dias é necessario matar um leão por dia para dar conta de tudo,
nem sempre é uma tarefa facíl, ser mãe é literalemente padecer no paraíso, ao longo desse período, percebi a dificuldade de conseguir uma recolocação no mercado de trabalho,
partindo desse principio entendi a necessidade de buscar qualificações para me adquar e assim alcançar um vaga de emprego ,
onde eu consiga dar continuidade ao sustento da minha família. 

<p align="justificar">
Na maioria dos casos falta informação para que essa mães consigam se qualificar e consiguir uma vaga de emprego, essa rede de apoio nasceu para dar suporte á essas mães negras, interioranas e periféricas.
que necessitam de uma coloção para manter o sustento da sua Familía.

##  🔑 SOBRE A API:

<p align="justificar">
O projeto "Rede de Ajuda: Mães em Ação" é voltado para mulheres que fazem parte da população em vulnerabilidade financeira que,
atualmente estão sem emprego fixo, com beneficios que agregam na sua renda mensal.Empresas terão acesso a plataforma para buscar,
por essas mães oferecendo oportunidades de trabalho e qualificações profissionais de forma gratuita.
Sendo assim ela é dividida em duas partes:

 -  **Empresas** : um espaço de consulta e cadastro de mães desempregadas.
 -  **Cursos** : Serão disponibilizados cursos em diversas aréas de atuação dentro do mercado , até mesmo para primeiro emprego.
 
 ##  ⚙🛠 FUNCIONALIDADES:

- Listar todos as Mães da API;
- Listar Cursos Profissionalizantes por meio de filtros;
- Cadastro, atualização e exclusão de Mães;
- Criação, atualização e exclusão de Cursos;
- Listar todas as Mães da API;
- Gerar informações de Cursos.

##  📚 MÉTODOS:
<p align="justificar">
Desenvolvida utilizando JavaScript e Node.js, uma API conta com dois CRUDs completos que respeitam princípios de SOLID e Clean Code. Usando a conexão com bando de dados MongoDB e as rotas foram testes no Insomnia.

##  📂 ARQUITETURA MVC
```
📁PROJETO FINAL
   |
   |- 📁 ativos
   |- 📁 src
   | |
   | |- 📁 controladores
   | |- 📑 maesController.js
   | |- 📑 cursosController.js
   |
   | |- 📁 banco de dados
   | |- 📑 mongoConfig.js
   |
   | |- 📁 modelos
   | |- 📑MaesSchema.js
   | |- 📑CursosSchema.js
   |
   | |- 📁 rotas
   | |- 📑indexRoutes.js
   | |- 📑maesRoutes.js
   | |- 📑cursosRoutes.js
   |
   | |- 📑 app.js
   | |- 📑 swagger.json
   |
   |
   |- 📑 .env
   |- 📑 .env.exemplo
   |- 📑 .gitignore
   |- 📑 package-lock.json
   |- 📑 package.json
   |- 📑Procfile
   |- 📑 README.me
   |- 📑 server.js
    
    ##  💻 TECNOLOGIAS E PACOTES UTILIZADOS:


**TECNOLOGIAS**

- [ Git/GitHub ](https://github.com/)
- [ Versel ](https://www.versel.com)
- [ Javascript ](https://www.javascript.com/)
- [ MongoDB Atlas ](https://www.mongodb.com/cloud/atlas)
- [ Node.js ](https://nodejs.org/en/)
- [ Insomnia ](https://www.isomnia.com/apps)
- [ VScode ](https://code.visualstudio.com/)  

###  PACOTES


- [ Cors ](https://www.npmjs.com/package/cors)
- [ Dotenv-safe ](https://www.npmjs.com/package/dotenv)
- [ Expresso ](https://expressjs.com/pt-br/)
- [ Mangusto ](https://mongoosejs.com/)
- [ Nodemon ](https://www.npmjs.com/package/nodemon)
- [ Swagger ](https://www.npmjs.com/package/swagger-ui-express)


#  🔃 ROTAS


##  🔃 ROTA INDEX E SWAGGER

| Método HTTP | ponto final | Descrição |
| ------------ | ----------------------- | ------------------------------------ |
| OBTER | `http://localhost:PORT/` | Apresentação do projeto | |


##  🔃 ROTAS - MAES

| Método HTTP | ponto final | Descrição |
| ------------ | --------------------- | ------------------------------------------ |
| OBTER | `/maes/pesquisa` | Lista de todasas Maes cadastrados |
| OBTER | `/maes/search/:id` | Filtrar maes pelo ID |
| POST | `/maes/criar` | Cadastro das Maes |
| COLOCAR | `/maes/buscar/:Id` | Buscar por maes Cadastradas |
| APAGAR | `maes/excluir/:id` | Excluir um cadastro por ID |


    
##  🔃 ROTAS - CURSOS

| Método HTTP | ponto final | Descrição |
| ------------ | --------------------- | ------------------------------------------ |
| OBTER | `/cursos/pesquisa` | Lista de todos os cursos cadastrados |
| OBTER | `/cursos/search/:id` | Filtrar os profissionais pelo ID |
| POST | `/cursos/criar` | Cadastro dos cursos |
| COLOCAR | `/cursos/buscar/:Id` | Buscar por cursos Cadastrados |
| APAGAR | `cursos/excluir/:id` | Excluir um cadastro por ID |
         


##  🛑​ PARA REALIZAR A INSTALAÇÃO NO SEU COMPUTADOR:



1. Primeiro é necessário clonar o seguinte repositório:

    ```bash
    $ git clone https://github.com/https://github.com/JaquelineFrancisco1/projetofinal/
     ```

2. Entre na seguinte massa:

    ```bash
    $ cd PROJETO-FINAL/
    ```
    
3. Para ansiosos, é necessário baixas as dependências:

   ```bash
    instalação de $npm
    ```
4. Inicie o projeto com o comando:

   ```bash
    $ npm executar dev
    ```   

<br>

---



#  ✔️VISUALIZAÇÃO E FUNCIONAMENTO:


<br>

> Cadastrando uma Mãe
<div alinhar = "centro">
<img src='./assets/mae_post.gif'>
</div>
<br>


<br>

> Listando todas as mães cadastrados
<div alinhar = "centro">
<img src='./assets/mae_getAll.gif'>
</div>
<br>
<br>

> Filtrando pela ocupação:
<div alinhar = "centro">
<img src='./assets/mae_getByOccupation.gif'>
</div>
<br>
<br>

> Filtrando pelo curso:
<div alinhar = "centro">
<img src='./assets/cursogetByGender.gif'>
</div>
<br>
<br>


> Encontrando por ID:
<div alinhar = "centro">
<img src='./assets/maes_getById.gif'>
</div>
<br>
<br>

> Atualizando o cadastro de uma Mãe:
<div alinhar = "centro">
<img src='./assets/maes_put.gif'>
</div>
<br>
<br>

> Excluindo o cadastro de uma mae:
<div alinhar = "centro">
<img src='./assets/mae_delete.gif'>
</div>
<br>
<br>

> Cadastrando curso:
<div alinhar = "centro">
<img src='./assets/cursos_post.gif'>
</div>
<br>
<br>

> Listando todos os cursos cadastrados:
<div alinhar = "centro">
<img src='./assets/cursos_getAll.gif'>
</div>
<br>
<br>

> Selecionando um curso aleatório do banco de dados:
<div alinhar = "centro">
<img src='./assets/cursos_random.gif'>
</div>
<br>

> Selecionando por ID:
<div alinhar = "centro">
<img src='./assets/cursos_getById.gif'>
</div>
<br>
<br>

> Atualizando curso:
<div alinhar = "centro">
<img src='./assets/cursos_put.gif'>
</div>
<br>
<br>

> Excluindo um curso por ID:
<div alinhar = "centro">
<img src='./assets/curso_delete.gif'>
</div>
<br>

##  🏗️ IMPLEMENTAÇÕES FUTURAS:

* ⬛ Desenvolvedor um front-end;
* ⬛ Adaptar a API para um formato de APP;
* ⬛ Implementar cadastramento, autenticação de Novos Cursos;
* ⬛ Implementar espaço para compartilhamento de experiências entre as mães;
* ⬛ Implementar espaço para dicas de como melhorar seu CV;


##   👩 SOBRE A AUTORA:


|Autora|Vivência|
|:------:|----|
|  Me chamo Jaqueline Francisco ,Paulista, mulher negra, mãe solo de 2 filhos, tenho 34 anos, sou libriana raiz, RESILIENTE por natureza, formada em Recursos Humanos em transição de carreia ,
para  desenvolvedora Back-end. Minha atual realidade de ser mãe solo após um termino,
de um relacionamento de 20 anos, onde foi necessário abrir mão de todos os meus bens, matérias construídos nesse relacionamento, recomecei do zero, vendo a necessidade de 
me superar todos os dias para dar o melhor aos meus filhos , perdi minha colocação no, 
mercado durante o período da pandemia, entendi a necessidade de buscar, mais conhecimentos e aprendizado para conseguir uma vaga de emprego , A {reprograma} foi essencial nessa jornada por me mostrar,
que as barreiras entre as mulheres e a tecnologia são criadas e sustentadas pelo patriarcado, porém juntas podem diminuí-las e possibilitar as mulheres de diversos contextos mudarem sua própria história. 


##   ✨ CONTATO:

<div>
<a href="https://instagram.com/jaque.ffrancisco" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the- badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href = "mailto:jaquelinetatiane25@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alvo ="_blank"></a>
<a href="https://www.linkedin.com/in/jaqueline-frederico-474484136/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-% 230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>


