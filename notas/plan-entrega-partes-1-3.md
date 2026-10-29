# Propuesta: índice y calendario de las partes 1–3

Borrador del 29/10/2026, pendiente de que Gustavo lo apruebe. Entrega supuesta: **jueves 3 de diciembre de 2026**.

## Índice adaptado al proyecto

1. **Introducción** (1 página): qué es la app, el problema (aprender inglés cuesta dinero y las apps gratis se estancan), a quién va dirigida (hispanohablantes adultos, sobre todo personas trabajadoras sin dinero ni tiempo para academias), funciones principales, tecnologías y cómo se organiza la memoria. **Se escribe al final.**
2. **Identificación de necesidades del sector**
   - 2.1 Empresas del sector: Duolingo, Babbel, Busuu, Rosetta Stone, Open English, ABA English, Memrise + oferta pública (EOI, That's English!) + abiertas (LibreLingo, Anki). Tabla comparativa: modelo de negocio, método, público, precio.
   - 2.2 Empresa tipo: una empresa de aprendizaje de idiomas en línea (contenidos y pedagogía, producto, desarrollo, diseño, datos, soporte, marketing, administración). Ejemplo real: Busuu o ABA English (con presencia en España).
   - 2.3 Necesidades: el idioma como requisito laboral (también en hostelería y limpieza), el precio de cursos y certificados, el estancamiento en las apps gratuitas, las explicaciones de gramática en español. Con datos (Eurostat/INE).
   - 2.4 Oportunidades: móvil y PWA, contenido abierto (Tatoeba, Wikimedia), voz del navegador, el hueco de un curso gratis, completo y sin anuncios para hispanohablantes.
   - 2.5 Tipo de proyecto: aplicación web progresiva (PWA) multiplataforma + empaquetado Android. Por qué no nativa, por qué sin servidor propio.
   - 2.6 Requisitos funcionales, no funcionales (accesibilidad, funcionar sin conexión, rendimiento en móviles baratos, privacidad) y condicionantes (tiempo, una sola persona, coste cero).
   - 2.7 Obligaciones: actividad sin ánimo de lucro, licencias del software y del contenido (CC BY, CC BY-SA, atribuciones), RGPD (si hay cuentas), PRL del puesto de desarrollo, condiciones de uso de terceros (tiendas, Supabase).
   - 2.8 Ayudas: Kit Digital, subvenciones a proyectos de código abierto o educativos (por investigar; si no aplica, justificarlo).
   - 2.9 Guion de trabajo: análisis → diseño → entorno → contenido → desarrollo → pruebas → despliegue → evaluación con usuarios → documentación.
3. **Diseño del proyecto**
   - 3.1 Aspectos tratados: perfiles (visitante sin cuenta, usuario con cuenta opcional), módulos (prueba de nivel, unidades, lecciones, ejercicios, repaso espaciado, progreso), arquitectura (estática + datos de contenido + almacenamiento local), modelo de datos del contenido.
   - 3.2 Viabilidad técnica: tecnologías conocidas (React, TypeScript), lo que hay que aprender (PWA, Capacitor, algoritmo de repetición espaciada), **riesgo principal: producir y revisar el contenido**.
   - 3.3 Fases y plazos con diagrama de Gantt (diciembre 2026 – marzo 2027, contando las prácticas).
   - 3.4 Objetivos verificables y alcance (qué entra y qué queda fuera: otros idiomas, niveles superiores, reconocimiento de voz, chat, certificados…).
   - 3.5 Actividades preparatorias: repositorio, entorno, cuentas, recopilar y revisar contenido con sus licencias.
   - 3.6 Recursos materiales y personales (y qué perfiles haría falta en una empresa).
   - 3.7 Financiación: coste cero de puesta en marcha; qué costaría publicarlo (por ejemplo, cuenta de Google Play) y el mantenimiento.
   - 3.8 Documentación: MCER (descriptores A1), documentación de React/Vite/PWA/Capacitor, WCAG 2.2, licencias Creative Commons, RGPD.
   - 3.9 Calidad: criterios comprobables (Lighthouse, accesibilidad, pruebas, contenido revisado).

## Calendario (unas 5 semanas)

| Semana | Fechas | Trabajo | Entregable |
|---|---|---|---|
| 1 | 29 oct – 8 nov | Confirmar decisiones, reorganizar carpetas, terminar 2.1 y 2.2 | 2.1 y 2.2 redactados |
| 2 | 9 – 15 nov | 2.3, 2.4, 2.5 y 2.6 (requisitos) | Necesidades y requisitos |
| 3 | 16 – 22 nov | 2.7, 2.8 y 2.9 | Parte 2 completa |
| 4 | 23 – 29 nov | 3.1 a 3.9 (diseño, viabilidad, Gantt, objetivos, recursos) | Parte 3 completa |
| 5 | 30 nov – 2 dic | Introducción, bibliografía, revisión con la lista de comprobación, exportar | Documento listo |
| — | **3 dic** | **Entrega** | |
