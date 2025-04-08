# Historia de usuario

## Historia 1

* **Como: Usuario registrado**

    Persona que tiene una cuenta en netflex y desea ver peliculas.

* **Quiero: Buscar y reproducir una película en la plataforma**

    Poder encontrar una pelicula por nombre, genero o categoria.

* **Para: Disfrutar de contenido de entretenimiento sin interrupciones**

    Acceder a peliculas y series de forma fluida y personalizable

### **Criterio de Aceptación 1:**

### Reproducción de una película en streaming

**Escenario:** El usuario busca y reproduce una película en la plataforma

   **Dado que** el usuario ha iniciado sesión en su cuenta

   **Y** se encuentra en la página principal de la plataforma

   **Cuando** busca una película por nombre, género o categoría

   **Y** selecciona una película de la lista de resultados

   **Y** presiona el botón de reproducir

   **Entonces** la película comienza a reproducirse en el reproductor

   **Y** el usuario puede pausar, adelantar o retroceder la reproducción

## Historia 2

* **Como: Usuario registrado**

    Persona que tiene una usuario y desea guardar contenido para verlo despues

* **Quiero: Agregar peliculas y series a una lista de favoritos**

    Tener la opcion de marcar contenido para acceder a el facilmente en el futuro

* **Para: No perder contenido que me interesa ver más tarde**

    Evitar buscar nuevamente lo que quiero ver

### **Criterio de Aceptación 2:**

### Agregar una película a la lista de favoritos

**Escenario:** El usuario guarda una película en su lista de favoritos

* **Dado que** el usuario ha iniciado sesión en su cuenta

* **Y** se encuentra en la página de detalles de una película o serie

* **Cuando** presiona el botón "Añadir a favoritos"

* **Entonces** la película se guarda en su lista de favoritos

* **Y** el usuario puede acceder a ella desde la sección de favoritos en su perfil

## Historia 3

* **Como: Usuario registrado**

    Persona que ha empezado a ver una pelicula o serie pero no la termino de ver

* **Quiero: Reanudar la reproducción desde el último punto visto**

    Que el sistema recuerde hasta donde vi una pelicula y me permita continuar otro dia

* **Para: No tener que buscar manualmente el minuto exacto donde pause**

    Evitar interrupciones de visualización y hacerla más cómoda

### **Criterio de Aceptación 3:**

### Continuar viendo una película desde donde la dejé

**Escenario:** El usuario reanuda la reproducción de una película

* **Dado que** el usuario ha visto previamente una película pero no la terminó

* **Y** el sistema ha guardado el minuto exacto en el que pausó

* **Cuando** el usuario accede nuevamente a la película desde la sección "Seguir viendo"

* **Y** presiona el botón de reproducir

* **Entonces** la película comienza a reproducirse desde el punto donde la dejó

***Y** el usuario puede continuar viéndola sin necesidad de buscar el minuto exacto
