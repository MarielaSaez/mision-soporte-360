# Misión Soporte Técnico 360° — Edición 4

Juego web Alfa/Beta para Prácticas Profesionalizantes, compatible con GitHub Pages.

## Publicación
Subí `index.html`, `videos/` y `.nojekyll` a la raíz de un repositorio. En Settings → Pages elegí Deploy from a branch, main y root. No subas el panel docente ni las respuestas a la web pública.

## Funcionamiento
El avance se guarda en cada navegador mediante localStorage. El estudiante exporta un JSON con su informe; la docente lo importa en el panel privado (`Panel_Docente_Soporte_360.html`) disponible por separado. No hay sincronización online automática.

## Configuración por enlace
Agregá `?min=80&pen=2&hints=off` al enlace publicado para configurar minutos iniciales, minutos de penalización por diagnóstico incorrecto y pistas. Se aplica a partidas nuevas. El modo docente genera estos enlaces.

## Seguridad
La consola y el laboratorio son simulaciones locales: NO ejecutan comandos ni manipulan hardware real. Los códigos y la evaluación están en el navegador; quien inspeccione el código fuente puede verlos, por lo que no es un sistema antitrampa de alta seguridad.
