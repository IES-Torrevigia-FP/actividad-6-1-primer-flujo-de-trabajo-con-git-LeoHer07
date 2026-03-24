El directorio de trabajo es la carpeta donde editas los archivos; la zona de staging es donde seleccionas qué cambios exactos quieres incluir en el próximo commit;
el historial de commits es el registro permanente de todas las instantáneas confirmadas del proyecto.

Un error típico es modificar archivos y hacer directamente git commit sin antes git add, 
por lo que tus cambios no entran en el commit; lo evitaría revisando siempre git status y usando git add antes de confirmar.

Poder decidir qué cambios entran en cada commit te permite crear commits pequeños y coherentes (por funcionalidad o arreglo), 
lo que facilita entender el historial, revisar el código y deshacer cambios concretos si hace falta.
