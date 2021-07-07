#### Caso sua wallet não esteja sincronizando da forma correta, exibindo como estando sem conexões ativas com a rede, realize o seguinte procedimento:

1. Feche sua carteira;
2. Localize e abra o arquivo ```rdct.conf```. Ele está localizado:
  * No linux: ```/home/nomedeusuario/.rdct/rdct.conf``` (pasta normalmente está oculta. Use o atalho ```Ctrl+H``` para visualizar itens ocultos)
  * No windows: ```%appdata%/RDCT/rdct.conf```
3. No final do arquivo adicione a seguinte lista:
  ```
  addnode=n1.rdctoken.io:49846
  addnode=n2.rdctoken.io:49846
  addnode=n3.rdctoken.io:49846
  addnode=n4.rdctoken.io:49846
  addnode=n5.rdctoken.io:49846
  addnode=n6.rdctoken.io:49846
  addnode=n7.rdctoken.io:49846
  addnode=n8.rdctoken.io:49846
  addnode=n9.rdctoken.io:49846
  addnode=n10.rdctoken.io:49846
  addnode=n11.rdctoken.io:49846
  addnode=n12.rdctoken.io:49846
  addnode=n13.rdctoken.io:49846
  addnode=n14.rdctoken.io:49846
  addnode=n15.rdctoken.io:49846
  addnode=n16.rdctoken.io:49846
  addnode=n17.rdctoken.io:49846
  addnode=n18.rdctoken.io:49846
  addnode=n19.rdctoken.io:49846
  addnode=n20.rdctoken.io:49846
  ```
  4. Salve e feche o arquivo;
  5. Abra novamente sua carteira

Pronto. Isso deve funcionar
