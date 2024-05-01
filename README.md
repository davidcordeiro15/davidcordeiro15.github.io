# CP-1-Front-end
O site da Vinheria Agnello foi desenvolvido para transmitir ao usuário uma experiência parecida com uma visita a vinheria física, proporcionando um momento de compras repleto de conhecimento sobre vinhos apenas utilizando um site.   

O nosso site de vinhos foi estruturado utilizando as tecnologias: JavaScript, HTML e CSS. Nós decidimos dividir o site entre página principal, sobre nós, curiosidades, vinhos, carrinho, formulario, verificação de idade, login e cadastro. 

A página pricipal contém algumas informações sobre a loja, nossos contatos e alguns dos vinhos vendidos. A página sobre nós, aborda algumas características da vínicola, como o tratamento de  clientes e o estoque de vinhos. A página curiosidades têm certas informações sobre os vinhos, por exemplo, acerca de sua história entre os romanos. A página de vinhos é o lugar em que está as nossas opções de vinhos a venda. E por último a  página de cadastro, que mostra uma tela para cadastrar seu perfil no site.

Há uma animação na pagina de verificação de idade (index.html)
O flex box está no css de cada pagina HTML
Há também alguns pseudoelementos modificando, por exemplo, a placeholder

Para a estilizar nós decidimos utilizar um tom de vinho, para fazer sentido com o produto a ser vendido e que lembre as cores de uma vínicola tradicional, assim como a vínicola Agnello.   



LOGINS, SENHAS E CUPONS: Nos arquivos .html de pages/PaginasVinhos/, temos 6 páginas de produtos, e nelas:

Na inserção de cupons nas páginas de vinhos, ao clicar em "Teste seu cupom", temos como padrão:

'', output: "Por favor, insira um cupom!"
'FIAP2024', output: "Cupom Válido! Você conseguiu 10% de desconto!"
Com qualquer outro input, output: "Cupom Inválido! Tente outro!"
Na adição de itens no carrinho, ao clicar em "Adicionar ao carrinho", temos como padrão:

'', output: "Adicione ao menos 1 unidade!"
Qualquer quantidade
Na página de Login, temos como padrão:

'1234' no usuário e '1234' na senha, output: "Login realizado com sucesso!"
Qualquer outra informação, output: "Login não foi realizado!"
CONTEÚDO:

Tela inicial perguntando se o usuário possui mais de 18 anos
Caso seja menor de idade, redirecionar para outro site
Caso seja maior, redirecionar para home page
Botão de compra para cada vinho
Levar para uma página de mais detalhes do vinho e lá dentro, ao comprar, gerar um pop up com a mensagem(adicionado ao carrinho com sucesso)
Calculadora de preços baseado na quantidade de garrafas
Dependendo de quantas garrafas a pessoa escolher, vai mostrando o valor total
Página de login simples
If e else com login genérico(1234 como login e senha)
Opção de cupom de desconto. Ao digitar no campo de desconto e clicar em Aplicar:
Se o cupom for FIAP2024 o preço terá 10% de desconto
Sugestão de combinações de comidas baseados no vinho
Página de sugestões que baseado na escolha do vinho, a página mostra algumas receitas que combinam.
Formulário de contato
Formulário simples de contato com Nome, telefone, email e mensagem e um botão enviar que irá gerar um pop up de mensagem enviada com sucesso.
Link do repositório:
https://davidcordeiro15.github.io/

Membros do grupo:
Caio Venancio da Silva 556030
David Alexandre Cordeiro Paixão 557538
Tiago Morais Neto 555619
