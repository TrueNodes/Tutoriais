# Tutorial de criação de masternode RDCToken hospedado pela True Nodes
Neste tutorial você irá ver o passo a passo para a criação de um masternode e as etapas para nos enviar os parâmetros necessários para a hospedagem.

### Você irá precisar de
* 7500 RDCT (compre um pouco a mais, pois você pode ter que pagar taxas de transação)
* A carteira RDCToken baixada ([link para pagina de downloads](https://github.com/reidocoin/rdctoken/releases)]) e sincronizada (caso sua carteira não sincronize ou não esteja conectado a rede, siga [esse](/wallet-fix/RDCT-RDCToken.md) tutorial)

### Procedimento
1. Abra sua carteira RDCToken já sincronizada;
2. Em cima no menu clique em ```Ferramentas(tools) > Debug Console```
3. Digite ```getaccountaddress masternode01```. Você pode trocar o nome "masternode01" por outro de sua preferência. Será gerado um endereço de recebimento. Anote esse endereço pois será usado no futuro. Caso for hospedar mais de 1 masternode, gere um novo endereço para cada masternode.
4. Envie exatamente 7500 moedas para esse(s) endereço(s);
6. Aguarde a transação ser totalmente confirmada;
7. Voltando ao console, digite o comando ```masternode outputs``` e dê _[ENTER]_. Se tudo estiver certo, irá aparecer uma lista de moedas alocadas disponíveis para serem usadas em masternodes. Cada item tem dois parâmetros, o ```txhash``` e o ```outputindex```. Anote esses parâmetros pois serão necessários no futuro.
8. Ainda no console, digite ```masternode genkey```. Será gerada uma PrivKey do seu masternode. Anote esse parâmetro. Caso você queira hospedar mais de 1 masternode, gere uma nova chave para cada masternode.

9. Após isso, entre em contato comigo pelo [telegram](https://t.me/matheus_bach) ou [whatsapp](https://api.whatsapp.com/send?phone=5549985054419&text=Quero%20hopedar%20meu%20masternode%20na%20True%20Nodes) para consultar qual é o custo da hospedagem e prosseguirmos com a hospedagem do masternode. Serão solicitados os parâmetros gerados no console. Após eu concluir o processo de hopedagem, você receberá os códigos de masternode para você poder visualizar o estado do seu masternode e fazer a inicialização dele.

10. Após eu lhe responder com os códigos, vá em sua carteira, na parte superior, acesse o menu ```Ferramentas(tools) > Abrir arquivo de Configuração de Masternode```
11. No final do arquivo adicione a(s) linha(s) que eu lhe enviei. Salve o arquivo e feche. Feche também a carteira RDCToken e abra ela novamente para que a configuração apareça na sua tela.
12. Vá para a aba Masternodes. Se você tiver feito os procedimentos corretamente, seu masternode irá aparecer na lista, 
13. Caso a situação do seu masternode não esteja "ENABLED", clique no botão "Start MISSING" localizado na parte inferior da janela.

Pronto. Seu masternode agora está ativo e em breve irá começar a gerar recompensas, que irão direto para sua carteira. Caso precise de suporte, entre em contato.

### Recomendações

#### Criptografar carteira
Essa etapa tem como finalidade impedir que alguém que tenha acesso ao seu arquivo wallet.dat possa movimentar suas moedas sem sua senha. Para criptografar a carteira vá no menu Configurações > Criptografar Carteira. Digite uma senha e repita.
Atenção: se você esquecer/perder a senha você não vai mais conseguir movimentar suas moedas. Recomendo que anote no papel em um local seguro e de preferência tenha mais que uma cópia. Salvar a senha em meios digitais pode ser insegura pois quem tiver acesso ao seu arquivo de carteira talvéz também tenha acesso a uma senha salva digitalmente.

#### Backup de carteira
Essa etapa tem como objetivo que você faça uma cópia de segurança do seu arquivo de carteira para permitir a você restaurar a carteira caso seu computador estrague e você fique sem acesso a sua carteira. Para fazer isso vá no menu Arquivo > carteira de backup (backup de carteira). Irá aparecer uma tela para você escolher onde salvar o arquivo de carteira. Salve ele em um ou mais locais seguros.

