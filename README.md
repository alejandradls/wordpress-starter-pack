# 🚀 Starter Pack de Plugins para WordPress  
Lista de plugins esenciales que uso para iniciar cualquier proyecto de WordPress.  
Este archivo permite instalar todos los plugins de forma automática mediante un paquete `.txt`.

---

## 📥 Descargar el Starter Pack

Haz clic para obtener el archivo:  
**wordpress-starter-pack.txt**

Este archivo contiene los slugs oficiales de los plugins, listos para usar en instalaciones masivas.

---

## 🔧 Plugins incluidos

- Autoptimize  
- Smush  
- SVG Support  
- Contact Form 7  
- Honeypot for Contact Form 7  
- UpdraftPlus  
- WP-Optimize  
- iThemes Security  
- LiteSpeed Cache  
- Yoast SEO  

---

## 🧰 Cómo instalar todos los plugins automáticamente

Tienes dos opciones, dependiendo de tu experiencia técnica:

---

# ✅ Método 1 — Instalación masiva (sin código) 
### Usando el plugin Bulk Plugin Installation

1. Instala el plugin desde el repositorio:  
   **Bulk Plugin Installation**

2. Ve al panel del plugin.

3. Sube el archivo:  
   **starter-stack-alejandra.txt**

4. Da clic en **Install Now**.

WordPress instalará y activará todos los plugins incluidos en el paquete.  
Este método es ideal para desarrolladores principiantes.

---

# ✅ 
Método 2 — Instalación masiva con WP-CLI (usuarios avanzados)

Si trabajas con WP-CLI en local o servidor, usa este comando:

```bash
wp plugin install $(cat starter-stack-alejandra.txt) --activate
