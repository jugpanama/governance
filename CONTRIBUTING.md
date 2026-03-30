# Directrices de Contribución a la Gobernanza

¡Gracias por tu interés en hacer crecer el estándar tecnológico de Panamá! Toda evolución en las reglas, valores o estructura del Panama JUG se gestiona de manera transparente y auditable a través de este repositorio.

Para mantener el orden, la seriedad y la calidad en la toma de decisiones, aplicamos el siguiente flujo de trabajo:

---

## Cómo Proponer un Cambio

### 1. El Debate (Abrir un Issue)
Antes de redactar cualquier cambio en los documentos, debes proponer la idea para que la comunidad y los líderes puedan debatir su viabilidad.
* Ve a la sección de *Issues* de este repositorio.
* Crea un nuevo Issue utilizando la plantilla correspondiente (Propuesta de Cambio).
* Explica detalladamente el problema que buscas resolver y el beneficio que traerá a la comunidad o al ecosistema nacional.
* Espera el feedback de los JUG Leaders y la comunidad.

### 2. La Propuesta (Enviar un Pull Request)
Si la idea del Issue recibe el visto bueno de los JUG Leaders para proceder a diseño:
* Haz un *Fork* de este repositorio.
* Crea una rama (*Branch*) con un nombre descriptivo (ej. `feat/actualizar-valores`).
* Realiza las modificaciones exclusivamente en formato Markdown (`.md`).
* Envía un *Pull Request* (PR) hacia la rama `main` de este repositorio, vinculándolo obligatoriamente al Issue original.
* **Nota Crítica:** Todo Pull Request debe cumplir con el DCO (ver abajo) para ser tomado en cuenta.

---

## Certificado de Origen del Desarrollador (DCO)

Para proteger la propiedad intelectual de la comunidad y prepararnos para futuras alianzas internacionales (siguiendo estándares de la Fundación Eclipse y la CNCF), **exigimos que todas las contribuciones estén firmadas**.

Al firmar tus commits, certificas que tú creaste el contenido o que tienes los derechos legales para enviarlo bajo la licencia Apache 2.0 de este repositorio.

### ¿Cómo firmar tus commits?
Es muy sencillo. Solo debes agregar el parámetro `-s` (sign-off) al momento de hacer el commit en tu terminal:

```bash
git commit -s -m "feat: mi mensaje descriptivo"
```

Esto agregará automáticamente una línea al final de tu mensaje de commit parecida a esta:

`Signed-off-by: Tu Nombre <tu_correo@ejemplo.com>`

Los Pull Requests que contengan commits sin firmar no serán aprobados por el equipo de JUG Leaders.

## Estándar de Mensajes de Commit

Para mantener un historial limpio, trazable y profesional, además de la firma DCO, te solicitamos utilizar el estándar de **Conventional Commits**:
* `feat:` para añadir nuevas secciones o documentos.
* `fix:` para corregir errores de redacción o inconsistencias.
* `docs:` para mejoras menores en la documentación existente.

---

## Voluntariado Activo
Si no deseas modificar los estatutos pero quieres sumarte como Voluntario en alguna de nuestras verticales operativas (Marketing, Operaciones, Contenido), por favor consulta los pasos detallados en el archivo `LEADERSHIP.md` para postularte.
