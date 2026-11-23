# prtApp

Study sessions on steroids.

Versão web do **PSCPP Estudo**, protegida por senha. O app e o banco de questões estão compactados e cifrados (AES-256-GCM); a página inicial pede a senha e decifra tudo no próprio navegador. Sem uma senha válida, os arquivos deste repositório são ilegíveis.

- Endereço (GitHub Pages): https://rsb-prt.github.io/prtApp/
- Esquecer a senha num aparelho: abra o endereço com `?sair` no fim.
- O progresso de estudo fica no navegador de cada aparelho (use Baixar/Importar backup em Configurações para levar de um aparelho a outro).

Arquivos gerados por `tools/build-web-cripto.js` do app (não editar à mão): `index.html` (tela de senha), `chaves.json` (chave embrulhada por senha), `app.bin` e `data/banco-N.bin` (conteúdo cifrado), `.nojekyll`.
