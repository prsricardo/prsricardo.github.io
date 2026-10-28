# Site de apresentação — Paulo Ricardo dos Santos

Página única com os serviços de gestão de contratos de TIC, PMO e delivery de fábricas de software.

## Como editar

Todo o site está no arquivo `index.html`. Para mudar um texto, abra o arquivo no GitHub, clique no ícone de lápis, edite e clique em **Commit changes**. A versão publicada se atualiza sozinha em um ou dois minutos.

Onde fica cada parte dentro do `index.html`:

| Seção do site | Procure por |
|---|---|
| Frase principal e números do topo | `id="topo"` |
| Três situações-problema | `id="problemas"` |
| Serviços | `id="servicos"` |
| Método em quatro etapas | `id="metodo"` |
| Cases | `id="cases"` |
| Certificações e formação | `id="credenciais"` |
| Contato | `id="contato"` |

Cores e fontes ficam no início do arquivo, no bloco `:root`. A cor de destaque é `--accent`.

## Publicação (GitHub Pages)

1. No repositório, abra **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
3. O site fica disponível em `https://prsricardo.github.io/` (se o repositório se chamar `prsricardo.github.io`) ou em `https://prsricardo.github.io/NOME-DO-REPOSITORIO/`.

## Créditos

Layout inspirado em [RyanFitzgerald/devportfolio](https://github.com/RyanFitzgerald/devportfolio) (licença MIT).
