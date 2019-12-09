# Mappings
Spring mappings

One department has many employees

Table-department
id,name,description

Table-employee
id,name,email,address,dept_id

INNER JOIN
SELECT d.name, e.name, e.email, e.address FROM department d INNER JOIN employee e ON d.id = e.dept_id;

LEFT JOIN/LEFT OUTER JOIN
SELECT d.name, e.name, e.email, e.address FROM department d LEFT JOIN employee e ON d.id = e.dept_id;

RIGHT JOIN/RIGHT OUTER JOIN
SELECT d.name, e.name, e.email, e.address FROM department d RIGHT JOIN employee e ON d.id = e.dept_id;


{
    "title" : "Post 2",
    "description" : "Post 2 description",
    "content" : "Post 2 content"
    
}

{
    "text" : "Nice Post"
    
}

Links
inner joins
https://www.roytuts.com/spring-boot-data-jpa-left-right-inner-and-cross-join-examples/

join types
https://www.baeldung.com/jpa-join-types

data jpa @query
https://www.baeldung.com/spring-data-jpa-query

one to many mappings
https://www.callicoder.com/hibernate-spring-boot-jpa-one-to-many-mapping-example/
https://www.baeldung.com/spring-data-jpa-query

many to many mappings
https://www.callicoder.com/hibernate-spring-boot-jpa-many-to-many-mapping-example/
