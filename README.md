![Screenshot_1](https://user-images.githubusercontent.com/45580434/79641791-06e1c100-8170-11ea-8ecf-b6c889805d55.png)
<br>


## _Escopo do Projeto_
A missão de vocês será desenvolver um e-commerce de trajes espaciais! 

O projeto consistirá em 3 grandes partes:

- Filtro
    - Por valor mínimo e máximo
    - Por nome do produto
    
- Home
    - Mostrando todos os produtos
    - Ordenação (Mais barato pra mais caro e vice versa)
    - Produtos:
        - Devem ter um botão que permita adicioná-los ao carrinho
        - Devem exibir o nome, preço e imagem em um card
        
- Carrinho
    - Mostrar todos os produtos e quantidades adicionadas
    - Capacidade de remover itens do carrinho
    - Mostrar o valor total do carrinho

Exemplo de estruturação de **UM** produto (Lembrem-se que vocês terão uma lista contendo todos):

```jsx
{
	id: 1,
	name: "Foguete da Missão Apollo 11",
	value: 10000.0,
	imageUrl: "https://picsum.photos/200/200",
}
```

- Desafios
    1. Salvar e Recuperar conteúdo do carrinho usando o `LocalStorage`
    2. Qual funcionalidade está faltando? Decida em grupo o que vocês concordam que poderia ser uma boa adição à loja virtual, pode ser qualquer funcionalidade, desde que vocês consigam implementá-la. Ao decidir uma funcionalidade, vocês devem confirmar com os instrutores antes de prosseguir através de um atendimento.
