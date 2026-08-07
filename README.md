# Rosanna Overholser — personal hub

Source for **https://roverhol.github.io/** (GitHub user site).

Teaching Overview remains a separate project site:  
**https://roverhol.github.io/teaching-overview/**

## Local preview

```bash
cd path/to/roverhol.github.io
quarto preview
```

## Create / deploy on GitHub (one-time)

The local repo is ready with a Pages workflow. The remote `roverhol.github.io` does not exist yet—create it, then push:

1. On GitHub: **New repository** named exactly `roverhol.github.io` (public), no README.
2. Locally:

```bash
cd path/to/roverhol.github.io
git remote add origin https://github.com/roverhol/roverhol.github.io.git
git push -u origin main
```

3. Repo **Settings → Pages → Build and deployment**: Source = **GitHub Actions**.
4. After the workflow succeeds, the hub is at `https://roverhol.github.io/`. Teaching Overview at `/teaching-overview/` is unchanged.

## Place themes

| Area | Theme CSS |
|------|-----------|
| Home, About, Projects index | `assets/css/valley-theme.css` |
| CPH courses | `humboldt-theme.css` |
| Open materials | `library-theme.css` |
| Learning | `sierra-theme.css` |
| Medical projects | `umea-theme.css` |
| Misc | `anza-theme.css` |

See `docs/ia.md` for nav locks and `docs/intake.md` for the first intake classification.
