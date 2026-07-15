# Equipo Dinamita

## Integrantes y roles

| Integrante | Rol | Archivos |
|---|---|---|
| Joaquín Antonino | Líder técnico / Analista funcional | `about.html`, `about.css` |
| Joaquín Esposito | Backend / Data Engineer / Ciberseguridad | `index.html`, `home.css`, `style.css` |
| Demián Cirión | Frontend / UI-UX / QA | `contact.html`, `contact.css`, `style.css` |

---

## Problemas y soluciones

### Conflicto con los estilos
Al principio solo teníamos un `style.css` compartido y no sabíamos cómo trabajar los tres sobre él sin pisarnos los estilos entre nosotros.

**Solución:** decidimos crear un CSS por página (`home.css`, `about.css`, `contact.css`) además del global, así cada uno tocaba únicamente su archivo.

### Pushes accidentales a main
En algunas ocasiones se hicieron pushes directamente a `main` en lugar de a la branch correspondiente.

**Solución:** revertimos los commits incorrectos consultando con IA, y ajustamos el flujo de trabajo para evitar que vuelva a pasar.