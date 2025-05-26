# 📁 Script para Criar Pasta e Arquivo

Este é um script em lote (batch script) para Windows que cria uma nova pasta e um arquivo de texto dentro dela automaticamente.

## 🛠️ Como Usar

1. Abra o Bloco de Notas ou qualquer editor de texto de sua preferência.
2. Copie o código abaixo:

@echo off  
mkdir NovaPasta  
echo Conteúdo do Arquivo > NovaPasta\NovoArquivo.txt

3. Salve o arquivo com a extensão `.bat`, por exemplo: `CriarPasta.bat`
4. Dê dois cliques no arquivo ou execute pelo Prompt de Comando.

Após a execução, o script criará uma pasta chamada `NovaPasta` e dentro dela um arquivo chamado `NovoArquivo.txt` com o conteúdo "Conteúdo do Arquivo".

## 💡 Observações

- Se a pasta já existir, o comando `mkdir` não causará erro.
- O arquivo será sobrescrito toda vez que o script for executado, a não ser que você modifique o redirecionamento `>` para `>>`.

## 🤝 Contribuições

Sinta-se à vontade para enviar sugestões de melhoria, abrir issues ou pull requests com funcionalidades extras, como: criação com nome dinâmico, múltiplos arquivos ou logs de execução.

## 📜 Licença

Este projeto está licenciado sob os termos da [MIT License](LICENSE).
