# Gabarito dos exercícios da tarefa do Dia 1: Primeiros passos e modo de pensar

Recomendamos muito que só veja a solução a seguir depois de ter executado todos os passos da tarefa do dia 1.

#### Exercícios

1. Utilizando o terminal (no Windows, o próprio "git bash"), navegue para uma localização desejada e crie uma pasta chamada `dia-1-primeiros-passos`
2. Navegue para a pasta e crie o diretório com o nome de `tarefa-dia-1` e navegue para dentro dele (desafio: tente fazer isso com um único comando)
3. Dentro da `tarefa-dia-1` crie um arquivo `resumo-dia-1.md`
4. Usando um editor de texto qualquer copie o conteúdo para o arquivo e salve.
5. De volta ao terminal, exiba as primeiras 5 linhas do texto.
6. Agora tente exibir todas as linhas que tem a palavra 'programação' no texto.
7. Desafio extra: exiba todas as linhas que não começam com '-'. Em seguida, exiba todas as linhas que não começam com '-'. Você deve pesquisar no google para resolver esse desafio.
  

#### Os comandos a seguir resolvem os exercícios

1. `mkdir dia-1-primeiros-passos` para fazer o diretório ITuring
2. Para fazer com um único comando você pode usar o &&: `cd dia-1-primeiros-passos && mkdir tarefa-dia-1 && cd tarefa-dia-1`
3. `touch resumo-dia-1.md`
4. Basta copiar o texto usando o notepad mesmo e salvar.
5. `head resumo-dia-1.md`
6. `grep programação resumo-dia-1.md`
7. `grep ^- resumo-dia-1.md` e `grep ^[^-] resumo-dia-1.md`

Você pode ver mais detalhes sobre o desafio além de outras possibilidades de como usar o comando grep aqui: https://guialinux.uniriotec.br/grep/.

O mais importante é sempre ter o hábito de buscar soluções, mesmo quando não temos ideia de como resolver. Hábito e técnica de pesquisa são habilidades extremamente importantes de uma pessoa programadora. Muito mais do que lembrar comandos de có.
