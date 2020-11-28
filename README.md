<h1>Projeto desenvolvido durante bootcamp Digital Innovation One e Everis Brasil - Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot </h1>


<h3>Projeto desenvolvido em JAVA 11</h3>


<h3>Para acessar o projeto seguir os passos:</h3>

   <ol> 
    <li> Clonar o repositório </li>
    <li> No terminal digite o comando: mvn spring-boot:run </li>
    <li> O projeto poderá ser visualizado pelo endereço: http://localhost:8080/api/v1/people</li>
  </ol>
  
  
  <h3> Projeto disponível na nuvem, para acessar: </h2>
   <ol> 
    <li> Acessar: https://peopleapi-everis.herokuapp.com/api/v1/people </li>
    <li> Para realizar o teste deve ser feito uma operação POST usando (Postman ou Insomnia) para o endeço acima com JSON no formato abaixo</li>
  <ul> 
    <li>{</br>
      "firstName": "Silvino",</br>
	    "lastName": "Cardoso",</br>
    	"cpf": "053.538.269-30",</br>
    	"birthDate": "30-01-1987",</br>
      "phones":[</br>
	  	{</br>
			"type":"MOBILE",</br>
			"number":"(47)999233389"</br>
		}</br>
    ]}
	}  
  </li> 
  </ul>
  </ol>
