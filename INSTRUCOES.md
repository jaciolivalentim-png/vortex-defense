# Atualização do portfólio da Vortex Digital

No repositório `vortex-digital`, abra `main.jsx`. Procure `const projects = [` e substitua SOMENTE o array de projetos pelo conteúdo de `projects-snippet.jsx`.

No mesmo arquivo, encontre o bloco `project-info` que apresenta cada projeto e adicione o link dentro do cartão, depois da descrição, usando:

```jsx
<a href={p.url} target="_blank" rel="noopener noreferrer" className="text-link">Ver projeto ↗</a>
```

Cole no FINAL do `style.css`:

```css
.project-info .text-link {display:inline-flex;margin-top:15px;color:#d6ad69;text-decoration:none;font-size:13px;font-weight:700}
```

Substitua `COLE_AQUI_URL_DPM_DEMO` e `COLE_AQUI_URL_VORTEX_DEFENSE` pelos endereços públicos reais após publicar as duas demos no Render.

A demo DPM é simulação inteiramente fictícia, sem conexão ao sistema real, sem upload de documentos e sem IA. O jogo usa Three.js importado de CDN, portanto requer conexão à internet.
