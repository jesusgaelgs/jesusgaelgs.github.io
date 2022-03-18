---
layout: post
title: Starknet
subtitle: Corriendo un nodo en Starknet 
categories: MMA
tags: [Starknet]
---

### Starknet 

Todo comenzó con mi buen amigo JJ Campuzano, que no es mi amigo, pero de tanto que me ha enseñado y de tanto que lo he escuchado siento que somos compitas. Vi el link donde decía que iba a correr su primer nodo en la Starknet ¿?, así mismo me quede, solo sabia que si el iba a correr un nodo yo también tendría que hacerlo y así es como empezó esto. 

![JJ.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1783c984-f347-445a-966b-8fa224df739b/JJ.png)

A continuación hare un copy paste de un tutorial que encontré y como seguí los pasos y donde tuve mis errores. 

Empezamos por donde inicio el hilo, JJ retuiteo a Noa y Noa le da créditos a @zup88, así que, me tendí al perfil de @zup88, el 5 de Marzo publico como empezar a correr tu propio nodo: 

[https://mirror.xyz/0x83857601C1cFA057F2576b343c563BDB9A4C9975/8HfjYCkbid2vlayxyPtSD9_wtb9a-wHb1uOENsAOwng](https://mirror.xyz/0x83857601C1cFA057F2576b343c563BDB9A4C9975/8HfjYCkbid2vlayxyPtSD9_wtb9a-wHb1uOENsAOwng)

![Zup88.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fc5738a6-6ab6-4bfb-ae1d-dbd5ef59ce73/Zup88.png)

- **PARTE 1.- Aqui empieza lo bueno**

Tu hazme caso sigue este tutorial neta ni vas a sentir cuando ya tengas tu nodo

Primero ínstalaremos el subsistema de Linux para Windows: 

- Presiona la tecla Windows en tu teclado
- Escribe “ ***Powershell*** ”
- Le das click derecho y seleccionas la opción que dice “Ejecutar como administrador”

Ya que carga el sistema, sin moverle nada de nada le pones: 

- ***wsl –install***

Va a empezar a instalar el sistema, puede que tarde dependiendo de tu internet, ya que se descargue reinicias tu computadora. 

Ya que reinicies tu computadora, presionas la tecla Windows y escribes ***Ubuntu*** 

Seleccionas la opción que te muestra y te abrirá la aplicación

** Bueno hasta aqui ya tienes lo mas importante que es Ubuntu, de aqui en adelante es puro código, puede que sea un poco intimidante si no sabes programas como yo mero pero no hay falla bro así empezamos todos aparte tratare de ser muy explicito en las explicaciones de los pasos a pasos. 

Ya que abres ***Ubuntu*** te va a pedir que crees un usuario le das enter, creas una contraseña (no se vera que escribas nada así que no te saques de onda), te pide que la repitas y sobres! ya tienes tu usuario en Ubuntu listo valedor@. 

Por alguna razón aun que tengamos el programa tenemos que hacerle updates para estar seguros que tenemos la version mas reciente así que, tecleamos lo siguiente le das ENTER

- sudo apt update

Luego 

- sudo apt full-upgrade

 ( después de dar enter te va a pedir que le des Y y que pongas tu contraseña ) 

Sudo haz de cuenta que es como ordenarle al sistema que eres admin y que quieres correr algo 

Bueno hasta aqui ya tienes todo lo que vamos a ocupar listo.
