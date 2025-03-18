# Projeto-DS-II
Caio Takehiro Magnoli Igari<br/>
10437809<br/>
takehiro14000@gmail.com <br/>
Equipe caio

## Cenário de negócio / Concepção:
### Problema ou oportunidade percebida :
Uma rede de restaurantes nova no ramo percebeu que está perdendo muitas vendas, e poderia resolver isso incrementando um sistema de software que facilite a organização interna de cada restaurante e melhore (facilite) a experiência do cliente. Atualmente, além dos processos manuais serem menos eficazes também possuem defeitos como a ocorrência de atrasos, erros operacionais e insatisfação dos consumidores. Além disso, a ausência de uma plataforma digital limita de certa forma o contato direto com os clientes, reduzindo as oportunidades de aumentar o número de pedidos(perda de vendas) e fidelizar consumidores.

### Razão ou justificativa para esta demanda :
O mercado não só de alimentação está cada vez mais competitivo, e as empresas precisam se adaptar às novas tecnologias para acompanhar as expectativas dos consumidores, caso  o contrário as outras empresas estaram sempre em vantagem nesse aspecto, podendo causar sua falência. A implementação de um software que integre os processos internos e facilite a interação com os clientes pode ajudar a rede a aumentar suas vendas, melhorar a eficiência e fazer com que se destaque no mercado.

### Descrição sucinta do produto de software que será produzido :
O software será uma plataforma digital integrada que permitirá:
Gerenciamento interno dos restaurantes, tornando muit mais práticos o controle de estoque, pedidos, funcionários, assim o restaurante consegue economizar muito tempo, que no futuro retornará como lucro.
Integração de sistema de delivery próprio da loja, para que não percam parte do dinheiro arrecado com taxas de aplicativos terceiros.
Interface amigável para os clientes realizarem pedidos online, acompanharem o status e avaliarem os serviços.

### Clientes, usuários e demais envolvidos/impactados com o produto :
Clientes finais: Consumidores que utilizarão os serviços da rede de restaurantes.
Usuários principais: Funcionários dos restaurantes, desde de o atendente até o dono.
Demais envolvidos: parceiros de delivery (entregadores).

### Principais critérios de qualidade para o produto :
Funcionalidade: O sistema deve atender a todas as necessidades de interação com os clientes.
Usabilidade: Interface deve ser simples e intuitiva tanto para os funcionários quanto para os consumidores.
Desempenho: Deve ter o menor tempo de resposta possível para evitar atrasos.
Confiabilidade: Sistema tem que ser confivael, isso quer dizer que ele deve cometer poucas falhas de forma que não impeça a continuidade das operações.
Facilidade de suporte: Facilidade de manutenção e atualização do software.

## Modelo de caso de uso:
### Casos de uso de negócio por ator (cumprir metas do usuário) e descrever os casos de uso de forma resumida
#### Atores principais, casos de uso e descrição:
##### Consumidor</br> 
Cadastrar no site: O consumidor acessa a plataforma e seleciona a opção de cadastro, caso já não tenha se cadastrado. Ele passa algumas informações pessoais como o e-mail, e escolhe uma senha. O sistema valida os dados, verifica se o e-mail já está registrado e, em caso positivo, notifica o consumidor. Após a validação, o sistema cria uma conta para o consumidor. </br>

Adicionar itens ao carrinho : O consumidor navega pelo site ou aplicativo, buscando os produtos que lhe interessam. Ao encontrar um item ideal, ele adiciona ao carrinho. O sistema atualiza o carrinho exibindo o item adicionado, e mostra o valor total atualizado. O consumidor pode continuar navegando e adicionando mais itens ou acessar o carrinho para revisar os produtos selecionados. </br> 

Realizar pagamento : O consumidor finaliza a seleção de itens e acessa o carrinho para prosseguir com o pagamento. Ele escolhe a forma de pagamento . O sistema solicita os dados necessários, como número do cartão, data de validade e código de segurança. Após a inserção dos dados, o sistema valida a transação. Se a transação for aprovada, o sistema gera um comprovante de pagamento e atualiza o status do pedido. </br> 

