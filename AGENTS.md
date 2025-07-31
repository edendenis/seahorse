# Instruções Codex

- Use o Git na branch `main`. Não crie novas branches nem altere commits existentes.
- Aguarde cada comando do terminal finalizar antes de responder.
- Verifique com `git status` se a árvore de trabalho está limpa antes de finalizar.
- Ao citar arquivos ou comandos, utilize os formatos `【F:<caminho>†L<inicio>-L<fim>】` e `【<chunk_id>†L<inicio>-L<fim>】`.

## README

- Após atualizar `README.ipynb`, execute `python convert_ipynb_to_md_and_py.py` para gerar `README.md` e `README.py`.
- Não altere a seção `## 1. Configurar/Instalar/usar o `Git` [1]` do `README.ipynb`.
- Nenhum teste adicional é necessário.
- Inclua a saída do script de conversão na seção de testes do PR.
