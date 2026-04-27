# 🚀 LinkedIn Profile Transformer — Copy-Paste Version

> Para usar con **Claude.ai común** (web o app móvil), sin necesidad de extensiones de browser.
> Vos copiás manualmente tu perfil de LinkedIn y se lo pegás a Claude. Claude te devuelve el rewrite, y vos pegás los cambios en LinkedIn.

---

## 📋 Cómo usar este prompt

1. Abrí [claude.ai](https://claude.ai) o la app de Claude.
2. **Antes de pegar el prompt**, contestá el mini-cuestionario abajo.
3. Recopilá el texto actual de tu perfil de LinkedIn:
   - Andá a tu perfil → Copiá manualmente headline, about, cada experiencia, skills, languages, certifications.
   - **O usá la opción oficial:** LinkedIn → Settings & Privacy → Data Privacy → "Get a copy of your data" → tildá "Profile" → recibís un archivo HTML/CSV con todo en pocos minutos.
4. Pegá el prompt completo (cuestionario + perfil) en el chat con Claude.
5. Seguí las instrucciones campo por campo y aplicá cada cambio en LinkedIn directamente vos.

---

## 🧭 Mini-cuestionario (rellená esto primero)

Tomate 3 minutos. Cuanto más claro tu target, mejor el rewrite.

```
1. URL de mi LinkedIn:
   →

2. Idioma de respuestas (Claude responde en):
   → [español / inglés / otro]

3. Mi situación actual:
   → [activo en búsqueda / passive candidate / open to relocate / freelance]

4. Mi objetivo de carrera (elegí UNA línea principal):
   → [a] Mismo nivel, mejor empresa
   → [b] Subir nivel (Senior / Lead / Manager / Director)
   → [c] Mismo nivel O subir (mantener flexible)
   → [d] Pivot a otra industria/función — especificá:
   → [e] Freelance / consulting independiente
   → [f] Otro:

5. Industrias o tipos de empresa target (2-4 ejemplos):
   →

6. Ubicaciones aceptables (remoto, híbrido, ciudades específicas):
   →

7. Idiomas que hablás y nivel:
   →

8. ¿Tu empleador actual NO debe enterarse de que estás abierto?
   → [sí / no / no me importa]

9. CV o info de respaldo (pegá texto o adjuntá archivo):
   →
```

---

## 🤖 PROMPT PARA PEGAR EN CLAUDE.AI

(Copiá todo lo de abajo, incluyendo tus respuestas del cuestionario y el perfil actual.)

---

```
Sos un coach experto en LinkedIn especializado en transformar perfiles
profesionales para maximizar visibilidad ante recruiters globales.
Vamos a hacer una revisión completa de mi perfil en dos pasadas
metódicas. Yo aplico los cambios manualmente — vos generás el contenido
y me decís dónde clickear.

═══════════════════════════════════════════════════════════════════
MI INFO (rellená estos campos antes de empezar)
═══════════════════════════════════════════════════════════════════

URL de mi perfil: [PEGAR_URL]
Idioma de respuestas: [español / inglés]
Mi situación: [activo / passive / open to relocate / freelance]
Objetivo de carrera: [mismo nivel / subir / mantener flexible / pivot a X / freelance]
Industrias target: [...]
Ubicaciones aceptables: [...]
Idiomas que hablo y nivel: [...]
¿Empleador actual no debe enterarse?: [sí / no]
CV / info clave:
[PEGAR_O_ADJUNTAR]

═══════════════════════════════════════════════════════════════════
TEXTO ACTUAL DE MI PERFIL DE LINKEDIN (copy-paste manual de cada
sección — incluí TODO aunque esté vacío o repetido):
═══════════════════════════════════════════════════════════════════

HEADLINE:
[...]

ABOUT / Sobre mí:
[...]

EXPERIENCE / Experiencia:
(Para cada rol: Cargo | Empresa | Fechas | Ubicación | Descripción)

Rol 1:
- Cargo:
- Empresa:
- Fechas:
- Ubicación:
- Descripción:

Rol 2:
[...]

(Repetir para todos los roles, en orden)

EDUCATION / Educación:
[...]

LICENSES & CERTIFICATIONS:
[... o "vacío"]

SKILLS / Aptitudes (top 10 en orden, con endorsements si visibles):
[...]

LANGUAGES / Idiomas:
[...]

RECOMMENDATIONS:
- Recibidas: [N]
- Enviadas: [N]

═══════════════════════════════════════════════════════════════════
QUÉ NECESITO DE VOS
═══════════════════════════════════════════════════════════════════

PASO 1 — DIAGNÓSTICO
Tabla "Antes vs. Debería decir" para cada sección. Identificá:
- Headline débil o desactualizado
- Typos (¡importantes!) en títulos de cargo
- Roles con descripción vacía
- Skills broken — auto-traducciones tipo "Washing" por "Lavado",
  skills en lowercase sin match al graph oficial de LinkedIn
- Secciones vacías (Languages, Certifications, About)
- Keywords críticos del target que faltan en headline + about + skills

PASO 2 — REWRITE COMPLETO
Generá el contenido nuevo de cada sección, optimizado para recruiter
search. Decime exactamente:
- Headline nuevo (≤220 caracteres, con keywords del target)
- About nuevo
- Descripción nueva de cada experiencia + 5 skills tagged por rol
- Education completa con descripción y acreditaciones relevantes
- Top 10 skills globales (ordenadas — las primeras 3 son las que
  LinkedIn destaca como "top skills")
- Languages
- Certifications con todos los campos
- Cualquier título de cargo que haya que renombrar

PASO 3 — PLAN DE EJECUCIÓN EN DOS PASADAS
Dividilo en:

Pasada 1 (~20 min): Headline + typos críticos + Languages + About
Pasada 2 (~40 min): Experiencias + Skills + Certifications

Para cada campo dame:
- Dónde clickear en LinkedIn (paso a paso, navegación literal)
- Texto en bloque de código listo para copy-paste
- Recordatorio de desactivar "Notify network" antes de guardar

═══════════════════════════════════════════════════════════════════
REGLAS
═══════════════════════════════════════════════════════════════════

- Trabajemos campo por campo. Esperá mi "done X" antes de mandar el
  siguiente.
- Si soy passive candidate, NO recomiendes activar el frame público
  #OpenToWork. Solo el toggle interno "Recruiters only" — y aclará
  que no garantiza 100% privacidad.
- No me digas "subí tu perfil" o "edité tu LinkedIn" — vos generás
  el contenido, yo lo aplico.
- Mantenete honesto: si algo del CV es débil para el target, decímelo
  en lugar de inflar.
- Si no entendés alguna parte del perfil que pegué, preguntame en
  lugar de inventar.

═══════════════════════════════════════════════════════════════════
ARRANCÁ POR EL PASO 1 (diagnóstico) cuando tengas mi info.
═══════════════════════════════════════════════════════════════════
```

---

## 💡 Tips mientras trabajás

- **Desactivá "Notify network" en cada save** — si no, tus contactos del trabajo actual reciben un feed con cada edit.
- Hacé el diagnóstico + rewrite en una sesión, y la aplicación de cambios en LinkedIn en otra. Cansa menos.
- Si LinkedIn te muestra una sección rara o un modal nuevo (cambian la UI seguido), sacá screenshot y mandáselo a Claude para que te oriente sobre dónde clickear.
- Después del rewrite completo, esperá 7–14 días antes de evaluar resultados (apariciones en búsquedas, InMails, vistas de perfil).

## ⚠️ Caveats honestos

- **El toggle "Recruiters only"** de LinkedIn reduce la visibilidad pública de tu búsqueda, pero **no es 100% privado** — alguien con LinkedIn Recruiter Lite en tu empresa actual te puede ver con la insignia.
- **Esta versión es 100% manual** — Claude no toca tu cuenta. Eso es más seguro pero más lento. Si querés automatización, mirá la versión "Side Panel".
- **Pegá el perfil con honestidad.** Si maquillás la info inicial, el rewrite te puede vender en algo que no podés sostener en una entrevista.
