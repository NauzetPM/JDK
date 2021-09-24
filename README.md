# JDK
Repositorio dedicado a la documentacion de la instalación de OpenJdk en Ubuntu

## ÍNDICE

-actualizar el sistema

-instalación de java

-instalación de versión específica




1ºEmpezamos actualizando el sistema con el comando:sudo apt-get update![1](https://user-images.githubusercontent.com/91209288/134735561-5b6f070c-5b4a-437e-89bd-f859f55c3abe.PNG)

2º Instalamos java con el comando:sudo apt-get install default-jdk![2](https://user-images.githubusercontent.com/91209288/134735632-1934f39b-86db-41df-8f97-7954844e2ec2.PNG)
![2 1](https://user-images.githubusercontent.com/91209288/134735641-a2394319-4acc-4a39-b9ff-d355be222297.PNG)

3ºVerificamos que se instalo correctamente con el comando:java --version
![3](https://user-images.githubusercontent.com/91209288/134735700-2acfb90d-c01d-425b-83b7-58fe32b5f147.PNG)

4ºPara Instalar una versión concreta (La 9) utilizaremos este comando:sudo apt install
openjdk-9-jdkAunque depende de la versión del sistema que tengas no te servirá.

![4](https://user-images.githubusercontent.com/91209288/134735944-520ddcec-0ff1-497c-b5bb-20bb568912ca.PNG)

5º Para Instalar una versión concreta (La 8) utilizaremos este comando:sudo apt install
openjdk-8-jdk![5](https://user-images.githubusercontent.com/91209288/134735981-1bf40357-cb42-4c49-a078-cfcae64da604.PNG)

6ºVerificamos que versión es la que tenemos en este caso la 8 que es la que utilizaremos
con el comando:java --version![6](https://user-images.githubusercontent.com/91209288/134736019-10f1305d-e99c-4069-b70b-21d80bb11b2a.PNG)
