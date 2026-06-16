# TODO — Guía VS Code para clientes

**Estado:** guía completa y publicada → https://meowrhino.github.io/guiaVSCode/

Todo lo de abajo es **opcional**. La guía ya funciona y está lista para pasar a clientes tal cual.

---

## Opcional (cuando apetezca)

- [ ] Captura del diálogo **«Do you trust the authors…»** (paso 4)
- [ ] Captura del **login de GitHub**: icono *Accounts* → «Sign in with GitHub» (paso 8)
- [ ] Captura de un **`.json` con subrayado rojo** de error (paso 6)
- [ ] Captura de **«Open Folder»** / pantalla de bienvenida (paso 4)
- [ ] Primer plano de la **ramita `main`** abajo a la izquierda (paso 4)
- [ ] Botón **«letra más grande»** (A+ / A−) para accesibilidad extra
- [ ] Versión **imprimible / PDF**

## Por cliente (al entregar la guía a cada uno)

- [ ] Rellenar la lista **«para cambiar X → edita el archivo Y»** (paso 6)
- [ ] Poner la **dirección pública** de su web (paso 9)
- [ ] (Si hace falta) la **URL del repo** para clonar (paso 4)

---

## Notas técnicas

- Los **originales** de las capturas están en la carpeta local `capturas/` (excluida del repo en `.gitignore`, para no publicar contenido de cliente).
- Para **añadir una captura nueva**: pásala a `.webp`, ponla en `img/`, y enlázala con:
  ```html
  <figure class="shot sm">
    <img src="img/nombre.webp" alt="descripción" loading="lazy" width="..." height="...">
    <figcaption>Pie de foto.</figcaption>
  </figure>
  ```
  (quita `sm` para imágenes grandes a todo el ancho). Luego: commit + push.
- Las imágenes actuales pesan ~211 KB en total (webp).

## Ya hecho ✓

- Contenido verificado contra la documentación oficial de VS Code (2026)
- Revisado: precisión técnica, accesibilidad y lenguaje para todos los niveles
- Estilo de la familia meowrhino (Inknut, monocromo, favicon, firma)
- Interruptor Mac/Windows · checklist con progreso · glosario
- 9 capturas en los pasos clave (5, 6, 7, 8 y vocabulario)
- Repo público + GitHub Pages activo
