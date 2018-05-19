# WappCo
Inicie uma conversa no WhatsApp com um único clique!

Crindo um link para seu número do Whatsapp 
====================

Você tem um negócio que precisa constantemente entrar em contato com os clientes pelo WhatsApp? Se você usa a rede social para suporte nas suas vendas vai gostar dessa ferramenta. Aprenda a fazer um link "clique para conversar" com seu número no WhatsApp!

O Wapp.Co gera um link que, ao ser clicado, leva o usuário a uma conversa com determinado número. Você pode até criar o link com uma mensagem pré-determinada para a pessoa que clicar nele te enviar.

Se uma pessoa estiver navegando em seu site pelo computador, por exemplo, e clicar no link do seu contato, automaticamente surge um aviso na tela para ela te enviar uma mensagem

Essa ferramenta tem recursos que pode ter uma série de utilidades. Por exemplo, se você estiver tentando vender um produto ou serviço, pode colocar as fotos junto com um link para o seu número. Nesse link, você também pode colocar uma mensagem como "Olá, estou interessado do produto/serviço!"; assim, o potencial comprador não terá nem o trabalho de digitar. E você pode fazer tudo isso sem revelar seu número de telefone à internet inteira. 

A probabilidade de uma venda acontecer aumenta, pois o cliente não tem o trabalho de adicionar o seu número na lista de contato deles.

Veja como criar o seu link
============

Para criar um link para seu número no Whatsapp:

1º Copie o link
-
`https://wapp.co/00000000000`

Somente com ele é possível criar o redirecionamento direto para o seu número.

2º Coloque o seu Número no Link. Substitua todos os ZEROS pelo seu número de telefone. Incluindo o DDD da sua cidade.
-
> Exemplo: Meu número de contato no WhatsApp é 99999-9999 e eu moro em Maceió/AL, onde o DDD é 82.

- No campo de número, eu vou substituir da seguinte maneira: `https://wapp.co/82999999999`

IMPORTANTE: fique atento se sua cidade possui o nono dígito, ok? No exemplo acima, a cidade tem o nono dígito.

3º Criar um link com uma mensagem pré-determinada
-
- Como não é possível inserir espaços nos links, é necessário substituí-los pelo símbolo `_`. Assim, se você quiser que a sua mensagem seja `Olá, meu amigo!`, você precisará substituir o espaço por `Olá,_meu_amigo!`.

- Então, se você quiser criar um link para o seu número com a mensagem pré-definida "Olá, meu amigo!", e o seu celular for brasileiro, de Maceió/AL, com o número 99999-9999, o seu link ficará 

`https://wapp.co/82999999999/Olá,_meu_amigo!`

4º Criar um link para compartilhar uma mensagem pré-determinada + link do site para vários contatos do WhatsApp
-
- No lugar de informar um número de telefone informe um `0` (zero) + a mensagem, e para o link do site mude as barras `/` _http://instagram.com/wappco_ para `|` _http:||instagram.com|wappco_, o seu link ficará 

`https://wapp.co/0/Olá,_meu_amigo!_siga_meu_instagram_http:||instagram.com|wappco_` _no final do link do site adicione um `_` para o WhatsApp exibir uma prévia do site_ 

> Teste o link acima clicando aqui: <https://wapp.co/0/Olá,_meu_amigo!_siga_meu_instagram_http:||instagram.com|wappco_> 

5º Criar um botão para exibir no rodapé de seu site
-
![](https://api.wapp.co/precisadeajuda.png)

> Substitua todos os ZEROS `...src="https://api.wapp.co/balao/00000000000..."` pelo seu número de telefone. Incluindo o DDD da sua cidade .

- Copie o código: 
```html
<iframe style="margin: 0;padding: 0;border: 0;font-size: 100%;font: inherit;vertical-align: baseline;position: fixed;bottom: 10px;right: 10px;height: 70px;width: 225px;overflow: hidden;" src="https://api.wapp.co/balao/00000000000" width="225" height="70" allowfullscreen hspace="0" vspace="0" frameborder="0" scrolling="no"></iframe>
```
- Cole o código antes de ` </body> `
