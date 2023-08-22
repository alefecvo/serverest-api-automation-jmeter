# serverest-api-automation-jmeter

[![Badge ServeRest](https://img.shields.io/badge/API-ServeRest-green)](https://github.com/ServeRest/ServeRest/)


This project is used to performace test using JMeter on site https://serverest.dev/.

The features:
- POST Cadastrar Usuário (the first step to create a new user - not need to use token)
- POST Login (the second step to access the services to create products - generated access token to next service)
- POST Cadastrar Produto (the third step to create new products using token generated)


## Dependencies

#### Install the items

1. Java Development Kit 8 or 11
2. JMeter 5.5

---

## Run Tests:

#### To download, get clone this project to your computer and execute the commands bellow:

1. Open project with JMeter (serveRest.jmx).
2. Run test with compiler or execute commands on terminal.
3. To run test in handless on terminal and generate results and generate dashboard, run the command:

```bash
/Users/YOUR_USER/apache-jmeter-5.5/bin/jmeter -t /Users/YOUR_USER/apache-jmeter-5.5/bin/serveRest.jmx -l /Users/YOUR_USER/apache-jmeter-5.5/bin/results.jtl -e -o /Users/YOUR_USER/apache-jmeter-5.5/bin/results_dash
```

4. To run test with JMeter application on terminal and generate results and generate dashboard, run the command:

```bash
/Users/YOUR_USER/apache-jmeter-5.5/bin/jmeter -n -t /Users/YOUR_USER/apache-jmeter-5.5/bin/serveRest.jmx -l /Users/YOUR_USER/apache-jmeter-5.5/bin/results.jtl -e -o /Users/YOUR_USER/apache-jmeter-5.5/bin/results_dash
```


---


## Prints Tests:

##### 1 - POST Cadastrar Usuário:

![image 01](/performance-api/images/01.png)

![image 02](/performance-api/images/02.png)

##### 2 - POST Login:

![image 03](/performance-api/images/03.png)

![image 04](/performance-api/images/04.png)

##### 3 - POST Cadastrar Produtos:

![image 05](/performance-api/images/05.png)

![image 06](/performance-api/images/06.png)

---


