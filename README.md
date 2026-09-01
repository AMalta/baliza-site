# Baliza — site

Páginas públicas do **Baliza**, sistema de apoio à vistoria de embarcação
pesqueira conforme a Portaria MPA nº 397/2024 e o Anexo IV.

| arquivo | conteúdo |
|---|---|
| `index.html` | apresentação do sistema |
| `manual.html` | manual do usuário |

Publicado com GitHub Pages. Não há código de aplicação aqui — só as páginas.

## Publicar

**Settings → Pages → Deploy from a branch**, com a branch `master` e a pasta
`/ (root)`.

## Atualizar

Estas páginas são geradas a partir do repositório do sistema, na pasta
`docs/`. Para trazer a versão mais recente, rode lá:

```bash
python tools/publicar_site.py
```

Ele copia os arquivos para cá e mostra o que mudou. Editar direto neste
repositório funciona, mas a próxima cópia sobrescreve — o original é o outro
lado.