Acompanhar o status do pedido: O consumidor acessa sua conta no site ou aplicativo para verificar a situação do pedido. O sistema exibe o status atual do pedido, indicando se o pedido está sendo preparado, pronto para entrega ou já foi entregue. Caso ocorra algum atraso ou problema, o sistema notifica o consumidor automaticamente com uma mensagem explicativa. O consumidor também pode receber atualizações via e-mail ou SMS.

##### Funcionários </br> 
Registrar pedidos: O funcionário atende um cliente presencialmente ou recebe um pedido via telefone. Ele acessa o sistema e registra os detalhes do pedido. O sistema valida os dados inseridos, se tudo estiver correto, confirma o registro do pedido. O sistema então notifica a pessoas nescessária para iniciar o processo da entrega do pedido.</br> 

Atualizar status do pedido: O funcionário acessa o sistema para informar o progresso do pedido. O sistema registra a alteração e notifica automaticamente o consumidor e o entregador sobre o novo status. Se houver algum problema durante a preparação, o funcionário pode registrar observações no sistema para comunicar a situação.</br> 

Gerenciar estoque: O funcionário monitora o estoque de produtos por meio do sistema, verificando a quantidade disponível de cada item. Quando um produto está próximo de ficar em falta, o sistema emite um alerta automático. O funcionário então solicita reposição no sistema, informando a quantidade necessária. O sistema atualiza o estoque em tempo real e registra a solicitação para acompanhamento. </br> 

##### Dono:</br> 
Monitorar desempenho financeiro: O dono acessa o sistema para visualizar relatórios sobre o desempenho financeiro da empresa. Ele filtra os relatórios de acordo com o que for conveniente para situação. O sistema gera gráficoscom os dados financeiros. Com base nessas informações, o dono toma decisões estratégicas, como ajustar preços ou otimizar custos operacionais.

##### Entregadores:</br> 
Receber informações sobre entregas: O entregador acessa o sistema para obter detalhes sobre o pedido. O sistema exibe informações como endereço de entrega, forma de pagamento, valor total e observações do cliente. O entregador também pode visualizar o status atual do pedido para garantir que está alinhado com o cronograma de entrega.</br> 

Atualizar status da entrega: Durante o processo de entrega, o entregador acessa o sistema para informar o progresso. Por exemplo, ao sair do restaurante, ele atualiza o status para "Saiu para Entrega". Quando o pedido é entregue ao cliente, ele registra o status como "Entregue" e, se necessário, coleta a assinatura ou confirmação do cliente no sistema. O sistema notifica automaticamente o consumidor sobre a conclusão da entrega.

### Caso de uso crítico/mais importante do sistema de forma completa
![423776558-290ea485-4f80-439e-a923-6cd245f2c732](https://github.com/user-attachments/assets/0004899c-f1dd-478c-b27f-c80a2cc8985b)


### Diagrama de caso de uso UML
![423770641-bdaf786e-e63e-409c-90e3-3c5b058e892f](https://github.com/user-attachments/assets/b6f034c1-640a-40e5-9b31-8b80c39a414f)

## Prototipagem
![423848191-6ef4d579-ae58-424b-99a0-f9025ca18918](https://github.com/user-attachments/assets/696e656e-a554-456a-ab8d-6279b9998d2c)

![423848317-23ed4ce8-bdb8-4e60-9787-0659e769d13d](https://github.com/user-attachments/assets/8ea5c227-f7c2-4df2-8732-f6b956fca8e7)

![423848425-408f498b-af42-46b1-81e0-1a35764ae445](https://github.com/user-attachments/assets/15e8aefa-e8bc-4511-aea4-0911f23bce90)

![423848521-ad679977-e27e-4453-bf68-6b5ab85b1925](https://github.com/user-attachments/assets/5ad7d9f0-2e24-4e2a-91c9-7355bd0717d0)

