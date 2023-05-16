# spring-cloud-config-server

- Will run on port 8888
- git local config repo will have 3 properties files rn limits-service.properties, limits-service-dev.properties, limits-service-qa.properties
- http://localhost:8888/limits-service/defaults will return contents of `limits-service.properties`
- http://localhost:8888/limits-service/qa will return contents of `limits-service-qa.properties`
- <img width="773" alt="Screenshot 2023-05-16 at 1 58 28 PM" src="https://github.com/beinghaziq/spring-cloud-config-server/assets/72576839/8560b9a2-17b6-40c6-92bd-743e419abf3f">
- spring.cloud.config.server.git.uri=file:///Users/dev/Projects/java/git-local-config-repo will be used to connect to git local repo
