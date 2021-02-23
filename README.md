# API-Gateway-JWT-Propagation

Following the steps in this article https://medium.com/@hashimati/micronaut-microservices-fundamentals-in-practice-fdf74af2b88f

1. Added UsersService which takes care of user signup based on roles and login. Also includes JWT token Propagation. Runs on port 8888.
2. Added RequestsService which takes care of requests related services. Runs on port 8889.
3. Added OffersService which takes care of offers related services and fetches information from RequestsService. Runs on port 8890.
4. Configured Zuul API gateway to provide interaction between frontend and the above 3 microservices. Runs on port 8080
5. Installed and configured Hashicorp Consul discovery service on local by following this link https://linuxhint.com/install_consul_server_ubuntu/. Runs on port 8500.
6. Included the screenshots of the above 5 microservices running and different APIs tested using Postman in the `screenshots` folder.
