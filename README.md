# api-scaffolding-initializer-for-node-js-projects
It is a template scaffolding repository, which have a specific organization of folders and resource disposition using the clean and hexagonal architecture principals to build a application programming interface
(API) using the Javascript technologies. It allow organize and manage the code resources using the next folder tree:
  
+ node-modules [Node js packages]
+ build [builded and boundle source code app]
  + app.js 
+ app [All API source code]
  + configs [Config global project properties files]
    + app-config.js
    + databases-config
      + postgresql-config.js
  + domains [Data representation folder]
    + main-domain.js [Object builder reference and manage the entitie and her dtos]
    + entities
      + main-entitie.js
    + dtos
      + main-dto.js
  + services [Specific logic behavior]
    + main-service.js
    + managers [Persistence administrator to domain]
      + main-manager.js
  + server [Server content]
    + app-server.js [Server source code]
    + endpoints [Endpoints]
      + routers [All API routs]
        + main-router.js
      + controllers [All API routs bussines logic]
        + main-controller.js
  + utils [Utilitari logic]
    + main-util.js
    + middlewares
      + main-middleware.js
  + unittests [Unit test project]
    + domain-test
      + main-domain-test.js
    + services-tests
      + main-service-test.js
    + server-test
        + main-endpoint-test.js 
    + utils-tests
      + main-util-tests.js
      +  middlewares-test
        + main-middleware-test.js 
  + web [web folders]
    + styles
      + main-style.css
    + pages
      + main-page.html      
+ statics [Static files]
  + images
    + main-image.(png,jpeg,etc...)
+ readme.md
+ .gitignore
+ .env
+ package.json
+ package-lok.json
+ Dockerfile
+ docker-compose.yml
