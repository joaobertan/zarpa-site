# zarpa-site

Página pública do app Zarpa, servida pelo GitHub Pages em `https://zarpa.joaobertan.com.br`.

- `/` redireciona para `/privacidade/`.
- `/privacidade/` é a política de privacidade e a página de suporte (mesma URL nos dois campos do App Store Connect).

HTML estático, sem build. O arquivo `CNAME` define o domínio; o DNS no Registro.br precisa de um
registro `CNAME zarpa -> joaobertan.github.io`. Em *Settings → Pages*, fonte `main` / raiz e
"Enforce HTTPS" ligado depois que o certificado for emitido.
