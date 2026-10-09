# CidadanIA — Guia completo do vídeo

Site explicativo em português sobre o vídeo do CidadanIA Digital. Inclui 60 capítulos, divididos entre apresentação do projeto e explicação do código, e 26 páginas de leitura e referência. Inclui apresentação do jogo, arquitetura, fluxo de análise, regras de pontuação, API, instalação e uma página para cada dependência direta do aplicativo.

## Abrir

Abra `index.html` no navegador ou execute `python3 -m http.server 8080` nesta pasta e acesse http://localhost:8080. Não precisa de npm, backend ou chave de IA.

## Editar

- `assets/content.js`: artigos e inventário de bibliotecas.
- `assets/style.css`: aparência e responsividade.
- `assets/app.js`: navegação, busca e tema.

O conteúdo técnico foi conferido no repositório Marcoxt67/CidadanIA, revisão `809a3baf93573284572808161a997a34f8b1b885`. As versões são faixas declaradas nos package.json. As dependências transitivas não estão descritas como escolhas diretas.

## Publicar no GitHub Pages

Em Settings → Pages, selecione **GitHub Actions** como origem. O workflow publica somente `index.html` e `assets/`. Execute a ação “Publicar wiki” ou envie alterações para main.

Endereço esperado após publicação: https://marcoxt67.github.io/CidadanIA-Wiki/ (a existência deste endereço depende da conclusão do deployment).

## Diferenças entre vídeo e código

Os capítulos sinalizam divergências do código consultado: critérios do README, interface e prompt; validação compacta que exige três intervenções; ausência de detalhamento individual na resposta compacta; e conferência do cadastro que depende do formato de resposta. O aplicativo não foi alterado.

## Limites

Esta wiki é independente do jogo e não executa análises por IA. As observações sobre o manual vêm da revisão feita para o roteiro; o manual e as cartas não são redistribuídos. Não inclua credenciais ou arquivos .env.
