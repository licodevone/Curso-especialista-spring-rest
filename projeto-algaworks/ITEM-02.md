# Spring e Injeção de Dependências

> https://app.algaworks.com/aulas/1786/preparando-o-ambiente-de-desenvolvimento-jdk-e-sts-for-eclipse

> https://spring.io/tools

## Ubuntu

### Download e instalação do Java e JDK 

> https://linuxcapable.com/how-to-install-openjdk-17-on-ubuntu-linux/

> https://jdk.java.net/archive/

> https://github.com/algaworks/curso-especialista-spring-rest

## Windows

### Instalação do Java

OpenJDK da Adoptium, é uma implementação da plataforma Java open source e gratuita, pronta para ser usada em produção.

![alt text](image-16.png)

![alt text](image-15.png)

![alt text](image-17.png)

![alt text](image-18.png)

![alt text](image-19.png)

![alt text](image-20.png)

![alt text](image-21.png)

![alt text](image-23.png)

![alt text](image-22.png)

![alt text](image-24.png)

> Variáveis de ambiente criadas automaticamente conforme modificado na imagem 22.png

![alt text](image-25.png)

> Verficação da versão do JRE e JDK

![alt text](image-26.png)

### 2.5. Criando um projeto Spring Boot com Spring Initializr

> Windows -> Preferences -> installed JREs

![alt text](image-27.png)

![alt text](image-28.png)

![alt text](image-29.png)

![alt text](image-30.png)

![alt text](image-31.png)

![alt text](image-32.png)

![alt text](image-33.png)

![alt text](image-5.png)

![alt text](image-34.png)

![alt text](image-35.png)

![alt text](image-36.png)

![alt text](image-37.png)

![alt text](image-4.png)

![alt text](image-6.png)

![alt text](image-7.png)

~~~java
package com.algaworks.algafood;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication
public class AlgafoodApiApplication {

	public static void main(String[] args) {
		SpringApplication.run(AlgafoodApiApplication.class, args);
	}

}

~~~

### Problemas e erros com o projeto

> New -> Mavem -> Update project

![alt text](image-9.png)

![alt text](image-10.png)

![alt text](image-11.png)

### Problemas no POM.xml

![alt text](image-8.png)

> Falta o S para ficar HTTPS

![alt text](image-12.png)

![alt text](image-13.png)

![alt text](image-14.png)

![alt text](image-38.png)

> Acessando o parent herdado no projeto

![alt text](image-60.png)

![alt text](image-61.png)

![alt text](image-62.png)

![alt text](image-63.png)

![alt text](image-64.png)

> https://www.youtube.com/watch?v=bEXzZTKjN88

> https://www.youtube.com/watch?v=iSbmB7ZJ5zw

> Pode ser utilizada a versão 2.7.9
> <version>2.7.9</version>

![alt text](image-39.png)

![alt text](image-40.png)

![alt text](image-41.png)

![alt text](image-42.png)

![alt text](image-43.png)

![alt text](image-44.png)

![alt text](image-45.png)

Maven Gerenciador de bibliotecas Java

![alt text](image-51.png)

> Wrapper possibilita rodar um projeto maven, fazer o build, mesmo não tendo o maven configurado no sistema.

![alt text](image-46.png)

![alt text](image-47.png)

### Como empacotar o projeto

![alt text](image-48.png)

![alt text](image-49.png)

![alt text](image-50.png)

![alt text](image-52.png)

![alt text](image-53.png)

[PACKAGE](../terminal/TERMINAL.md)

> Posso utilizar o arquivo ./nvm para utilizar o Maven no terminal

```sh
.\mvnw package
```

![alt text](image-54.png)

![alt text](image-55.png)

![alt text](image-56.png)

Rodar o projeto pelo terminal

[RUN](../terminal/TERMINAL.md)

![alt text](image-58.png)

![alt text](image-59.png)

### Instalação de bibliotecas no POM.xml de maneira gráfica

![alt text](image.png)

![alt text](image-69.png)

![alt text](image-1.png)

> Problemas com o parent 2.7.18 então fui para o 3.3.4

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-65.png)

![alt text](image-66.png)

![alt text](image-67.png)

![alt text](image-68.png)

# Criando um controller com Spring MVC

# Criar uma classe Java

![alt text](image-13.png)

![alt text](image-14.png)

![alt text](image-15.png)

~~~~java
package com.algaworks.algafood;

import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.ResponseBody;

@Controller
public class PrimeiroController {

	@GetMapping("/hello")
	@ResponseBody
	private String hello() {
		return "Hello World!";
	}
}

~~~~

![alt text](image-17.png)

![alt text](image-18.png)

> Acessar a url: http://localhost:8080/hello

![alt text](image-19.png)

# Restart mais rápido da aplicação com DevTools

O Java Class Loader, parte do Java Runtime Environment, carrega dinamicamente classes Java na Java Virtual Machine. Ele reinicia apenas parte do programa que foi modificado facilitando e agilizando a criação de projetos Spring.

![alt text](image-70.png)

![alt text](image-71.png)

# O que é injeção de dependências-IOC(Inversion of Control)?


# Representação de pacotes

![alt text](image-72.png)






































