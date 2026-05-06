# Arrancá con Fuerza

Sistema de gestión de gimnasios — landing page informativa.

🔗 **Demo:** [antoninojoaquin.github.io/arrancaconfuerza](https://antoninojoaquin.github.io/arrancaconfuerza/)

---

## Equipo Dinamita

| Integrante | Rol | Archivos |
|---|---|---|
| Joaquín Antonino | Líder técnico / Analista funcional | `about.html`, `about.css` |
| Joaquín Esposito | Backend / Data Engineer / Ciberseguridad | `index.html`, `home.css`, `style.css` |
| Demián Cirión | Frontend / UI-UX / QA | `contact.html`, `contact.css`, `style.css` |

---

## Estructura

```
├── index.html
├── about.html
├── contact.html
├── style.css
├── home.css
├── about.css
└── contact.css
```

---

## Problemas y soluciones

**Conflicto con los estilos**
Solo teníamos un `style.css` compartido y no sabíamos cómo trabajar los tres sin pisarnos. Lo resolvimos creando un CSS por página además del global, así cada uno tocaba únicamente su archivo.

**Pushes accidentales a main**
En algunas ocasiones se pusheó directamente a `main` en lugar de a la rama correspondiente. Lo resolvimos revirtiendo los commits y consultando con IA.
