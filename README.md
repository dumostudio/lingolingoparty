# Lingo Lingo Party — Countdown V2

Demo de una sola pantalla para celular.

## Demo
- Festejada: Samanta
- Edad: 7
- Fecha: 17 de enero de 2027
- Hora: 4:00 PM
- WhatsApp de prueba: 8110314514
- Ubicación: enlace de Google Maps proporcionado para Lingo Lingo Party

## Flujo
1. Pantalla inicial con la imagen temática.
2. Botón caricaturesco "TOCA ¡AQUÍ!" colocado sobre una zona clara para no tapar a los personajes.
3. Al tocar:
   - se abre el countdown;
   - comienza música generada con Web Audio, en loop;
   - comienza confeti durante 2 minutos.
4. Al llegar a cero:
   - desaparecen WhatsApp y ubicación;
   - aparece "¡Feliz cumpleaños, Samanta!";
   - hay una segunda explosión de confeti;
   - cambia la música a una melodía de Happy Birthday.

## Nota
La música actual es una melodía sintetizada tipo MIDI creada directamente en el navegador para evitar depender de archivos externos. Se puede sustituir por archivos de audio cuando se defina la música final.

## Personalización
Todos los datos principales están al principio del bloque `const EVENT` dentro de `index.html`.
