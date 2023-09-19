# Sorteador com Grunt.js

Este projeto é uma aplicação web simples que permite aos usuários definirem um número máximo e, ao clicar em "Sortear", gera um número aleatório entre 1 e o número máximo especificado.

**[Veja a Aplicação em Ação](https://sorteadorgrunttomas.vercel.app/)**

## Funcionalidades Principais

- **Geração de Números Aleatórios:** O código JavaScript no arquivo `main.js` é responsável por gerar números aleatórios com base no número máximo fornecido pelo usuário.

## Configuração do Grunt.js

Este projeto utiliza o Grunt.js para automatizar várias tarefas de desenvolvimento e construção. Aqui estão as principais tarefas configuradas no Grunt:

- **Compilação de Estilos Less:** Os estilos Less são compilados em dois modos: desenvolvimento (sem compressão) e produção (com compressão).

- **Observação de Alterações:** O Grunt observa as mudanças nos arquivos Less e HTML. Quando ocorrem alterações, ele dispara automaticamente as tarefas apropriadas, como compilação de estilos e substituição de caminhos de recursos.

- **Substituição de Caminhos de Recursos:** A tarefa de substituição permite que você altere dinamicamente os caminhos dos arquivos CSS e JavaScript no arquivo HTML com base no ambiente (desenvolvimento ou produção).

- **Minificação de Arquivos HTML:** Os arquivos HTML são minificados para criar versões compactadas para implantação em produção.

- **Limpeza de Diretório:** O diretório `prebuild` é limpo regularmente para remover arquivos temporários gerados durante o processo de construção.

## Como Usar

1. **Clone o Repositório:** Clone este repositório para o seu ambiente local.

2. **Instale as Dependências:** Certifique-se de ter o Node.js instalado. No diretório do projeto, execute o comando `npm install` para instalar as dependências do Grunt.

3. **Inicie o Grunt em Modo de Desenvolvimento:** Execute `grunt` para iniciar o Grunt em modo de desenvolvimento. Isso compilará os estilos Less, substituirá os caminhos de recursos e observará as alterações nos arquivos.

4. **Teste a Aplicação:** Abra o arquivo `index.html` em seu navegador para testar a aplicação.
