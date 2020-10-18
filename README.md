# spring-boot-h2
Spring Boot and H2 in memory database 

## Certain Endpoints to check:

1. http://localhost:8080/getAllEmployees
sample response:
[
    {
        "id": 1,
        "name": "Abhijeet",
        "dept": "ISE",
        "salary": 98474.0
    },
    {
        "id": 2,
        "name": "Anish",
        "dept": "ISE",
        "salary": 34621.0
    },
    {
        "id": 3,
        "name": "Saraf",
        "dept": "ISE",
        "salary": 70121.0
    },
    {
        "id": 4,
        "name": "Saraf",
        "dept": "ISE",
        "salary": 90212.0
    },
    {
        "id": 5,
        "name": "sahil",
        "dept": "IT",
        "salary": 39212.0
    }
]  

2. http://localhost:8080/saveEmployee -- POST
sample response:
Employee saved..
  
  
3.http://localhost:8080/getEmployee/ISE -- DEPT vise search  {dept}

