Experiencia 2 de programacion de ionic con angular

Explicare todas las dependencias que tuve que instalar para hechar a andar ionic, angular y firebase

----Instalar----
Crear un proyecto con cordoba
ng g s services/database
npm install -g firebase
ng add @angular/fire
npm install @angular/fire firebase --save

---Firebase---
logearse en firebase
crear proyecto en firebase
crear la app en firebase
dejarla como app web
en conf del proyecto de firebase sacar la key y colocarlar en enviroments.ts


Ejemplo de key de firebase y como debe de quedar, en especial cambiar el = que estara delante de firebaseConfig por un :

firebaseConfig : {
apiKey: -------
authDomain: ----
projectId: ----
storageBucket: ---
messagingSenderId: ---
appId: ---
measurementId: ---
},

Habilitar en firebase el logeo por correo

Autor Maickol Moreira Godoy.

