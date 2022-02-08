# Postgresql JDBC Connection

```java

Connection conn = null;


try {
	Class.forName("org.postgresql.Driver");
	conn.DriverManager.getConnection("jdbc:postgresql://localhost:8072/postgres", "postgres", "password_of_postgres");
	
	if(conn!=null){
	
	System.out.println("Connection successful");
	
	}
	
	else {
	
	System.out.println("Connection failed");
	
	}   
	
	
}

catch (Exception e){
	System.out.println(e);
}

```





