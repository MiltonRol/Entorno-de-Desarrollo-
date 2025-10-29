



<html>


  <body>

# Tapat APP

## Requisitos Funcionales
### <u>RF1 Login/Autenticació</u>
- Tots els Users
- Actors: Admin,Metges, Tutors, Cuidadors, Infant
### RF2 Registre Usuari TUTOR
- Actors
## Descripcion del Proyecto
<ol>

  <li> L’objectiu de TapatApp consisteix en proporcionar a totes les famílies afectades per cataracta congènita, o qualsevol patologia</li>
  <li> que faci servir pedaç ocular, una eina senzilla i gratuïta que els ajudi a portar aquest tractament de la forma</li>
  <li>més equilibrada possible i, com a conseqüència, obtenir el màxim desenvolupament d’agudesa visual.</li>

  <li>Esperant que el nostre projecte TapatApp, sigui del seu interès.</li>
</ol>

## Objetivos del proyecto

-    <u> Tractament </u>

- Control del temps del pegat de l'infant
- Compartir informacio del tractament mab el servei medic
- Acces restringit per a tipus d'usuari al control del
-  pegat aplicacio multiusuari

## Actors de la App

- Administrador
- Servei Medic
- Tutors (Mares/Pares)
- Cuidadors (Mestres,avis...)
- Infant
- "Part Publica"



## Requisits Funcionals RF i Requisits No Funcioinals RNF

### Requisits Funcionals (RF)

  <li>	<p> Alfred</p>
        <p>Mestre d’educació infantil</p>
        <p>Que poguéssim enregistrar a l’app el temps en minuts que porten el pegat mentre són a l’escola i que tota aquesta informació quedi
           disponible per la resta de persones
           cuidadores de l’infant.</p>
  </li>

  <li->	<p> Joan</p>
        <p>Pare de fill amb cataracta congènita</p>
        <p>Fora molt interessant que el cuidador rebi un alerta a través de l’aplicació cada vegada que calculi, l’app, que el pegat s’ha
            de retirar.</p>
  </li>

  <li> <p>	Marisa</p>
       <p>Informàtica, professora i mare d’un nen amb cataracta congènita</p>
       <p>voldria tenir un resum amb les dades acumulades de seguiment del tractament que ha seguit el meu nen, així li podria donar
          directament a l'oftalmòleg quan tingui visites de seguiment del tractament.</p>
  </li>

  <li> <p>	Carla</p>
       <p>Oftalmòloga</p>
       <p>m’agradaria incidir en el fet que cada vegada tenim més famílies i pacients de diverses nacionalitats. Per tant, l’aplicació
          hauria de desenvolupar-se en els idiomes més comuns com ara el català, castellà, anglès i àrab.</p>
  </li>


### Requisits No Funcionals (RNF)
  
  
  
### a. Requisits del Servidor
  
  
  <ul>
	<li> Allotjament: Hosting Compartit</li>
	<li> Base de dades: MySQL o MariaDB</li>
	<li> Sistema Operatiu: Linux o Windows</li>
	<li> WebService: RESTful llibreria Python Flask</li>
  </ul>

### b. Llenguatges de Programació
  
  - Python
 
 
### c. Seguretat


  <ul>
	<li> Autenticació i autorització pels usuaris</li>
	<li> Xifratge de dades HTTPS </li>
	<li> Copies de seguretat automatiques</li>
  </ul>

## 2. Frontend

### a. Tipus de Clients

 <ul>
	<li> App Mobil: Android</li>
	<li> Consola Python</li>
	<li> Framework Multiplataforma: Flutter (Apps IOS, Android, Web i Desktop)</li>
 </ul>
 
### b. Enmagatzematge local i sincronització

 <ul>
	<li> Guardem dades en local: Token, Nickname </li>
	<li> Seguretats: HTTPS, Autenticació serveis per Token </li>

 </ul>

### c. Gestió d'accessibilitat
 <ul>
	<li> Nivells A, AA, AAA d'accessibilitat</li>
 </ul>

## 3. Requisits Generals Infraestructura

 <ul>
  <li> Xarxa: Internet</li>
  <li> Espais d'Enmagatzematge a Servidor: 1Tb</li>
  <li> APIs a tercers: No en fem servir</li>
 </ul>

### a. Gestió d'usuari i autenticació

 <ul>
  <li> Rols d'Usuari: Tutor i cuidador </li>
  <li> Seguretat password: md5, sha256 o sha512 </li>

 </ul>

## 4. Requisits del Procés de Desenvolupament

 <ul>
  <li> IDE's: VScode Python, Android Studio, PYCharm </li>
  <li> Control de versions: git, Github </li>
  <li> Metodologia de desenvolupament: SCRUM</li>
  <li> Testing i proves de qualitat (QA): Test i proves unitàries</li>


 </ul>






  </body>

</html>

