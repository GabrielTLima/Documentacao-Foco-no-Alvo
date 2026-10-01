## Funcionalidades Detalhadas

## Animações
As animações do site são feitas principalmente com CSS3. A propriedade opacity controla a transparência dos elementos, e a transition faz as mudanças de estado acontecerem de forma gradual, sem trocas bruscas. Com isso, os elementos aparecem e somem com suavidade, e a navegação fica mais fluida e agradável.

O JavaScript completa esse comportamento ao responder às ações do usuário. O método addEventListener registra cliques, nos elementos da página. Quando um evento acontece, o script muda o estado do elemento, por exemplo adicionando ou removendo uma classe CSS, e isso dispara a animação definida no style.css. Assim, o CSS cuida da parte visual e o JavaScript cuida da interação.

## Busca e Filtro dos produtos
O sistema de busca e filtro ajuda o visitante a encontrar rapidamente o que procura no catálogo. Primeiro, o JavaScript acessa os elementos da página com os métodos getElementById e querySelector. É assim que ele lê o texto digitado no campo de busca e os filtros escolhidos.

Depois, o script aplica o método filter sobre a lista de produtos, guardada como um array de objetos. Esse método percorre cada produto e gera um novo array só com os que atendem aos critérios do usuário. A lista original continua intacta. Por fim, a página é atualizada para mostrar apenas os resultados encontrados.

## Sistema de paginação
A paginação divide o catálogo em páginas com um número fixo de produtos. Isso evita listas longas demais e deixa a navegação mais leve. Ela trabalha junto com a busca e os filtros: primeiro, o método filter define quais produtos fazem parte do resultado, de acordo com a organização interna do site e as escolhas do usuário.

Em seguida, o método slice separa desse resultado só a parte que corresponde à página atual. Por fim, o JavaScript mostra na tela os produtos daquela página. Quando o usuário troca de página ou muda um filtro, o processo se repete e a exibição é atualizada.

Acessar [Readme](README.md)
Acessar [Arquivos detalhados](arquivosdetalhados.md)
