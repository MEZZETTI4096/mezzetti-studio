# Deploy do site Mezzetti⁴⁰⁹⁶



## Opção B — GitHub Pages (mais gratuito, controle total)

**Tempo total: ~10 minutos. Custo: zero, sempre.**

1. Crie conta em [github.com](https://github.com) se ainda não tem.
2. Crie um repositório público chamado `mezzetti-studio` (ou qualquer nome).
3. Faça upload dos arquivos da pasta `site/` para o repositório (interface web aceita drag-and-drop).
4. No repositório → **Settings → Pages**.
5. Em **Source**, escolha branch `main` e folder `/ (root)`. Salve.
6. Em ~1 minuto, o site fica em `https://[seu-usuario].github.io/mezzetti-studio/`.
7. Para domínio próprio `mezzetti.studio`: no campo **Custom domain**, digite `mezzetti.studio`. Aponte um CNAME no DNS do registrador apontando para `[seu-usuario].github.io`.

**Vantagens:** versionamento Git nativo, histórico de mudanças, totalmente gratuito.

## Comprar o domínio mezzetti.studio

O domínio `.studio` está disponível em qualquer registrador (Registro.br não vende `.studio`, então use internacional):

- [Namecheap](https://www.namecheap.com) — ~US$ 30/ano, interface simples
- [Cloudflare Registrar](https://www.cloudflare.com/products/registrar/) — preço de custo, sem markup (mais barato no longo prazo)
- [Hostinger](https://www.hostinger.com.br) — em português, aceita pix

Depois de comprar, aponte o DNS para o serviço de deploy escolhido (Vercel ou GitHub Pages).

## Próximos passos sugeridos

1. Escolha um caminho (Vercel para velocidade, GitHub Pages para custo zero).
2. opção alternativa
3. Faça o deploy inicial e configure o domínio próprio.
4. Atualize o site sempre que houver mudança (novo serviço, frase, ou eventualmente cases de portfólio).

Qualquer dúvida durante o processo: cole o erro aqui e a gente resolve.
