# Respuesta Pregunta 2

## ¿Hay error en el fragmento?
int dias = segundos / DIAS_EN_SEGUNDOS;
segundos = segundos % DIAS_EN_SEGUNDOS;

int horas = segundos / HORAS_EN_SEGUNDOS;
segundos = segundos % HORAS_EN_SEGUNDOS;

int minutos = segundos / MINUTOS_EN_SEGUNDOS;
segundos = segundos % MINUTOS_EN_SEGUNDOS;

## Respuesta
Primero hay un error con segundos en el cual no tiene el tipo de variable declarada.Segundo que todo para que sea mas efectiva y precisa la variable segundos deberia de ser double.

## Solucion
Poner el tipo de variable declarada en segundos que sea double.