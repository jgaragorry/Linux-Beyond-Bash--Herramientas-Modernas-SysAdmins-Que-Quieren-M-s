# 🌐 Shell Evolved: Comandos Linux Que Redefinen la Terminal

> **Curso práctico y visual para administradores de sistemas que quieren dominar los comandos más modernos, eficientes y productivos directamente desde la terminal en Ubuntu Server 24.04 LTS**

---

## 🎯 Objetivo del curso

Capacitar a administradores y profesionales de IT para adoptar herramientas modernas de línea de comandos que aumenten la productividad, claridad visual y eficacia en tareas administrativas sin entorno gráfico.

---

## 👤 Dirigido a:

- SysAdmins que usan servidores sin entorno gráfico (headless)
- Técnicos que administran desde SSH, WSL o VM
- DevOps que automatizan tareas y monitorean recursos
- Estudiantes de Linux con base sólida en comandos clásicos

---

## ✅ Beneficios del curso

- Mejora inmediata de experiencia en terminal
- Productividad real en gestión de archivos, rendimiento y diagnóstico
- Compatibilidad con VMs locales (VirtualBox), WSL y servidores en la nube
- Prácticas funcionales desde TTY
- Evolución profesional hacia una administración moderna y ágil

---

## ⚙️ Requisitos técnicos

- Ubuntu Server 24.04 LTS (en WSL, VM o Cloud)
- Acceso `sudo`
- Conexión a internet

### Recomendado:
- Familiaridad básica con comandos tradicionales (`ls`, `cat`, `du`, `ps`, `cd`, etc.)

---

## 🧱 Estructura del repositorio

```bash
shell-evolved-linux/
├── README.md                          # Documento principal del curso
├── scripts/                           # Scripts por módulo para instalación automática
│   ├── modulo1_instalar_exploradores.sh
│   ├── modulo2_instalar_procesos.sh
│   ├── modulo3_instalar_automatizacion.sh
│   └── modulo4_instalar_diagnostico.sh
├── ejercicios/                        # Prácticas funcionales por módulo
│   ├── modulo1_exa_bat_dust.md
│   ├── modulo2_btm_procs_hyperfine.md
│   ├── modulo3_just_entr_zoxide.md
│   └── modulo4_dog_rg_gdu.md
└── LICENSE                            # Licencia del proyecto (MIT)
```

---

## 🛠️ Preparación inicial (recomendado ejecutar primero)

```bash
sudo apt update && sudo apt install -y curl wget unzip snapd cargo fzf ripgrep entr
```

> ⚠️ En WSL, algunos paquetes vía `snap` pueden fallar. Se recomienda usar `cargo` o binarios `.deb` cuando sea necesario.

---

## 📦 Módulos del curso

| Módulo | Enfoque | Herramientas |
|--------|---------|--------------|
| 1️⃣ Exploradores visuales | Archivos y discos | `exa`, `bat`, `dust`, `duf` |
| 2️⃣ Procesos y rendimiento | Recursos del sistema | `btm`, `procs`, `hyperfine` |
| 3️⃣ Automatización CLI | Productividad real | `just`, `entr`, `zoxide` |
| 4️⃣ Diagnóstico y red | Filtros y búsquedas | `dog`, `ripgrep`, `gdu` |

Cada módulo incluye:
- Script de instalación
- Ejercicios funcionales desde TTY
- Comparaciones contra comandos tradicionales

---

## 🚀 Laboratorio final

Ejercicio integrado con uso de herramientas de todos los módulos para:
- Automatizar tareas comunes (`just`)
- Diagnosticar errores de red (`dog`)
- Auditar uso de disco (`gdu`, `dust`)
- Medir eficiencia (`hyperfine`)

---

## 📤 Compatibilidad y ejecución

✅ 100% funcional en:
- Ubuntu Server 24.04 LTS (nativo, VM VirtualBox, VPS)
- WSL2 (parcial — puede requerir binarios directos por falta de soporte `snap`)
- Consolas TTY, SSH y terminales sin GUI

---

## ✨ Contribuciones y mejora

Este curso se encuentra en constante mejora. Puedes adaptar los scripts a tu distro o entorno si es necesario. Se aceptan pull requests y sugerencias para nuevos comandos o ejercicios.

---

¿Listo para redefinir tu forma de trabajar con Linux?

🔸 ¡Ejecuta el primer script de instalación y comienza el viaje!

```bash
bash scripts/modulo1_instalar_exploradores.sh
```
