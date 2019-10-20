# scg-demo

	$ mvn clean install
	E mvn spring-boot:run
	$ curl http://localhost:8080/get

	## without fallback 
	$ curl --dump-header - --header 'Host: www.hystrix.com' http://localhost:8080/delay/3
	
	## with fallback
	$ curl --dump-header - --header 'Host: www.hystrix.com' http://localhost:8080/delay/3

