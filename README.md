# Pràctica UF4 - Instal·lació i Configuració de Moodle

## 1. Objectius Generals

- Instal·lar i configurar Moodle com a gestor de continguts.
- Aprendre a utilitzar Moodle com a administrador.

## 2. Descàrrega i Instal·lació

### 2.1 Descarregar Moodle

1. Accedeix a la pàgina oficial de Moodle: [Moodle.org](https://moodle.org).
2. Descarrega l'última versió estable i desa l'arxiu a la teva màquina.

### 2.2 Instal·lació a IsardVDI

1. Obre un nou escriptori a IsardVDI.
2. Segueix el manual d'instal·lació d'aplicacions web.
3. Executa la instal·lació seguint els passos indicats.

4. Captura de pantalla de la instal·lació iniciada:
   <img src="images/instalacion del tema, viendo como se instalan los procesos y eso.png" alt="Instal·lació Moodle">

5. Captura de pantalla del fitxer descarregat (Descarrega Moodle).  
   *(Observa que aquesta imatge es mostra després ja que és de la pàgina principal.)*
   <img src="images/pagina principal (el boton para crear curso).png" alt="Descarrega Moodle">

## 3. Configuració Inicial

### 3.1 Configuració de l'Administrador

1. Inicia sessió a Moodle com a administrador.
2. Ves al teu perfil i realitza les següents accions:
   - Canvia el correu electrònic.
   - Modifica la contrasenya.
   - Afegeix un avatar.

### 3.2 Configuració del Lloc

1. Ves a **Administració del lloc > Primera Plana > Paràmetres**.
2. Canvia el nom del lloc (tant el nom llarg com el curt) i configura la visibilitat perquè els usuaris no autenticats no puguin accedir al contingut.
3. Captura de pantalla dels paràmetres modificats:
   <img src="images/Pagina principal del sitio(no accesible para invitados hasta el registro).png" alt="Configuració del Lloc">

### 3.3 Ajustos Addicionals

1. Ves a **Administració del lloc > Ubicació > Paràmetres** i configura la franja horària correcta (ex.: zona horària d'Espanya):
   <img src="images/Ajustes de ubicacion, zona horaria de españa .png" alt="Franja Horària">
2. Canvia l'idioma predeterminat:
   - Instal·la l'idioma Català:
     <img src="images/Idioma Catalan.png" alt="Idioma Català">
     <img src="images/Instalando paquete de idioma en CATALAN.png" alt="Instal·lació del paquet Català">
   - Configura l'idioma per defecte a ESPAÑOL:
     <img src="images/Idioma por defecto ESPAÑOL.png" alt="Idioma per defecte ESPAÑOL">
3. Configura la política de contrasenyes per assegurar un mínim de 4 caràcters amb majúscules, minúscules i xifres:
   <img src="images/Configuracion de las contraseñas .png" alt="Política de Contrasenyes">

---

## 4. Creació de Cursos

### 4.1 Creació dels Cursos A i B

1. Ves a **Administració del lloc > Gestiona cursos i categories**.
2. Crea el curs **A** amb 3 seccions:
   <img src="images/Crear nuevo curso (A).png" alt="Creació Curs A">
   <img src="images/Numeros de secciones (3).png" alt="Número de seccions (3)">
3. Crea el curs **B** amb 5 seccions:
   <img src="images/Crear nuevco curso (B).png" alt="Creació Curs B">
   <img src="images/Numeros de secciones (5).png" alt="Número de seccions (5)">
4. Verifica que ambdós cursos apareguin:
   <img src="images/Imagen de los dos cursos disponibles (Comprobacion).png" alt="Cursos Disponibles">

### 4.2 Afegir Material als Cursos

1. Accedeix al curs A (o B) i activa l'edició.
2. Afegeix un document PDF com a material i canvia el títol d'algun tema.
3. Captura de pantalla de l'edició del curs:
   <img src="images/Creando temas y tareas dentro.png" alt="Edició de Curs">
4. Es crea una activitat específica anomenada "wordpress" dins del Moodle:
   <img src="images/Actividad creada llamada wordpress dentro del moodle.png" alt="Activitat WordPress">

---

## 5. Creació i Gestió d'Usuaris

### 5.1 Creació Manual d'Usuaris

1. Ves a **Administració del lloc > Usuaris > Comptes > Afegeix un usuari**.
2. Crea l'usuari **Bob** amb autenticació manual:
   <img src="images/Creando a Bob manualmente.png" alt="Creació Usuari Bob">
3. Assigna-li una contrasenya:
   <img src="images/Poniendole contraseña a Bob.png" alt="Assignació de contrasenya a Bob">
4. Assigna el rol de professor:
   <img src="images/Captura poniendo a Bob como professor.png" alt="Bob assignat com a professor">
5. (Opcional) Revisa l'opció per crear un nou usuari:
   <img src="images/Crear un nuevo usuario (opcion enmarcada, donde se situa).png" alt="Crear Nou Usuari">

### 5.2 Creació Massiva d'Alumnes

1. Prepara un fitxer CSV amb la llista d'alumnes (consulta el model del fitxer `usuarios.csv`).
2. Ves a **Administració del lloc > Usuaris > Comptes > Carrega usuaris**.
3. Pugeu el fitxer CSV i completa la creació.
4. Captura de pantalla del procés:
   <img src="images/Usuarios csv.png" alt="CSV d'usuaris">
   <img src="images/Subiendo el archivo csv de los usuarios dentro de subir usuarios.png" alt="Carrega del CSV">
   <img src="images/Subir usuarios boton (para el csv y eso, pero el boton).png" alt="Botó per pujar el CSV">
   <img src="images/Usuarios en lista (para seleccionar).png" alt="Llista d'usuaris">

### 5.3 Accions Massives d'Usuaris

1. Per eliminar usuaris en bloc, selecciona els alumnes corresponents.
2. Executa l'acció d'eliminar.
3. Captura de pantalla del procés d'eliminació:
   <img src="images/Acciones de usuarios massivas.png" alt="Accions massives">
   <img src="images/Borrar 2 usuarios.png" alt="Eliminar Usuaris - Part 1">
   <img src="images/Borrar 2 usuarios parte 2.png" alt="Eliminar Usuaris - Part 2">
   <img src="images/Confirmar el borrado de los 2 usuarios.png" alt="Confirmació de l'Eliminació">
   <img src="images/Imagen comprobacion de todos los usuarios .png" alt="Verificació d'usuaris">
   <img src="images/Todos los usuarios con sus roles correspondientes (estudiante, profesor etc).png" alt="Usuaris amb rols">

---

## 6. Matriculació d'Usuaris

### 6.1 Configuració de la Inscripció als Cursos

1. Ves a **Administració del curs > Usuaris > Mètodes d'inscripció**.
2. Per al curs **A**, configura l'accés com a públic (sense inscripció d'usuaris):
   <img src="images/Pagina principal del sitio(no accesible para invitados hasta el registro).png" alt="Accés Públic al Curs A">
3. Per al curs **B**, activa la inscripció manual per matricular usuaris.
4. Assigna com a professor l'usuari **Bob** al curs B:
   <img src="images/Comprobacion del curso A abierto libre y Bob como professor en el A.png" alt="Matriculació i Rol de Bob">
5. Verifica la llista d'usuaris inscrits:
   <img src="images/Participantes del curso A.png" alt="Participants del Curs A">
   <img src="images/Participantes curso B manual.png" alt="Participants del Curs B">

---

## 7. Personalització i Aparença

1. Descarrega un nou tema per Moodle.
2. Ves a **Administració del lloc > Connectors > Instal·lar complement** per instal·lar el tema:
   <img src="images/metiendo el archivo.zip de la extension del tema dentro del instalador de complementos.png" alt="Instal·lació del Tema">
   <img src="images/Boton de continuar para instalar el complemento.png" alt="Continuar Instal·lació del Complement">
3. Activa el tema i personalitza la capçalera, peu de pàgina i logotip:
   <img src="images/Pagina principal con el tema ya cambiado.png" alt="Tema Actiu">
   <img src="images/Tema 1 del curso A con sus tareas y eso.png.png" alt="Personalització del Tema">
4. Utilitza el botó d'edició per realitzar canvis:
   <img src="images/Boton de edicion (Simplemente una captura del boton activado, reusable para otros momentos del manual) .png" alt="Botó d'Edició">
   <img src="images/Boton de continuar general (REUTILIZABLE).png" alt="Botó Continuar">
   <img src="images/Guardar cambios (captura del boton REUTILIZABLE ).png" alt="Guardar Canvis">

---

## 8. Activitats i Tasques

1. **Creació de continguts al curs:**  
   Afegeix materials i configura activitats dins del curs:
   <img src="images/Creando temas y tareas dentro.png" alt="Creació de Temes i Tasques">
2. **Enviament d'una tasca:**  
   Simula l'enviament d'una tasca (rol d'estudiant):
   <img src="images/Enviando una tarea en el moodle (me he puesto en el rol de estudiante).png" alt="Enviament de Tasca">

---

## 9. Seguretat i Ajustos Finals

1. Ves a **Administració del lloc > Politicas de seguridad del sitio** i aplica la política de seguretat (banejar IP sospitosa, etc.):
   <img src="images/Politicas de seguridad del sitio.png" alt="Polítiques de Seguretat">
2. Verifica els ajustos d'ubicació:
   <img src="images/Ubicacion, ajuste de ubicacion boton.png" alt="Ajust d'Ubicació">
