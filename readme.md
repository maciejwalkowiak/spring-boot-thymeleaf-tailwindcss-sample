# Spring Boot + Thymeleaf + TailwindCSS Sample

Follow tutorial 👉 [http://maciejwalkowiak.com/blog/spring-boot-thymeleaf-tailwindcss](http://maciejwalkowiak.com/blog/spring-boot-thymeleaf-tailwindcss)

CSS file is located in `src/main/frontend/main.css`.

Building the project:

```bash
$ ./mvnw package
```

To run in dev mode:

```bash
$ ./mvnw paseq:exec
```

Live reloading the browser without needing to refresh it possible with [Live Reload Extension](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei/related).

Look into `pom.xml` for `paseq-maven-plugin` configuration to understand how it works.
