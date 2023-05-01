# EULER-AI
Una pequeña inteligencia artificial para Arduino capaz de aprender a jugar al juego Subway Surfers.

Esta es una pequeña inteligencia artificial programada en Arduino que puede aprender a jugar a Suway Surfers. En este juego debes moverte de un lado a otro entre tres carriles de vías de tren intentando esquivar los vagones en tu camino. En este juego también puedes saltar, pero para simplificar el proceso, he optado por solo aprender a esquivar los vagones. Los carriles estan representados por led, una fila de tres leds donde se mostrarán los vagones que vayan apareciendo por los carriles y otra fila donde se indicará la posición del jugador. Primero el programa elige de manera "aleatoria" el carril que estrá libre de vagones, por lo que los otros dos leds se encenderán indicando que ahí hay un vagón, dejando una sola solución posible, que el personaje se encuentre en la columna donde no hay vagones. Después el personaje elije también de manera "aleatoria" entre una lista creada para cada situación posible situación. Si el personaje acierta en un principio por suerte, este será recompensado aumentando la probabilidad de que vuelva a hacer la elección ganadora cuando se le vuelva a presentar esa situación, creando así un refuerzo positivo, pero en caso de no acertar, no sufrir ningun tipo de consecuencia a parte de no tener más probabilidades de replicar esta elección en futuras ocasiones.

Adjunto una gráfica de victorias y derrotas: https://imgur.com/a/5PUG3BG

Configuración electrónica: https://imgur.com/a/Lxljjr7
