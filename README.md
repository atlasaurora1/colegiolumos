# Colégio Lumos

Landing page estática, responsiva e mobile-first para o Colégio Lumos.

## Publicar no GitHub Pages

1. Faça merge das alterações na branch `main`.
2. No repositório, abra **Settings → Pages** e selecione **GitHub Actions** em **Build and deployment → Source**.
3. A execução do workflow **Deploy static site to GitHub Pages** publica a página. O endereço inicial do repositório de projeto é `https://atlasaurora1.github.io/colegiolumos/`.

O workflow também pode ser executado manualmente pela aba **Actions**.

## Atualizar o site

- `index.html`: textos, links e contatos.
- `styles.css`: identidade visual e layout responsivo; regras base são mobile-first.
- `script.js`: navegação móvel e atualização do ano no rodapé.
- `.github/workflows/pages.yml`: publicação automática.

O logo está carregado do endereço público usado pelo site atual do Lumos. Antes de migrar o domínio, salve o logo dentro do repositório e altere o `src` correspondente em `index.html`, para não depender do domínio antigo.

## Conteúdo a validar antes do lançamento

Esta versão usa apenas informações confirmadas: etapas do berçário ao ensino médio, projeto bilíngue do maternal ao ensino médio, integral até o 5º ano, projeto Maker, apoios pedagógicos no contraturno, matrículas 2027, endereço e contatos. Acrescente fotos autorizadas e detalhes pedagógicos após validação da escola. Não foram inventados depoimentos, horários ou resultados.
