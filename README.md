# springcruddemo


server.port=9099
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/test
spring.datasource.username=root
spring.datasource.password=admin
spring.jpa.show-sql=true
spring.jpa.hibernat.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5InnoDBDialect



{   "id":1,
	"name":"Dinesh",
	"address":"Hyderabad"
}

[
{   "id":2,
	"name":"Kumar",
	"address":"Delhi"
},
{   "id":3,
	"name":"Uday",
	"address":"Mumbai"
}
]

create table employee(id int NOT NULL AUTO_INCREMENT primary key, name varchar(50) not null, address varchar(50) not null);
select * from employee;
truncate table employee;--use this to delete the table record



