Linguagem / language: [PORTUGUÊS](#tutorial-de-criação-de-masternode-lunarium-hospedado-pela-true-nodes) | [ENGLISH](#lunarium-masternode-creation-and-hosting-tutorial-by-true-nodes)

[►](https://github.com/TrueNodes/SUPORTE.md) **Actual hosting price: only ```R$ 3,50``` (arround U$ 0.65) paid in crypto**

# Tutorial de criação de masternode Lunarium hospedado pela True Nodes
Neste tutorial você irá ver o passo a passo para a criação de um masternode e as etapas para nos enviar os parâmetros necessários para a hospedagem.

### Você irá precisar de
* 10000 XLN para cada masternode que for criar (compre uma fração a mais, pois você pode ter que pagar taxas de transação)
* A carteira Lunarium baixada ([link para pagina de downloads](https://github.com/LunariumCoin/lunarium/releases/latest)) e sincronizada

### Procedimento
1. Abra sua carteira Lunarium e se certifique de que esteja sincronizada ou aguarde sincronização completa;
2. Em cima no menu clique em ```Ferramentas(tools) > Debug Console```
3. Digite ```getaccountaddress masternode01```. Você pode trocar o nome "masternode01" por outro de sua preferência. Será gerado um endereço de recebimento. Caso for hospedar mais de 1 masternode, gere um novo endereço para cada masternode.
4. Envie exatamente 10000 moedas para esse(s) endereço(s);
6. Aguarde a transação ser totalmente confirmada;
7. Voltando ao console, digite o comando ```masternode outputs``` e dê _[ENTER]_. Se tudo estiver certo, irá aparecer uma lista de moedas alocadas disponíveis para serem usadas em masternodes. Cada item tem dois parâmetros, o ```txhash``` e o ```outputindex```. Anote esses parâmetros pois serão necessários para a hospedagem.
8. Ainda no console, digite ```masternode genkey```. Será gerada uma PrivKey do seu masternode. Anote esse parâmetro pois é necessário para a hospedagem. Caso você queira hospedar mais de 1 masternode, repita o procedimento para gerar uma chave para cada masternode.

9. Com os códigos gerados nas etapas ```7``` e ```8``` em mãos, entre em contato comigo pelo [telegram](https://t.me/matheus_bach) ou [whatsapp](https://api.whatsapp.com/send?phone=5549985054419&text=Quero%20hospedar%20meu%20masternode%20na%20True%20Nodes). Com esses códigos eu irei realizar a hospedagem do masternode e fornecer para você os parâmetros usado na próxima etapa para você poder ativar o masternode em sua carteira e visualizar o status dele. Costumo responder em poucas horas. Para agilizar mais o processo, prefira a comunicação via telegram e já tenha anotado os códigos gerados nas etapas ```7``` e ```8```, pois eles serão solicitados.

10. Após eu lhe fornecer os parâmetros do serviço de hospedagem, vá em sua carteira e na parte superior, acesse o menu ```Ferramentas(tools) > Abrir arquivo de Configuração de Masternode```
11. Será aberto um arquivo onde fica uma lista contendo os masternodes. No final do arquivo adicione a(s) linha(s) que eu lhe enviei sendo que cada linha corresponde a um masternode. Salve o arquivo e feche. Feche também a carteira Lunarium e abra ela novamente para que a configuração seja aplicada e apareça em sua tela.
12. Vá para a aba Masternodes. Se você tiver feito os procedimentos corretamente, seu masternode irá aparecer na lista, 
13. Caso a situação do seu masternode não esteja "ENABLED", clique no botão "Start MISSING" localizado na parte inferior da janela. Assim seu masternode irá iniciar.

Pronto. Seu masternode agora está ativo e em breve irá começar a gerar recompensas, que irão direto para sua carteira. Caso precise de suporte, [entre em contato](https://github.com/TrueNodes/SUPORTE.md).

### Recomendações (muito importante!)

Veja as [recomendações de segurança](/Seguranca.md)

---

# Lunarium masternode creation and hosting tutorial by True Nodes
In this tutorial you will see the step by step for creating a masternode and the steps to send us the parameters needed for hosting.

### You will need
* 10000 XLN for each masternode you create (buy a fraction more as you may have to pay transaction fees)
* Lunarium wallet downloaded ([link to downloads page](https://github.com/LunariumCoin/lunarium/releases/latest)) and synced

### Procedure
1. Open your Lunarium wallet and make sure it is synced or wait for full sync;
2. At the top of the menu click ```Tools(tools) > Debug Console```
3. Type ```getaccountaddress masternode01```. You can change the name "masternode01" to one you like. A receiving address will be generated. If you are going to host more than 1 masternode, generate a new address for each masternode.
4. Send exactly 10000 coins to this(these) address(es);
6. Wait for the transaction to be fully confirmed;
7. Returning to the console, type the command ```masternode outputs``` and press _[ENTER]_. If everything is ok, a list of allocated coins available for use in masternodes will appear. Each item has two parameters, the ```txhash``` and the ```outputindex```. Make a note of these parameters as they will be needed for hosting.
8. While still at the console, type ```masternode genkey```. A PrivKey of your masternode will be generated. Make a note of this parameter as it is required for hosting. If you want to host more than 1 masternode, repeat the procedure to generate a key for each masternode.

9. With the codes generated in steps ```7``` and ```8``` in hand, contact me via [telegram](https://t.me/matheus_bach) or [whatsapp](https://api.whatsapp.com/send?phone=5549985054419&text=I%20want%20host%20my%20masternode%20in%20True%20Nodes). With these codes I will host the masternode and provide you with the parameters used in the next step so you can activate the masternode in your wallet and view its status. I usually respond in a few hours. To speed up the process, prefer communication via telegram and have already noted the codes generated in steps ```7``` and ```8```, as they will be requested.

10. After I provide you with the parameters of the hosting service, go to your wallet and at the top, go to the menu ```Tools > Open Masternode Configuration File```
11. A file will be opened with a list containing the masternodes. At the end of the file add the line(s) I sent you where each line corresponds to a masternode. Save the file and close. Also close the Lunarium wallet and open it again so that the setting is applied and appears on your screen.
12. Go to the Masternodes tab. If you have done the procedures correctly, your masternode will appear in the list,
13. If your masternode status is not "ENABLED", click on the "Start MISSING" button located at the bottom of the window. Then your masternode will start.

Ready. Your masternode is now active and will soon start generating rewards that will go straight to your wallet. If you need support, [contact me](https://github.com/TrueNodes/SUPORTE.md).

### Recommendations (very important!)

See the [safety recommendations](/Security.md) 
