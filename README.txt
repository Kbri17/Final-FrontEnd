# Final-FrontEnd

Nos dividimos el trabajo el trabajo en dos partes:


Primera parte :  Lina Maria Gonzalez

Destkop

Lo dividí en dos partes principales:  

•	El header lo compone el logo el menú y adicional el icono de hamburguesa que solo se visualizará cuando sea móvil. 
•	En el Main se dividió por 3 secciones:
    -	Home se encuentra dos div, uno de ellos tiene la imagen esta imagen tiene un width 100vw esto para que se visualice
        de tal forma que se alinee con el logo y la opción del menú “About Us”. 
    -	En la parte de la información se ve de un color violeta cuando se encuentra en desktop con un texto definido.
    -	La última parte se una lista enumerada que se trabajo en dos filas, donde se creo un pseudo-clase con el fin de 
        organizar ese último numerado en el centro del section que lo contenía y se utilizó el pseudo-elemento ::before 
        para darle forma a la numeración, hace que inicie del 01 y así podamos tener la numeración de 2 dígitos. 

Mobile
•	El menú y el botón no se visualizarán por esta razón está el display: none.
•	La parte del home que incluye la imagen, el texto y el botón se ve de manera vertical. 
•	Cuando la página este en mobile se visualizará el texto donde se encuentra la pregunta de un color celeste brillante y con un texto diferente al que se observa en desktop. 
•	La lista ordena se verá de manera vertical y esta lista numerada se encuentra, se dejo el mismo pseudo-elemento ::before para que cambiará el estilo en esta lista, el h3 va a tener un background-color violeta y con su respectiva numeración de dos dígitos. 


Segunda parte -parte abajo - : Kenia Vilcapaza 
Lo dividi en tres partes : La primera incluia la foto y descripcion de los deportistas.
La segunda incluia un p y el boton de "Go for it" y la tercera : el footer.

Modo Compu:
Para la parte de los deportistas use flex direccion horizontal, y le di un ancho de 30% para cada seccion de
 deportista.
 Organizar el footer: lo dividi en tres partes. Aplicando el ancho respectivo de 25%,50% y 25%. Luego a cada seccion 
 le di un flex direccion vertical y solo cuestion de acomodar los elementos internos. 
Modo Mobile : 
Aqui solo hice pequeños cambios: 
- Uso del display:none para ocultar la seccion de los dos deportistas laterales.
- Ajuste de la altura , el tipo de letra y el ancho paso a ser casi el 100vw.
- Para el footer , aplique direccion vertical reversa y cambie los margenes.
- Al div de copyright lo reubique poniendo position:relative y un top:280px , asi se ubico en la base del footer.

El modo responsive esta diseñado para un ancho de 480px.

