# WorkTracker

WorkTracker is a simple project and task planning tool that runs directly in your web browser.

No installation is required for normal use.

The application is contained in the file:

`Work-tracker-v4.html`

Your project plans are stored separately as `.json` files. This means you can keep different plans, open them when needed and save your changes.

WorkTracker is also designed to work with AI agents. The file `WorkTracker-AGENT-GUIDE.md` explains how an AI agent should read and safely modify your plan, so you can ask your agent to help you organise, update and maintain your tasks.

---

# Español

## 1. Descargar WorkTracker

### Opción recomendada: descargar como ZIP

No necesitas saber programar ni instalar Git.

1. Abre la página del proyecto en GitHub.
2. Pulsa el botón verde **Code**.
3. Pulsa **Download ZIP**.
4. Espera a que termine la descarga.
5. Ve a tu carpeta de **Descargas**.
6. Haz clic derecho sobre el archivo ZIP descargado.
7. Selecciona **Extraer todo...**.
8. Abre la carpeta que se ha creado.

Dentro encontrarás los archivos de WorkTracker.

---

## 2. Abrir WorkTracker

Busca este archivo:

`Work-tracker-v4.html`

Haz doble clic sobre él.

WorkTracker se abrirá en tu navegador, por ejemplo:

- Google Chrome
- Microsoft Edge
- Firefox

No necesitas instalar ningún programa adicional.

> Si Windows pregunta con qué programa quieres abrir el archivo, selecciona tu navegador habitual.

---

## 3. Abrir un plan

Los planes de WorkTracker son archivos con extensión:

`.json`

Por ejemplo:

`Example-plan.json`

Para abrir uno:

1. Abre `Work-tracker-v4.html`.
2. Pulsa **Abrir**.
3. Selecciona el archivo `.json` de tu plan.
4. El plan aparecerá en WorkTracker.

---

## 4. Guardar tus cambios

Una vez abierto un plan, puedes modificar tareas, estados, responsables, notas y el Roadmap.

Cuando WorkTracker tiene acceso directo al archivo, puede guardar los cambios sobre el mismo archivo y utilizar autoguardado.

Dependiendo del navegador o de cómo se haya abierto el archivo, puede que en su lugar WorkTracker descargue una nueva copia del archivo `.json`.

Si estás trabajando con información importante, conserva siempre una copia de seguridad de tu plan.

---

## 5. Usar un agente de IA para organizar tus tareas

El archivo:

`WorkTracker-AGENT-GUIDE.md`

está pensado para que puedas darle tu plan a un agente de IA y pedirle que te ayude a organizarlo.

Por ejemplo, puedes pedirle:

- Añadir nuevas tareas.
- Dividir una tarea grande en subtareas.
- Reorganizar tareas.
- Actualizar responsables.
- Cambiar estados.
- Añadir notas.
- Revisar tareas pendientes.
- Identificar tareas bloqueadas o en espera.
- Mantener el Roadmap organizado.
- Actualizar el plan a medida que avanza el proyecto.

La guía explica al agente cómo modificar el archivo `.json` sin destruir información existente, cómo conservar la estructura del proyecto y cómo evitar marcar tareas como terminadas sin evidencia.

Una forma sencilla de trabajar es darle al agente:

1. Tu archivo de plan `.json`.
2. El archivo `WorkTracker-AGENT-GUIDE.md`.
3. Una instrucción con lo que quieres organizar o actualizar.

Por ejemplo:

```text
Lee WorkTracker-AGENT-GUIDE.md y utiliza esas reglas para gestionar mi plan.

Revisa el proyecto, organiza las tareas pendientes y divide las tareas demasiado grandes en subtareas claras. No marques ninguna tarea como terminada sin evidencia.
```

De esta forma puedes utilizar WorkTracker manualmente o dejar que un agente te ayude a mantener el plan organizado.

---

## 6. No edites el JSON manualmente si no es necesario

Para el uso normal, trabaja desde WorkTracker o utiliza un agente siguiendo `WorkTracker-AGENT-GUIDE.md`.

El archivo `.json` contiene todos los datos del plan y su estructura. Editarlo manualmente con un editor de texto puede estropear el plan si se modifica su formato accidentalmente.

---

## 7. Exportar a Markdown

WorkTracker puede exportar una representación del plan en formato Markdown (`.md`).

Este archivo sirve para leer, compartir o documentar el plan.

**Importante:** el Markdown exportado no sustituye al archivo `.json` y no puede utilizarse para volver a importar el plan en WorkTracker.

Conserva siempre el archivo `.json` original.

---

## 8. Actualizar WorkTracker

Si aparece una nueva versión:

1. Vuelve a la página del proyecto en GitHub.
2. Descarga nuevamente el proyecto con **Code → Download ZIP**.
3. Extrae el nuevo ZIP.
4. Utiliza el nuevo archivo `Work-tracker-v4.html`.

Tus planes `.json` pueden guardarse en otra carpeta para evitar confundirlos con los archivos del programa.

---

## 9. Para usuarios de Git

Si ya utilizas Git, también puedes descargar el proyecto desde una terminal:

```bash
git clone <URL_DEL_REPOSITORIO>
```

Después entra en la carpeta:

