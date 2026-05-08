# Borrador del Proyecto: Mind&Money - Gestor Integral de Vida

## Descripción del Proyecto
Mind&Money es una aplicación móvil diseñada para el ecosistema Android que integra, en una sola plataforma, la gestión de finanzas personales y la administración de tareas y proyectos. El objetivo principal es ofrecer al usuario una herramienta de productividad 360° que fomente el ahorro y el cumplimiento de metas personales mediante recordatorios dinámicos y mensajes motivacionales de introspección.

## Exposición del Problema
En la actualidad, los usuarios suelen fragmentar su información en múltiples aplicaciones (una para gastos, otra para tareas y otra para notas). Esta dispersión genera fatiga digital y falta de correlación entre los recursos financieros y las metas de vida. Además, muchas apps dependen de una conexión constante a internet, lo que limita su uso en zonas de baja conectividad o compromete la privacidad del usuario.

## Plataforma
La aplicación se desarrollará exclusivamente para la plataforma **Android**. Se utilizará el lenguaje **Kotlin/Java** y el entorno de desarrollo **Android Studio**, apuntando a una compatibilidad mínima de Android 8.0 (API 26) para asegurar un alcance masivo.

## Interfaz de Usuario e Interfaz de Administrador
*   **Interfaz de Usuario (App):** Diseño limpio y minimalista. Contará con un menú de navegación (Bottom Navigation) con secciones para: Dashboard (resumen), Finanzas (ingresos/gastos), Tareas (lista de pendientes) y "Mensajes del Futuro".
*   **Interfaz de Administrador:** Se implementará un módulo de recepción de datos simple donde la app consumirá un servicio web (API) para mostrar consejos diarios de inversión o motivación enviados de forma remota.

## Funcionalidad
1.  **Gestión Financiera (Offline):** Registro de transacciones con categorías y visualización de saldo total.
2.  **Gestión de Tareas (Offline):** Creación de metas con fechas límite y recordatorios mediante notificaciones locales.
3.  **Cápsula del Tiempo:** Función para programar mensajes que el usuario recibirá en una fecha futura.
4.  **Sincronización de Consejos (Online):** Recepción de tips de educación financiera y frases motivacionales.

## Diseño (Wireframes)
*Para esta sección en el README, deberás subir imágenes de tus bocetos o describir brevemente cada pantalla:*
*   **Pantalla 1:** Login/Acceso con PIN.
*   **Pantalla 2:** Dashboard con gráfico circular de gastos y lista de tareas prioritarias.
*   **Pantalla 3:** Formulario de registro de gastos/ingresos.
