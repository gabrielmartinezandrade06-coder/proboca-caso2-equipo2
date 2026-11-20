# Guía del repositorio del Equipo 2

Cómo entrar al repositorio del Caso 2 de PROBOCA y trabajar en él desde GitHub, ChatGPT y Claude.

**Repositorio:** https://github.com/gabrielmartinezandrade06-coder/proboca-caso2-equipo2 (público: cualquiera lo ve; solo el equipo lo edita)

## Por qué trabajar todos en un mismo repositorio

1. **Una sola versión de todo.** Se acaba el "¿cuál es el bueno, el de WhatsApp o el del correo?". El archivo del repositorio es el bueno.
2. **Nadie depende de quién tiene el archivo.** Los entregables, los Excel y las notas están ahí a cualquier hora, para las cinco.
3. **La IA ya sabe del proyecto.** Claude y ChatGPT leen el repositorio con las instrucciones del caso. No hay que volver a explicar qué es PROBOCA, qué producto llevamos ni qué cambió.
4. **Los datos están al día.** Cuando algo cambia (un arancel, un cierre sanitario, una decisión), se corrige una vez en `04-notas/hechos-clave.md` y todas trabajan con el dato nuevo.
5. **Nada se pierde.** GitHub guarda cada versión. Si alguien borra o cambia algo por error, se recupera.
6. **Se ve quién hizo qué.** Cada cambio queda con nombre y fecha, así que el trabajo de cada una cuenta.

## Paso 1. Entrar al repositorio

1. Abre el correo de invitación de GitHub y dale **Accept invitation**. Si no lo encuentras, entra a https://github.com/gabrielmartinezandrade06-coder/proboca-caso2-equipo2/invitations con tu sesión de GitHub abierta.
2. Abre el enlace del repositorio. Si ves las carpetas, ya estás dentro.
3. **Empieza leyendo dos archivos:** `README.md` (qué hay y dónde) y `04-notas/hechos-clave.md` (lo vigente del caso).

**Qué hay en cada carpeta**

- `00-contexto/`: el kick-off de PROBOCA y el documento del equipo con lo que dijo Adrián.
- `01-entregables/`: todo lo que ya entregamos, numerado en orden.
- `02-datos/`: los Excel (modelo de costos, matriz de proveedores, lista de cotizaciones).
- `03-texto/`: los mismos archivos en texto, para que las IAs los lean bien.
- `04-notas/`: hechos clave, actividades de clase y pendientes.

## Paso 2. Usarlo en ChatGPT

1. En ChatGPT, abre **Configuración** y busca la sección de **Apps** o **Conectores**.
2. Elige **GitHub**, dale **Conectar** e inicia sesión con tu cuenta de GitHub. Autoriza el acceso.
3. Abre un chat nuevo, toca el **+** de la barra de mensajes y elige **GitHub**.
4. Escribe, por ejemplo: *"Usa el repositorio proboca-caso2-equipo2. Lee primero AGENTS.md y 04-notas/hechos-clave.md. Luego ayúdame con…"*

**Antes de pegar datos de PROBOCA en ChatGPT:** en Configuración, en Controles de datos, apaga la opción que usa tus conversaciones para mejorar el modelo.

**Si no te aparece el repositorio:** como ya es público, puedes pegarle a ChatGPT el enlace del repositorio. Para que ChatGPT pueda editarlo con tu cuenta, Gabriel tiene que darle acceso al conector desde la suya.

**Si no te aparece GitHub en ChatGPT** (puede depender de tu plan): crea un Proyecto en ChatGPT y sube los archivos de `04-notas/` y `03-texto/`. Funciona, pero no se actualiza solo.

**ChatGPT lee, pero no guarda en el repositorio.** Lo que hagas con él, súbelo tú (Paso 4).

## Paso 3. Usarlo en Claude

1. En claude.ai, crea un **Proyecto** (por ejemplo, "PROBOCA Caso 2").
2. En el conocimiento del proyecto, elige **Agregar desde GitHub**, conecta tu cuenta y selecciona `proboca-caso2-equipo2`. Puedes elegir todo el repositorio o solo `04-notas/` y `03-texto/`.
3. Pega el contenido de `CLAUDE.md` en las instrucciones del proyecto, para que Claude siempre sepa las reglas del caso.
4. Pregunta lo que necesites dentro de ese proyecto.

**Cuando alguien suba algo nuevo**, actualiza o sincroniza el conocimiento de GitHub en el proyecto para que Claude vea la versión nueva.

**Avanzado (opcional):** con Claude Code o Codex puedes clonar el repositorio y pedirle a la IA que edite los archivos y suba los cambios ella misma.

## Paso 4. Subir o cambiar archivos (desde el navegador, sin instalar nada)

**Subir un archivo nuevo** (por ejemplo, un entregable):

1. Entra a la carpeta donde va (por ejemplo, `01-entregables/`).
2. Toca **Add file** y luego **Upload files**.
3. Arrastra el archivo.
4. Abajo, en el mensaje, escribe qué es (por ejemplo, *"Entregable 7: final report"*).
5. Toca **Commit changes**. Listo: ya lo tienen todas.

**Corregir una nota** (por ejemplo, `04-notas/pendientes.md`):

1. Abre el archivo y toca el **lápiz** (Edit).
2. Haz el cambio.
3. Escribe en el mensaje qué cambiaste y toca **Commit changes**.

**Nombres de archivo:** número, nombre corto y sin acentos ni espacios raros, como los que ya están (`07-Final-Report.pdf`).

## Paso 5. Reglas del equipo

- **El repositorio es público** desde el 20 nov 2026, con permiso de PROBOCA: cualquiera lo ve, pero solo el equipo lo edita. La lista de cotizaciones sigue siendo de uso académico: no la uses para otra cosa.
- **No contactamos proveedores a nombre de PROBOCA.** Las preguntas a PROBOCA van por las profesoras.
- **Todo dato lleva su fuente y su fecha.** Si algo no está confirmado, se escribe que falta.
- **Lo nuevo se sube el mismo día**, y se anota en `04-notas/` qué cambió.
- **No borres archivos de otras sin avisar en el grupo.** Si pasa, Gabriel lo recupera del historial.

## Si algo no funciona

| Problema | Qué hacer |
| --- | --- |
| No me llegó la invitación | Entra a la página de invitaciones (Paso 1) con tu sesión abierta |
| Veo "404" en el enlace | No has aceptado la invitación o estás en otra cuenta de GitHub |
| ChatGPT no ve el repositorio | Gabriel tiene que darle acceso al conector desde su cuenta |
| Claude no ve un archivo nuevo | Sincroniza el conocimiento de GitHub en tu proyecto |
| Subí algo por error | Avisa en el grupo; se recupera del historial |
