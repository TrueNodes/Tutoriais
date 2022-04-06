# Tutorial de criação de masternode Touriva hospedado pela True Nodes
Neste tutorial você irá ver o passo a passo para a criação de um masternode e as etapas para nos enviar os parâmetros necessários para a hospedagem.

### Você irá precisar de
* 500 TOUR para cada masternode que for criar (compre uma fração a mais, pois você pode ter que pagar taxas de transação)
* A carteira Touriva baixada ([link para pagina de downloads](https://touriva.info/#Downloads)) e sincronizada

### Procedimento
1. Abra sua carteira Touriva e se certifique de que esteja sincronizada ou aguarde sincronização completa;
2. Em cima no menu clique em ```Ferramentas(tools) > Debug Console```
3. Digite ```getaccountaddress masternode01```. Você pode trocar o nome "masternode01" por outro de sua preferência. Será gerado um endereço de recebimento. Caso for hospedar mais de 1 masternode, gere um novo endereço para cada masternode.
4. Envie exatamente 500 moedas para esse(s) endereço(s);
6. Aguarde a transação ser totalmente confirmada;
7. Voltando ao console, digite o comando ```masternode outputs``` e dê _[ENTER]_. Se tudo estiver certo, irá aparecer uma lista de moedas alocadas disponíveis para serem usadas em masternodes. Cada item tem dois parâmetros, o ```txhash``` e o ```outputindex```. Anote esses parâmetros pois serão necessários para a hospedagem.
8. Ainda no console, digite ```masternode genkey```. Será gerada uma PrivKey do seu masternode. Anote esse parâmetro pois é necessário para a hospedagem. Caso você queira hospedar mais de 1 masternode, repita o procedimento para gerar uma chave para cada masternode.

9. Com os códigos gerados nas etapas ```7``` e ```8``` em mãos, entre em contato comigo pelo [telegram](https://t.me/matheus_bach) ou [whatsapp](https://api.whatsapp.com/send?phone=5549985054419&text=Quero%20hospedar%20meu%20masternode%20na%20True%20Nodes). Com esses códigos eu irei realizar a hospedagem do masternode e fornecer para você os parâmetros usado na próxima etapa para você poder ativar o masternode em sua carteira e visualizar o status dele. Costumo responder em poucas horas. Para agilizar mais o processo, prefira a comunicação via telegram e já tenha anotado os códigos gerados nas etapas ```7``` e ```8```, pois eles serão solicitados.

10. Após eu lhe fornecer os parâmetros que indicam para sua carteira a comunicação com o serviço de hospedagem, vá em sua carteira e na parte superior, acesse o menu ```Ferramentas(tools) > Abrir arquivo de Configuração de Masternode```
11. Será aberto um arquivo onde fica uma lista contendo os masternodes. No final do arquivo adicione a(s) linha(s) que eu lhe enviei sendo que cada linha corresponde a um masternode. Salve o arquivo e feche. Feche também a carteira Touriva e abra ela novamente para que a configuração seja aplicada e apareça em sua tela.
12. Vá para a aba Masternodes. Se você tiver feito os procedimentos corretamente, seu masternode irá aparecer na lista, 
13. Caso a situação do seu masternode não esteja "ENABLED", clique no botão "Start MISSING" localizado na parte inferior da janela.

Pronto. Seu masternode agora está ativo e em breve irá começar a gerar recompensas, que irão direto para sua carteira. Caso precise de suporte, [entre em contato](https://github.com/TrueNodes/SUPORTE.md).

### Recomendações (muito importante!)

Veja as [recomendações de segurança](/Seguranca.md)

