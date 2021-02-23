# API-Gateway-JWT-Propagation

Following the steps in this article https://medium.com/@hashimati/micronaut-microservices-fundamentals-in-practice-fdf74af2b88f

1. Added UsersService which takes care of user signup based on roles and login. Also includes JWT token Propagation.
2. Added RequestsService which takes care of requests related services.
3. Added OffersService which takes care of offers related services and fetches information from RequestsService.
4. Configured Zuul API gateway to provide interaction between frontend and the above 3 microservices.
5. Installed and configured Hashicorp Consul discovery service on local by following the link https://linuxhint.com/install_consul_server_ubuntu/
6. Included the screenshots of all the services running and different apis tested using Postman in the `screenshots` folder.
