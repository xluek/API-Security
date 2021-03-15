Cómo contribuir
===============

Cuando contribuya a este repositorio, primero discuta el cambio que desea realizar
enviando un problema con los propietarios de este repositorio antes de realizar 
un cambio. La corrección de errores tipográficos o la reformulación para una mejor 
comprensión NO requieren discusión. 

## Modelo de ramificación

Este repositorio tiene dos ramas principales con una vida útil infinita:
* `master` es la rama predeterminada que siempre refleja la última versión.
* `develop` es la rama principal que refleja los últimos cambios entregados para 
la próxima versión. Cuando la rama "develop" alcanza un punto estable y está lista 
para ser lanzada, entonces todos los cambios deben fusionarse nuevamente en "master". 

Se utiliza una variedad de ramas de apoyo para ayudar al desarrollo paralelo. 
Estas ramas tienen una vida útil limitada, ya que eventualmente se eliminarán. 

## Contribuyendo

Las contribuciones a este repositorio son bienvenidas. Para facilitar la 
administración, siga los pasos a continuación: 

1. Bifurque este repositorio a su cuenta. 

2. Clona tu copia de este repositorio, localmente.
   ```
   git clone https://github.com/YOU/API-Security.git
   ```
3. Cree una nueva rama basada en `develop` (e.g., `fix/foreword-section`).
   ```
   git checkout develop && git checkout -b fix/foreword-section
   ```
4. Aplique sus cambios.
   
   Por favor, siga siempre nuestras convenciones de estilo.
   
   Aunque hay un [archivo `.editorconfig`] [1] en la raíz del repositorio,
   es posible que su editor no lo admita. Para obtener más información sobre 
   [EditorConfig] [2] y la compatibilidad con editores de texto / IDE, 
   consulte el sitio web: https://editorconfig.org/.
   
5. Confirme sus cambios.
   
   1. Verifique los archivos modificados y agregue solo los requeridos 
      (por ejemplo, los artefactos de construcción NO DEBEN ser rastreados).
   2. La primera línea del mensaje de confirmación debe proporcionar una breve 
      descripción de sus cambios. Puede entrar en más detalles sobre el cuerpo 
	  del mensaje de confirmación opcional.
      
6. Envíe los cambios a su repositorio público.
   ```
   git push origin fix/foreword-section
   ```
7. Abra una solicitud de extracción desde su `fix/foreword-section` 
   a la rama upstream del repositorio `develop`. 

[1]: .editorconfig
[2]: https://editorconfig.org/