```bash
cd <NOMBRE_DEL_REPOSITORIO>
```

Y abre:

`Work-tracker-v4.html`

Para obtener futuras actualizaciones:

```bash
git pull
```

---

## Estructura básica

Los archivos principales son:

```text
Work-tracker-v4.html
    Aplicación WorkTracker.

Example-plan.json
    Ejemplo de un plan.

WorkTracker-AGENT-GUIDE.md
    Instrucciones para que un agente de IA pueda ayudarte
    a organizar y actualizar el plan de forma segura.

tu-plan.json
    Tus propios planes.
```

Para una persona que únicamente quiera utilizar WorkTracker manualmente, normalmente solo necesita:

1. `Work-tracker-v4.html`
2. Su archivo de plan `.json`

Si además quiere que un agente de IA le ayude a organizar el proyecto, debe proporcionar también:

3. `WorkTracker-AGENT-GUIDE.md`

---

# English

## 1. Download WorkTracker

### Recommended option: download the ZIP file

You do not need to know how to program or install Git.

1. Open the project page on GitHub.
2. Click the green **Code** button.
3. Click **Download ZIP**.
4. Wait for the download to finish.
5. Open your **Downloads** folder.
6. Right-click the downloaded ZIP file.
7. Select **Extract All...**.
8. Open the newly created folder.

You will find the WorkTracker files inside.

---

## 2. Open WorkTracker

Find this file:

`Work-tracker-v4.html`

Double-click it.

WorkTracker will open in your web browser, for example:

- Google Chrome
- Microsoft Edge
- Firefox

You do not need to install any additional software.

> If Windows asks which application should open the file, select your normal web browser.

---

## 3. Open a plan

WorkTracker plans are files ending in:

`.json`

For example:

`Example-plan.json`

To open one:

1. Open `Work-tracker-v4.html`.
2. Click **Open**.
3. Select the `.json` file containing your plan.
4. The plan will appear in WorkTracker.

---

## 4. Save your changes

Once a plan is open, you can modify tasks, statuses, owners, notes and the Roadmap.

When WorkTracker has direct access to the opened file, it can save changes back to that file and use autosave.

Depending on your browser and how the file was opened, WorkTracker may instead download a new `.json` file.

If the plan contains important information, always keep a backup copy.

---

## 5. Use an AI agent to organise your tasks

The file:

`WorkTracker-AGENT-GUIDE.md`

is designed so you can give your plan to an AI agent and ask it to help you organise and maintain the project.

For example, you can ask the agent to:

- Add new tasks.
- Break large tasks into smaller subtasks.
- Reorganise tasks.
- Update task owners.
- Change task statuses.
- Add notes.
- Review pending work.
- Identify blocked or waiting tasks.
- Keep the Roadmap organised.
- Update the plan as the project progresses.

The guide tells the agent how to modify the `.json` file safely, preserve the existing project structure and avoid marking tasks as complete without evidence.

A simple workflow is to give your AI agent:

1. Your `.json` plan file.
2. `WorkTracker-AGENT-GUIDE.md`.
3. An instruction describing what you want it to organise or update.

For example:

```text
Read WorkTracker-AGENT-GUIDE.md and follow those rules when managing my plan.

Review the project, organise the pending work and break down tasks that are too large into clear subtasks. Do not mark anything as complete without evidence.
```

This allows you to use WorkTracker manually while also letting an AI agent help maintain the project.

---

## 6. Avoid manually editing the JSON file unless necessary

For normal use, make changes through WorkTracker or use an AI agent following `WorkTracker-AGENT-GUIDE.md`.

The `.json` file contains all the plan data and its structure. Editing it manually in a text editor can damage the plan if its format is accidentally changed.

---

## 7. Exporting to Markdown

WorkTracker can export a Markdown (`.md`) representation of your plan.

This is useful for reading, sharing or documenting the plan.

**Important:** the exported Markdown file does not replace the `.json` plan and cannot be imported back into WorkTracker.

Always keep the original `.json` file.

---

## 8. Updating WorkTracker

When a new version is available:

1. Return to the project page on GitHub.
2. Download the project again using **Code → Download ZIP**.
3. Extract the new ZIP file.
4. Use the new `Work-tracker-v4.html` file.

You may want to keep your own `.json` plans in a separate folder so they are not confused with the application files.

---

## 9. For Git users

If you already use Git, you can also download the project from a terminal:

```bash
git clone <REPOSITORY_URL>
```

Then enter the project folder:

```bash
cd <REPOSITORY_NAME>
```

Open:

`Work-tracker-v4.html`

To download future updates:

```bash
git pull
```

---

## Basic file structure

The main files are:

```text
Work-tracker-v4.html
    The WorkTracker application.

Example-plan.json
    Example plan.

WorkTracker-AGENT-GUIDE.md
    Instructions that allow an AI agent to help organise
    and safely update your project plan.

your-plan.json
    Your own plans.
```

For somebody who only wants to use WorkTracker manually, the two files normally needed are:

1. `Work-tracker-v4.html`
2. Their `.json` plan file

If they also want an AI agent to help organise the project, they should also provide:

3. `WorkTracker-AGENT-GUIDE.md`
