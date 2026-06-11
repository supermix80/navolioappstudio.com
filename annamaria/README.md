# Annamaria Cerbone — GitHub Pages package

Pagine pubbliche statiche pronte per essere pubblicate su `navolioappstudio.github.io`.

## File

- `index.html` — landing principale
- `faq.html` — domande frequenti
- `chi-sono.html` — profilo agente
- `privacy.html` — informativa privacy del form lead

## URL attesi

- `/navolioappstudio/annamaria/`
- `/navolioappstudio/annamaria/faq.html`
- `/navolioappstudio/annamaria/chi-sono.html`
- `/navolioappstudio/annamaria/privacy.html`

## Nota backend

La landing è già predisposta per inviare il form lead al backend.

Per rendere il form operativo su GitHub Pages, bisogna esporre un backend server-side e impostare:

```html
<script>
  window.AGENTE_API_BASE_URL = "https://tuo-backend.example.com";
</script>
```

prima dello script di submit, oppure modificare la costante JS nella pagina.
