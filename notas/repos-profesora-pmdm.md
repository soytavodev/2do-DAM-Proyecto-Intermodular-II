# Repos de la profesora de PMDM (github.com/caferven), leídos el 15/11/2026

- `dam2627`: ejercicios de repaso de Kotlin (variables, funciones, if, when, bucles, operador Elvis, llamadas seguras). Último cambio: 04/11/2026.
- `pmdm`: proyecto de clase «MiTiendaApp», iniciado el 10/11/2026 (último cambio: 13/11/2026). Es **solo Android** (un módulo `app`), no Kotlin Multiplatform.
  - Kotlin 2.4.21, AGP 9.5.1, Compose BOM 2026.09.00, Material 3, minSdk 24, targetSdk 37.
  - **Arquitectura por capas**: `data` (API remota falsa, DTO, repositorio), `domain` (modelo, interfaz del repositorio, caso de uso), `ui` (pantallas, ViewModel, navegación, tema), `di` (contenedor de dependencias manual), `util`.
  - Navigation Compose, ViewModel, corrutinas y Flow, Coil 3 para imágenes, tests unitarios de ViewModel y caso de uso con repositorio falso.
  - Todavía **no hay red real** (ni Retrofit ni Ktor) ni base de datos local (ni Room ni DataStore).
  - Comentarios en español; textos de datos en inglés.

Conclusión: la forma de trabajar de la clase es Android nativo con Jetpack Compose y arquitectura por capas. Freenglish puede seguir esa misma estructura.
