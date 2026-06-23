# Método Dólar — Landing Page

Landing page do **Método Dólar** (Leonardo Dorea). Página estática, standalone (sem build).

## Estrutura
- `metodo-dolar.html` — a página completa
- `assets/` — imagens, fontes (woff2), runtime e fotos

## Rodar localmente
Qualquer servidor estático serve. Ex.:

```bash
python3 -m http.server 8123
```

Depois abra: <http://localhost:8123/metodo-dolar.html>

## Checkout
Os CTAs apontam para o checkout da Kiwify e repassam automaticamente os
parâmetros de UTM da URL (utm_source, utm_medium, utm_campaign, fbclid, etc.).
Ex.: acessar a página com `?utm_source=instagram&utm_campaign=lancamento`
faz o link do checkout herdar esses parâmetros.
