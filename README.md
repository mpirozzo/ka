# 💪 Piso Firme — Ejercicios de Kegel para hombres

App personal, **manos libres**, pensada para hacer los ejercicios **desde el auto** (u otro rato muerto). Te guía por **voz** y con una **animación simple**, así ejercitás sin mirar la pantalla.

Brilla por su simpleza: elegís objetivo → elegís nivel → tocás **Empezar**. El resto lo maneja la voz.

---

## 🎯 Tres programas según el objetivo

Cada objetivo entrena el piso pélvico distinto, según lo que dice la evidencia:

| Programa | Para qué sirve | Cómo entrena |
|---|---|---|
| 🛡️ **Continencia** | Menos pérdidas / escapes de orina (goteo, esfuerzo, tos) | Contracciones **rápidas** (cierran la uretra ante el esfuerzo) + **retenciones largas** de sostén |
| ⏱️ **Control eyaculatorio** | Prolongar y controlar la eyaculación | Protocolo tipo **Pastore**: retenciones lentas 10s + rápidas 1s, para dominar el reflejo |
| 🔥 **Erecciones** | Más firmeza y rigidez | Contracciones **máximas sostenidas** tipo **Dorey**: mejoran el retorno venoso. De sentado → parado |

Cada programa tiene **3 niveles** (de principiante a avanzado) que suben las repeticiones y el tiempo de retención.

---

## 🗣️ Manos libres

- **Guía por voz:** la app te dice *"contraé… mantené… soltá"* y marca el ritmo con pitidos suaves. No necesitás mirar.
- **Comandos de voz:** decí **"empezá"**, **"pausa"**, **"seguí"**, **"siguiente"** o **"terminá"** para manejarla sin manos.
  *(Necesita permiso de micrófono; anda mejor en Chrome. Con mucho ruido de ruta puede fallar.)*
- **Pantalla siempre encendida** durante la sesión.
- **Animación clara:** un anillo que se llena y un orbe que crece al contraer y se achica al soltar, con la cuenta grande en el centro.

Todo se configura en **⚙️ Ajustes** (podés apagar voz, pitidos o comandos).

---

## 🚗 Uso en el auto (importante)

Los Kegel son **contracciones internas e invisibles**: se pueden hacer manejando sin que nadie lo note y sin soltar el volante.

Pero por seguridad:

1. **Configurá la sesión con el auto detenido** (elegí objetivo, nivel y tocá Empezar).
2. Una vez en marcha, **no mires ni toques la pantalla**: dejá que te guíe la voz.
3. Los comandos de voz te dejan pausar/terminar sin usar las manos.

---

## 📲 Instalar como app (recomendado)

Es una PWA: se instala en el teléfono y funciona **offline** y a pantalla completa.

- **iPhone (Safari):** Compartir → *Agregar a inicio*.
- **Android (Chrome):** menú ⋮ → *Instalar app* / *Agregar a pantalla de inicio*.

También funciona abriéndola en cualquier navegador.

---

## 🧠 Cómo hacer la contracción correcta

1. Apretá como si **aguantaras las ganas de orinar** o de **retener un gas** (movimiento de "elevar hacia adentro").
2. **No** aprietes abdomen, glúteos ni piernas. La panza no se endurece.
3. **Respirá normal**, no contengas el aire. Soltá del todo entre contracción y contracción.
4. Constancia: los resultados suelen aparecer en **4 a 12 semanas**, con 1–2 sesiones por día.

> ⚠️ No hagas Kegel cortando el chorro al orinar de forma habitual: solo sirve una vez para identificar el músculo, y repetirlo puede favorecer infecciones.

---

## 🚀 Ver / probar

- Es un sitio estático de un solo `index.html`. Se puede publicar en **GitHub Pages** y abrir desde el celular.
- Para probarlo local: abrí `index.html` en el navegador. *(Para que anden los comandos de voz y la instalación PWA conviene servirlo por HTTPS, p. ej. GitHub Pages.)*

### Publicar en GitHub Pages
1. Subí esta carpeta a un repo.
2. En el repo: **Settings → Pages → Branch: `main` / root → Save**.
3. En un minuto tenés la URL pública (algo como `https://TU-USUARIO.github.io/piso-firme/`).

---

## 📁 Contenido

```
index.html                 · toda la app (HTML + CSS + JS, sin dependencias)
manifest.webmanifest       · configuración PWA
sw.js                      · service worker (offline)
icon-192 / 512 / maskable  · íconos
README.md                  · esto
```

---

## ⚕️ Aviso

Esta app es una herramienta de **bienestar y hábito**, no un tratamiento médico ni un diagnóstico. La información se basa en fuentes de divulgación y estudios sobre entrenamiento del piso pélvico, pero cada persona es distinta. Si tenés **dolor, pérdidas persistentes, disfunción eréctil o eyaculatoria que te preocupa**, consultá a un médico/urólogo o kinesiólogo de piso pélvico. Ante síntomas nuevos o que empeoran, buscá evaluación profesional.

---

## 📚 Fuentes

- Mayo Clinic — *Kegel exercises for men: Understand the benefits*. https://www.mayoclinic.org/healthy-lifestyle/mens-health/in-depth/kegel-exercises-for-men/art-20045074
- Cleveland Clinic — *Kegel Exercises for Men*. https://my.clevelandclinic.org/health/treatments/22211-kegel-exercises-for-men
- Harvard Health — *Step-by-step guide to performing Kegel exercises*. https://www.health.harvard.edu/step-by-step-guide-to-performing-kegel-exercises
- NIDDK (NIH) — *Kegel Exercises*. https://www.niddk.nih.gov/health-information/urologic-diseases/kegel-exercises
- Pastore AL, et al. — *Pelvic floor muscle rehabilitation for patients with lifelong premature ejaculation*, Therapeutic Advances in Urology (2014). https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6858748/
- Dorey G, et al. — *Developing a pelvic floor muscle training regimen* / trabajos sobre PFMT y disfunción eréctil, Physiotherapy.
