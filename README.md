# citas-medicas

Taller de pruebas de software en Spring Boot (Java 25 · Spring Boot 4.0.0 · Maven).

- Ejecutar: `CitasApplication` → http://localhost:8080/citas.html
- Pruebas: `mvn test` (excluye las etiquetadas `ui`)
- Cobertura: `mvn verify` → `target/site/jacoco/index.html` (umbral 70 % de líneas)
- Selenium: ejecutar `ReservaUITest` individualmente (requiere Google Chrome)
