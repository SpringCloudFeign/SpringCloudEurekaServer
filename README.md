1.Apply Annotation @EnableEurekaServer at the main class

2. Modify application.properties file
   
  a)eureka.client.register-with-eureka=false --> this is optional for other microservices/applications to mark as true, but this is Eureka server & make it false
  
  b)eureka.client.fetch-registry=false --> This is used to intearct with other services, here its not required.
