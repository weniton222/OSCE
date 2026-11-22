# Treino OSCE Semiotécnica

Site de treino para o OSCE de Semiotécnica I: 44 estações, com 1 minuto de leitura, 3 minutos de execução e correção pelo checklist.

## Como funciona

- **Simular a prova:** sorteia 2 estações. O tempo de execução pode ser trocado para 5 minutos ou sem limite.
- **Treinar uma estação:** escolha qualquer uma na lista. A melhor nota de cada estação fica salva no navegador de quem usa.
- **Resposta:** digite ou dite (o ditado funciona no Chrome e no Edge).
- **Correção:** ao entregar, marque no checklist o que você fez. O botão "Copiar para corrigir com IA" copia o caso, o checklist e a resposta para colar em um assistente.

Os checklists e os pesos são de treino e não substituem o checklist oficial da disciplina.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub (por exemplo, `treino-osce`).
2. Envie `index.html`, `stations.js` e este `README.md` para a raiz do repositório (Add file > Upload files).
3. Abra Settings > Pages. Em "Build and deployment", escolha Source: "Deploy from a branch", Branch: `main`, pasta `/ (root)`, e salve.
4. Depois de um ou dois minutos o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Arquivos

- `index.html`: a página.
- `stations.js`: as estações, os checklists e as observações do gabarito. Para corrigir um texto ou um peso, edite este arquivo.

## Fotos das estações

As estações com figura mostram uma descrição em texto no lugar da foto. As fotos originais vêm de livro-texto e de slides da disciplina, por isso não estão neste repositório. Se a pasta `img/` existir ao lado do `index.html`, com os arquivos nomeados como no campo `img` de cada estação em `stations.js`, o site passa a mostrar as fotos sozinho.
