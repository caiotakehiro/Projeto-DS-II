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

## Modelo de domínio
![423931158-15412b95-81ab-46ea-9c85-458f1dfe24a7](https://github.com/user-attachments/assets/817c63ac-c05f-410f-ba93-c4b0e0162817)

### Descrição sobre o Modelo de Domínio
  Fica evidente que a maior parte deste modelo foi feito a partir de um padrão de análise, mais especificamente o de E-commerce, em relação ao original eu mantive praticamente toda sua base, apenas troquei a relação do perfil, pois eu vi que ele se encaixava como uma relação de herança com alguns dos novos objetos do dominío, que no caso são os funcionários e entregadores, visto que ambos tem dados pessoais e eles são convenientes para situação pois eles tem seus registros também. A entrega foi outra modificação que eu adicionei no Modelo, como se trata de um aplicativo de entrega de comida eu achei importante colocar esse objeto, e ele deve conter algumas informações que seriam a situação atual da entrega (em preparo, saiu para entrega ou já chegou), a hora que a entrega chegou e alguma observação caso seja nescessário, e é claro que ela tem uma relação direta com o entregador que é quem a realiza. Por ultimo temos o estoque que tem uma relação de agregação do produto com ele, e também temos uma relação do estoque com os funcionários, pois são eles quem gerenciam o estoque, outra relação que foi adicionada é a dos funcionários com o pedido pois como é um restaurante é essencial que alguém os prepare. 
  
  Outro fator interessante de mencionar é que as classes Cliente, Carrinho, Item, Pedido, Funcionário, Entrega, Entregador, Estoque, Produto e Fatura foram diretamente derivadas dos casos de uso, assim como seus relacionamentos, que refletem o fluxo das principais ações do sistema, como o cliente fazendo um pedido, o funcionário preparando e o entregador realizando a entrega. A composição entre Carrinho e Item, além da gestão de Estoque pelo Funcionário, também foram baseadas nesses cenários. Outras decisões, como a criação da classe Perfil e o uso de composição ou agregação, seguiram padrões de análise para complementar a modelagem.

## Prototipagem
![423848191-6ef4d579-ae58-424b-99a0-f9025ca18918](https://github.com/user-attachments/assets/696e656e-a554-456a-ab8d-6279b9998d2c)

![423848317-23ed4ce8-bdb8-4e60-9787-0659e769d13d](https://github.com/user-attachments/assets/8ea5c227-f7c2-4df2-8732-f6b956fca8e7)

![423848425-408f498b-af42-46b1-81e0-1a35764ae445](https://github.com/user-attachments/assets/15e8aefa-e8bc-4511-aea4-0911f23bce90)

![423848521-ad679977-e27e-4453-bf68-6b5ab85b1925](https://github.com/user-attachments/assets/5ad7d9f0-2e24-4e2a-91c9-7355bd0717d0)

link figma: https://www.figma.com/design/kqa24SEzVIFO5gqo8plBzO/Prototipagem-DS-II?node-id=0-1&t=Hkkh2n9FQUhi3f3s-1

## Levantamento de requisitos
### Requisitos Consolidados e Priorizados

1. O consumidor pode se cadastrar no site, informando dados pessoais como e-mail e senha.

2. O consumidor pode navegar pelo site ou aplicativo, adicionando itens ao carrinho e visualizando o valor total atualizado.

3. O consumidor pode realizar o pagamento do pedido, escolhendo entre diferentes formas de pagamento.

4. O consumidor pode acompanhar o status do pedido em tempo real.

5. O funcionário pode registrar pedidos recebidos presencialmente ou via telefone.

6. O funcionário pode atualizar o status do pedido no sistema.

7. O funcionário pode monitorar e gerenciar o estoque de produtos.

8. O entregador pode visualizar detalhes do pedido, como endereço, forma de pagamento, valor total e observações do cliente.

9. O entregador pode atualizar o status da entrega no sistema.

10. O dono pode visualizar relatórios financeiros filtrados por período ou categoria.

11. O consumidor pode avaliar os serviços após a entrega.

12. O sistema deve garantir um tempo de resposta inferior a 2 segundos para operações críticas, como login e checkout.

13. O sistema deve garantir a segurança dos dados dos usuários, utilizando criptografia para senhas e informações de pagamento.

## Especificação de requisitos
### Introdução 
Nessa sesão veremos todos os requisitos do sistema proposto que não estão documentados nos casos de uso. Ele aborda aspectos como segurança, usabilidade, confiabilidade, desempenho e outros requisitos não funcionais, além de detalhar os requisitos funcionais e as regras de negócio.

### Requisitos Não Funcionais
#### Segurança
Toda utilização do sistema requer autenticação do usuário.

O sistema deve garantir a segurança dos dados dos usuários, utilizando criptografia AES-256 para senhas e informações de pagamento.

Por questões de segurança, o usuário deve realizar novamente o login ao acessar funcionalidades críticas, como alterar dados pessoais ou realizar pagamentos.

#### Usabilidade
O texto exibido no monitor de vídeo do sistema deve ser facilmente visível a uma distância de um metro.

Cores associadas com formas comuns de daltonismo devem ser evitadas.

Sinais e alertas devem ser informados por sons, além de meios visuais, para facilitar a atenção dos funcionários e consumidores.
#### Confiabilidade
Se ocorrer uma falha no uso de um serviço externo (autorização de pagamentos, integração com sistemas de delivery, etc.), o sistema deve tentar resolver o problema com uma solução local (por exemplo, armazenar temporariamente os dados e seguir em frente), de modo a poder completar uma venda.

O sistema deve emitir notificações automáticas para clientes e funcionários em caso de atrasos ou problemas operacionais.

O sistema deve garantir previsibilidade, minimizando falhas durante operações críticas, como registro de pedidos e atualização de status.
#### Desempenho
O sistema deve garantir um tempo de resposta inferior a 2 segundos para operações críticas, como login, checkout e atualização de status.

O sistema deve suportar até 1.000 usuários simultâneos sem degradação significativa no desempenho.

O retorno da busca de produtos ou pedidos não pode demorar mais que 1 segundo.
#### Facilidade de Suporte
O sistema deve ser facilmente escalável para suportar novas funcionalidades futuras.

O sistema deve ser compatível com navegadores modernos (Chrome, Firefox, Edge).

O sistema deve permitir a configuração e personalização de relatórios financeiros e operacionais.

### Requisitos Funcionais
![428605823-64be59fe-0068-43b4-aa09-04ed3ba60d76](https://github.com/user-attachments/assets/05c58082-1d80-4eb8-98f5-393f3ab8fd91)

### Regras de Negócio
![428626853-a753dd53-84b2-43cc-95da-a088a82da05e](https://github.com/user-attachments/assets/f10a71df-08af-450a-bcae-0fbba2ff20f9)

##  Modelos de interação com aplicação de padrões GRASP
### Diagrama de sequência do caso de uso principal
![444922825-0fb44c94-5850-4ab5-ac92-ac29fbd1a019](https://github.com/user-attachments/assets/81d9e510-f1b3-4ff7-b547-d20a6d6184a5)

### Padrões Grasp Aplicados:
#### Controlador
Aplicado em :ctlPagamento, que recebe as ações da interface e coordena o fluxo do pagamento. Foi usado para centralizar a lógica do caso de uso, evitando sobrecarga na interface.

#### Criador
ctlPagamento cria a Fatura porque possui os dados necessários. O padrão foi usado para manter o controle da criação em quem já gerencia o processo.

#### Especialista na Informação
A Fatura gera o comprovante e armazena os dados da transação. Isso evita espalhar informações e garante que quem tem os dados cuide deles.

#### Acoplamento Baixo
Cada classe tem uma função bem separada: interface, controle e dados. Isso reduz dependências e facilita manutenção.

#### Coesão Alta
As classes realizam tarefas específicas e bem definidas, tornando o sistema mais organizado, compreensível e fácil de modificar.
