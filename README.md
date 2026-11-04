# Daniel Rodríguez Diz

[Español](#español) · [English](#english) · daniel.rodriguezdiz182002@gmail.com

## Español

Estudio Ingeniería Informática en la Universidad de Santiago de Compostela. Fuera de clase, con otros tres estudiantes, hice webs y pequeñas aplicaciones para negocios de hostelería.

Aprendo rápido. Cuando un proyecto pide una tecnología que no conozco, me apoyo en la IA para aprenderla sobre la marcha.

### Proyectos de la carrera de los que estoy orgulloso

#### Gestión de un refugio de animales (Bases de Datos II)

Aplicación de escritorio que hicimos entre seis. Diseñamos el esquema en PostgreSQL, con funciones y triggers, y la interfaz en Java Swing, conectada a la base de datos por JDBC.

`Java` `PostgreSQL` `PL/pgSQL` `JDBC`

#### [Monopoly en Java](https://github.com/danielrodriguezdiz/monopoly-java) (Programación Orientada a Objetos)

Lo programé con David Toimil Plaza y Andrés Vázquez Llorente a lo largo de tres entregas. Son unas 4.600 líneas: casillas, edificios y cartas se organizan por herencia, y las reglas del juego se controlan con una jerarquía de excepciones propia. El tablero se dibuja en color en la consola.

`Java` `POO`

#### [Estudios de rendimiento en el FinisTerrae III](https://github.com/danielrodriguezdiz/arquitectura-computadores-hpc) (Arquitectura de Computadores)

Dos informes que escribí con Mateo Rozas González a partir de experimentos en el supercomputador del CESGA. En el primero medimos cuántos ciclos cuesta leer de memoria según el salto entre datos y el tamaño del conjunto, y se ve en qué punto los datos dejan de caber en L1 y L2.

En el segundo optimizamos el método de Jacobi. Con OpenMP llegamos a unas 54 veces más rápido usando 64 hilos, y con instrucciones AVX256 a unas 4,5. Una conclusión que me llevo: compilando con -O3, muchas de las optimizaciones que habíamos hecho a mano dejaban de notarse, porque el compilador ya las aplicaba.

`C` `OpenMP` `AVX` `SLURM`

En la carrera también he hecho prácticas de concurrencia en C con hilos POSIX, redes, OpenGL, inteligencia artificial y autómatas.

### Webs para negocios locales

Éramos cuatro estudiantes. Cada uno buscaba sus clientes y se encargaba de su proyecto, y nos echábamos una mano con el diseño y el código. Hicimos las webs de cuatro bares (Las Vegas, París, Romero y Tokio), una app de reservas para restaurantes, otra para organizar los turnos del personal y una web con reservas para un estudio de tatuajes. Los contratos los generábamos con LuaLaTeX y Python.

`HTML` `CSS` `JavaScript`

### Hackathon: Desenreda

Una app a la que le haces una foto a una multa de tráfico y te explica qué es, cuánto plazo tienes para pagar con descuento o recurrir, y si huele a estafa. Yo me encargué de la parte de IA, los textos y el detector de fraude.

### Por mi cuenta

La Gramola de Música, una web con temática de Minecraft para la clase de Música, y algunos montajes con Arduino UNO para entender cómo funciona.

---

## English

I'm a Computer Engineering student at the University of Santiago de Compostela. Outside class, three other students and I built websites and small apps for bars and restaurants.

I pick things up quickly. When a project needs a technology I haven't used, I lean on AI to learn it as I go.

### University projects I'm proud of

#### Animal shelter management (Databases II)

A desktop app built by a team of six. We designed the PostgreSQL schema, with functions and triggers, and a Java Swing interface that talks to the database through JDBC.

`Java` `PostgreSQL` `PL/pgSQL` `JDBC`

#### [Monopoly in Java](https://github.com/danielrodriguezdiz/monopoly-java) (Object-Oriented Programming)

Written with David Toimil Plaza and Andrés Vázquez Llorente over three milestones. It's around 4,600 lines: squares, buildings and cards are modeled through inheritance, and a custom exception hierarchy enforces the game rules. The board is drawn in color in the terminal.

`Java` `OOP`

#### [Performance studies on FinisTerrae III](https://github.com/danielrodriguezdiz/arquitectura-computadores-hpc) (Computer Architecture)

Two reports I wrote with Mateo Rozas González, based on experiments on CESGA's supercomputer. The first measures how many cycles a memory read costs depending on the stride and the data size, and you can see exactly where the data stops fitting in L1 and L2.

The second is about optimizing the Jacobi method. OpenMP got us about a 54x speedup with 64 threads, and AVX256 about 4.5x. One takeaway: with -O3, many of our hand-made optimizations stopped making a difference, because the compiler was already doing them.

`C` `OpenMP` `AVX` `SLURM`

I've also done coursework on concurrency in C with POSIX threads, networking, OpenGL, AI and automata.

### Websites for local businesses

There were four of us. Each one found their own clients and handled their own project, and we helped each other with design and code. We built websites for four bars (Las Vegas, París, Romero and Tokio), a booking app for restaurants, a shift-planning app for staff and a site with bookings for a tattoo studio. We generated our contracts with LuaLaTeX and Python.

`HTML` `CSS` `JavaScript`

### Hackathon: Desenreda

You take a photo of a traffic fine and the app tells you what it is, how long you have to pay at a discount or appeal, and whether it looks like a scam. I worked on the AI part, the written content and the fraud detector.

### On my own

La Gramola de Música, a Minecraft-themed website for a Music class, and a few Arduino UNO builds to learn how it works.
