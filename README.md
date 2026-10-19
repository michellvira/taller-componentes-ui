# Taller 2: componentes en JavaScript

Continuación del taller de formularios de autenticación.

En esta actividad organicé el menú, el pie de página y el formulario de registro en componentes nativos (HTMLElement y Shadow DOM) para reutilizarlos sin repetir el mismo código.

La aplicación incluye validaciones con expresiones regulares y mensajes al completar el formulario. Los envíos son de prueba: no se crean cuentas ni se envían correos reales.

## Cómo abrirlo

Desde la carpeta del proyecto, ejecutar en la terminal:

```powershell
C:\xampp\php\php.exe -S localhost:8000
```

Después escribir `http://localhost:8000` en el navegador. Esta dirección funciona únicamente mientras el servidor esté encendido en el computador.

## Estructura

```
index.html
assets/
├── css/style.css
└── js/
    ├── main.js
    └── components/
        ├── NavComponent.js
        ├── FooterComponent.js
        └── RegisterComponent.js
```

## Nivel de IA utilizado

Nivel de IA: 3 / 5

Criterio de Medición del Nivel de IA (0 a 5): 0 (Nada): No se utilizó ninguna herramienta de Inteligencia Artificial; todo el desarrollo y código fue realizado de manera completamente manual. 1 (Mínimo): Se usó la IA únicamente para corrección ortográfica puntual o consulta rápida de definiciones aisladas. 2 (Moderado-Bajo): Se usó la IA para generar ideas generales, estructurar borradores o resolver errores menores de sintaxis. 3 (Intermedio): Se usó la IA para estructurar fragmentos de código, plantillas base o refactorizar secciones específicas del proyecto. 4 (Avanzado): La mayor parte de la planeación y esquemas iniciales fueron asistidos por IA, con revisión y adaptación rigurosa por parte del aprendiz. 5 (Total): El entregable fue generado casi en su totalidad por Inteligencia Artificial con mínima o nula intervención humana en su modificación.
