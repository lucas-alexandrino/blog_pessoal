# Blog Pessoal
Este é o repositório do back-end do Blog Pessoal. Aqui, utilizei o framework Spring Boot para criar uma API REST que permite a interação do front-end com um banco de dados MySQL. O MySQL é responsável por armazenar todas as informações do blog, incluindo postagens, temas e usuários

# Configuração do Ambiente
Certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:
<ul>
<li> Java Development Kit (JDK) 8 ou superior
<li> Spring Boot
<li> MySQL
  <li> IDE de sua preferência (recomendo o uso do IntelliJ ou Eclipse) </li>
</ul>

# Instruções de Instalação
<ol> 
  <li>Clone este repositório em sua máquina local utilizando o seguinte comando: </li>
  
``` 
 git clone https://github.com/lucas-alexandrino/blog_pessoal.git
``` 

<li>Abra sua IDE e importe o projeto.</li>

<li>Configure as propriedades do banco de dados MySQL no arquivo application.properties. Certifique-se de fornecer as informações corretas de conexão com o banco de dados, como URL, nome de usuário e senha. </li>

<li>Execute o projeto através da IDE ou utilize o seguinte comando no diretório raiz do projeto:

  
  ``` 
./mvnw spring-boot:run
  ``` 
<li>A API estará disponível no seguinte endereço: http://localhost:8080
  
  </ol>

# Endpoints da API
A API REST do Blog Pessoal fornece os seguintes endpoints principais:
<ul>
<li> /api/postagens: Endpoints relacionados às postagens do blog.
<li> /api/temas: Endpoints relacionados aos temas das postagens.
<li> /api/usuarios: Endpoints relacionados aos comentários das postagens. </li>
</ul>
Para obter mais detalhes sobre os endpoints disponíveis e os dados esperados, consulte a documentação da API.

# Contato
Se tiver alguma dúvida ou sugestão relacionada a este projeto, pode entrar em contato comigo através do email lucas.alexcontato@gmail.com

Agradeço seu interesse no Blog Pessoal. Espero que este projeto seja útil e inspire outros desenvolvedores a criar seus próprios blogs pessoais!
