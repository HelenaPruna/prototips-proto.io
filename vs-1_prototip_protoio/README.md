# Primera versió del prototip

Prototip inicial fet amb [proto.io](https://proto.io). Aquesta versió és la visualització d'un usuari 
administrador que pot fer totes les accions possibles que aquest projecte vol assol·lir.

## Visualitzar el prototip
Clicar l'arxiu dintre d'aquesta carpeta amb nom `fullscreen.html`. En cas de no saber amb quins items de la pantalla si es clica en qualsevol part i es veuran uns requadres blaus a sobre dels items interactuables.  

Aquest prototip ha estat implementat amb un ordre molt concret d'accions, per evitar errors s'ha de seguir com està explicat a continuació:
1. Inicia sessió: Posar nom (i cognom) i clica el botó `iniciar sessió`. 
2. Observar quines són les sol·licituds actuals. 
3. Mirar la informació del taller `Costura`. Haurà d'afegir una persona a la llista d'espera. Abans de confirmar els canvis, haurà d'eliminar el participant `Àlex Martin`. Confirmem els canvis.
5. L'usuari ja no vol el taller, i per tant l'eliminarà.
6. Afegir un taller amb els següents requisits:
   - Nom qualsevol
   - Un o dos responsables (persones que portaran el taller)
   - Horari qualsevol (dates i temps)
   - Número de participants màxim que sigui 5
   - Número de faltes justificades i no justificades a 1
   - Sala qualsevol
7. Editar el llistat de participants del taller creat:
   - Modificar la capacitat màxima a 3. 
   - Afegir tres persones a la llista de participants.
   - Passar la llista. Els dos primers participants hauran assistit, però el tercer no, i no ho haurà justificat.
8. Per aquest nou taller s'haurà de fer una sol·licitud nova. És lliure el tipus, el missatge i la categoria. 
9. L'usuari haurà de comprovar que la nova sol·licitud és present a la pestanya de sol·licituds. 
10. Afegir la persona `Paula Romero` al calendari de rentadora en l'horari de dilluns a les 9:00. 
11. Mirar la disponibilitat de sales pel dia 26/04/2024 a l'horari 8:30-10:30 per a 20 persones. 
12. Reservar una sala pel dia 26/04/2024 a l'horari 8:30-10:30 per a 20 persones.