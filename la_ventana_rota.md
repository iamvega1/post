# La ventana rota en tu proyecto

> Consideren un edificio con una ventana rota. Si la ventana no se repara, los vandalos tenderán a romper unas cuantas más. Finalmente, quizás hasta irrumpan en el edificio; y si está abandonado, es posible que lo ocupen ellos y que prendan fuego dentro o consideren una acera o una banqueta, se acumula algo de basura; pronto, más basura se va acumulando, con el tiempo, la gente acaba dejando bolsas de basura de restaurantes de comida rápida o hasta asaltando coches. ”
> **[1982 de The Atlantic Monthly](https://es.wikipedia.org/wiki/The_Atlantic_Monthly)**

Un poco mas de contexto, si ya conoces la teoria salta hasta el párrafo que dice “**Mi opinion**”.

Existe la teoría llamada **teoría de las ventanas rotas**, en 1969, en la Universidad de Stanford (EEUU), el Prof. Philip Zimpardo realizó un experimento de psicología social. Dejó dos autos abandonados en la calle, dos autos idénticos, la misma marca, modelo y hasta color. Uno lo dejó en el Bronx, por entonces una zona pobre y conflictiva de Nueva York y el otro en Palo Alto, una zona rica y tranquila de California

Dos autos idénticos abandonados, dos barrios con poblaciones muy diferentes y un equipo de especialistas en psicología social estudiando las conductas de la gente en cada sitio.

Resultó que el auto abandonado en el Bronx comenzó a ser vandalizado en pocas horas. Perdió las llantas, el motor, los espejos, la radio, etc. Todo lo aprovechable se lo llevaron, y lo que no lo destruyeron. En cambio el auto abandonado en Palo Alto se mantuvo intacto.

Es común atribuir a la pobreza las causas del delito, tema en el que coinciden las posiciones ideológicas más conservadoras, (de derecha y de izquierda). Sin embargo, el experimento en cuestión no finalizó ahí.

Cuando el auto abandonado en el Bronx ya estaba deshecho y el de Palo Alto llevaba una semana impecable, los investigadores rompieron un vidrio del automóvil de Palo Alto. El resultado fue que se desató el mismo proceso que en el Bronx, y el robo, la violencia y el vandalismo redujeron el vehículo al mismo estado que el del barrio pobre.

¿Por qué el vidrio roto en el auto abandonado en un vecindario supuestamente seguro es capaz de disparar todo un proceso delictivo?

No se trata de pobreza. Evidentemente es algo que tiene que ver con la psicología humana y con las relaciones sociales. Un vidrio roto en un auto abandonado transmite una idea de deterioro, de desinterés, de despreocupación que va rompiendo códigos de convivencia, como de ausencia de ley, de normas, de reglas, como que vale todo. Cada nuevo ataque que sufre el auto reafirma y multiplica esa idea, hasta que la escalada de actos cada vez peores se vuelve incontenible, desembocando en una violencia irracional.

### Mi opinión

A donde voy con todo esto bueno aquí **ahora si entra el código**, traslademos todo lo aprendido anteriormente siganme el viaje.

Imaginen un proyecto donde el tiempo es reducido, o ni siquiera imaginen solo piense en su proyecto actual, al tener poco tiempo a veces no podremos sacar el proyecto con la mejor calidad esto quiere decir que puede tener errores y es entendible, la idea no es que sea perfecto sino funcional y en el tiempo establecido.

Bueno partiendo de aquí también se pueden presentar malas prácticas imagine que sin querer dejaste algoritmos muy complejos y no los simplificar, bueno tu código podrá contener ifs anidados tal ves, comparación entre strings o números que aparentemente no dicen mucho (ejemplo un if contra un 87635, no sabes que es pero es parte de la lógica).

Bueno a donde quiero llegar creo que es primordial que tengamos en mente que al tener detalles en nuestro código esto psicológicamente hará que sea más propenso a seguir extendiendo estas malas prácticas, creo que es necesario después de terminar un proyecto así tener en cuenta que existe una segunda etapa después de entregar a la cual llamare refactorizar o embellecer tu código.

### Propuesta

Cuando te topes con un ifs anidado, replantea el problema, recuerda que alguien más lo tendrá que leer y tal vez le puedas facilitar el trabajo si mejoras esta parte.

Cuando tengas una validación intenta no comparar contra un número textual o string intenta contextualizar dale un nombre haz que tenga sentido la validación.

Cuando un método es muy extenso y contiene mucha lógica toca replantearse un método debería hacer una cosa así que tal vez puedas simplificar extrayendo esa lógica en métodos más pequeños esto ayudará a su legibilidad.

Estos son solo unos pequeños puntos a considerar si quieres aprender más sobre cómo tener una buena base de código te comparto la guía de js de Google, [link para volverte PRO](https://google.github.io/styleguide/jsguide.html).


Con toda esta información que te di lo que busco, es que comprendas que al dejar pequeños indicios de mal código, será más propenso a que exista una tendencia de continuar por el mal camino. Recordemos que muchas veces nuestro código pasará por muchos Ingenieros ellos modificaran, eliminaran, o simplemente leerán el código, si tenemos una mala implementación es posible que ellos también lo usen por que al verlo pensaran que es aceptable.

Yo opino que **#NoAlaVentanaRota en mi codigo**, ahora busquemos que nuestro código no incluya estas malas prácticas, esto ayudará a que el proyecto sea más entendible legible y mantenible, ya no será un dolor de cabeza el agregar una nueva característica y nos dará una facilidad tremenda para la reutilización del código.

> Nota: Este post no intenta decir como debes hacer tu codigo solo quiero compartir mi experiencia e intentar fundamentar, por qué creo que debemos buscar el no permitir las malas prácticas aun cuando estas sean muy pequeñas. Esto es una guía, no una regla.
[Luis V.](https://github.com/iamvega1/post)