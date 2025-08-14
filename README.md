# Challenge-Literalura

NOTA: Este es solo un ejemplo basico, del cual necesita muchisimo mas trabajo y preparacion para ser llamado proyecto.

# 📚 Literalura

Aplicación Java de consola para explorar libros usando la API Gutendex con almacenamiento en PostgreSQL.

```bash
# Requisitos: JDK 17+, PostgreSQL
git clone https://github.com/tu-usuario/literalura.git
cd literalura
mvn spring-boot:run

🚀 Características clave
Busca libros por título

- Almacena tus búsquedas localmente
- Filtra por idioma (ES/EN/FR/PT...)
- Consulta autores por periodo histórico

🛠️ Tecnologías
Java 17 | Spring Boot 3.1

PostgreSQL | JPA/Hibernate

API Gutendex | HttpClient

🖥️ Uso básico
Ejecuta la aplicación

Usa el menú interactivo:
1 - Buscar libro
2 - Listar libros guardados
3 - Filtrar por idioma
0 - Salir

📦 Estructura principal

src/
├── main/
│   ├── model/       # Entidades (Libro, Autor)
│   ├── service/     # Lógica de negocio
│   └── resources/   # Configuración

📄 Licencia
MIT © Tu Nombre

### Ventajas de esta versión:
1. **Más scaneable** - Los ojos captan inmediatamente lo importante
2. **Acción inmediata** - El bloque de código al inicio permite probar rápido
3. **Secciones esenciales** - Solo lo que realmente necesita un usuario
4. **Visualización móvil** - Se lee bien en cualquier dispositivo
5. **Fácil mantenimiento** - Más simple de actualizar

### ¿Qué quité y por qué?
- Tablas muy detalladas (se sobreentiende con la lista de tecnologías)
- Instrucciones de instalación redundantes (el comando inicial basta)
- Ejemplos de flujo muy extensos (el menú es autoexplicativo)
- Estructura completa del proyecto (solo pongo lo relevante)

**Recomendación**: Si el proyecto crece, puedes añadir:
1. Un `CONTRIBUTING.md` separado
2. Un wiki para documentación avanzada
3. Un archivo `EXAMPLES.md` con casos de uso
