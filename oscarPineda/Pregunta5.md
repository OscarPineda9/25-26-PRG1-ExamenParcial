# Respuesta Pregunta 5

## ¿Hay error en el fragmento?

while (dia <= DIAS) {
    int consumoDia = 0;
    int hora = 0;
    while (hora < HORAS) {
        // ...
        hora++;
    }
}
System.out.println("Media semanal: " + (consumoTotalSemana / 7));

## Respuesta 
Primero que todo la Variable final int DIAS se puede confundir con el int dia.Lo mismo con final int HORAS y el int hora.Es una mala practica he implementacion.

## Solucion
Poner ULTIMO_DIA en vez de DIAS en la variable final ya asi puedes dejar el int dia asi como esta. En la variable final HORAS poner ULTIMA_HORA para poder dejar claras las variables y no estar repitiendo nombres de variables ya que lo vuelve confuso al leerlo y es una mala practica.