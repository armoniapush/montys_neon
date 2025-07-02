
---

# 👾 Monty's Neon

### *Un Tema Cyberpunk para Oh My Posh*

Un tema diseñado para entusiastas de la estética retrofuturista: **minimalismo funcional con alma de neón**.
Inspirado en consolas de ciencia ficción, *Monty’s Neon* transforma tu terminal en una interfaz que parece sacada directamente de *Blade Runner* o *Ghost in the Shell*.

> ⚠️ **Nota:** Reemplaza la URL de la imagen de vista previa con la tuya propia después de subirla a tu repositorio.

---

## ✨ Filosofía de Diseño

Este tema evita el caos visual. Se enfoca en lo esencial, con una identidad visual marcada por:

* **🧠 Claridad Distópica**
  Cada elemento tiene su espacio. Nada está ahí por azar. Todo transmite *solo lo necesario*.

* **🔧 Minimalismo Funcional**
  Solo verás lo que importa: contexto de shell, usuario, ubicación, estado del comando. Sin relleno.

* **🌃 Estética Neón**
  Colores saturados sobre fondo oscuro. Como vallas publicitarias en una noche lluviosa.

---

## 🤖 Estructura y Segmentos

El prompt se organiza en **tres líneas limpias**, como una consola de datos en tiempo real:

| Línea | Icono | Segmento | Descripción                                                   |
| ----- | ----- | -------- | ------------------------------------------------------------- |
| 1     | 셸     | Shell    | Muestra la versión actual de la shell (ej. PowerShell 7.5.2). |
| 2     | ⚡     | Sesión   | Alerta visual (rojo neón) si estás en modo administrador.     |
| 2     |      | Usuario  | Tu alias o nombre en red.                                     |
| 2     |      | Ruta     | Muestra la ruta actual (`~` para home).                       |
| 2     | ♡     | Estado   | Corazón púrpura si el último comando fue exitoso.             |
| 3     |      | Hora     | Hora del sistema, para referencia constante.                  |
| 3     | ❯     | Prompt   | Cursor minimalista. Espera tus órdenes.                       |

---

## 🎨 Paleta Cyberpunk Neón

Una combinación de alto contraste para legibilidad perfecta y atmósfera visual poderosa:

| Color               | Uso                                         |
| ------------------- | ------------------------------------------- |
| `#f50742` Rojo Neón | Alertas críticas (modo admin, errores).     |
| Lavanda/Púrpura     | Indicadores de estado y toques estilizados. |
| Blanco/Gris Claro   | Texto legible sobre fondo oscuro.           |
| Azul Medianoche     | Fondo. Sombra digital de la ciudad.         |

---

## 🚀 Instalación

### 🔧 Requisitos Previos

* **Oh My Posh** (motor del prompt).
* **Nerd Font** instalada y activada (ej. *FiraCode Nerd Font*) para renderizar íconos y glifos.

### 📦 Pasos

1. **Descarga el archivo del tema:**
   Guarda el JSON como `montys_neon.omp.json` en una ubicación estable (ej. tu carpeta de usuario).

2. **Edita tu configuración de shell:**

#### PowerShell:

```powershell
oh-my-posh init pwsh --config 'C:\ruta\a\tu\montys_neon.omp.json' | Invoke-Expression
```

#### Bash:

```bash
eval "$(oh-my-posh init bash --config '~/ruta/a/tu/montys_neon.omp.json')"
```

#### Zsh:

```bash
eval "$(oh-my-posh init zsh --config '~/ruta/a/tu/montys_neon.omp.json')"
```

3. **Recarga tu terminal:**

   * PowerShell: `source $PROFILE`
   * Zsh: `source ~/.zshrc`

Una vez hecho... conexión establecida.

---

## 🛠️ Personalización

Lo bello de *Monty's Neon* es su sencillez.
¿Quieres otro icono? ¿Un color distinto?
Abre `montys_neon.omp.json` y cambia lo que quieras.
Todo está claro, legible, listo para ser modificado.

---

> **Cromo, código y neón.**
> El futuro ya no es mañana. Es tu terminal.

---
