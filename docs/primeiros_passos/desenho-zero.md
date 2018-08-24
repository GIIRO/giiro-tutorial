# Desenhando um mapa do zero!

Agora que você já sabe como criar e como visualizar um mapa, vamos então começar a preenchê-lo com os elementos da sua rede. Caso ainda não saiba, clique no [guia rápido!](primeiros_passos/guiarapido.md)

Basicamente os elementos podem ser classificados em dois tipos: marcadores (**Site**, **Poste**, **Caixa Subterrânea**, **Reserva Técninca**, **Caixa de Emendas** e **Nota**) e linhas (**Cabo** e **Duto**). Estes elementos **podem possuir** algum tipo de relação entre eles, por exemplo, uma **Reserva Técnica** que está acoplada a um **Poste** ou uma **Caixa de Emendas** entre dois **Cabos**.

**Reserva Técnica com Poste** 

[markdown video](img/add-poste-reserva.mp4 ':include :type=video') 

**Caixa de Emenda com Cabo**

[markdown video](img/add-cabo-caixa.mp4 ':include :type=video')

Nem todos os elementos se relacionam entre si (um **Poste** não tem nenhuma relação com um **Duto**) em especial o elemento **Nota** que não se relaciona com nenhum outro elemento. Também vale destacar que um elemento não se relaciona com um outro do mesmo tipo.

[markdown video](img/mesmo-elemento.mp4 ':include :type=video') 

## Desenhando o mapa

Depois de ter criado o seu mapa na área administrativa e clicado em visualizá-lo, você será redirecionado para a área de inserção de elementos no mapa.

### Inserindo elementos do tipo marcador

Para inserir elementos do tipo marcador no mapa é muito simples, basta selecionar no menu lateral à direita o tipo do elemento para **habilitar** a sua inserção. Uma vez selecionado, para inserir no mapa basta **clicar no local** onde você queira inserir o elemento. Você poderá inserir vários elementos do mesmo tipo em sequência. Para desabilitar a inserção, clique no **Seletor** ou pressione o botão `ESC`.

[markdown video](img/remessa-inserir.mp4 ':include :type=video') 

Para inserir marcadores de outros tipos, é só selecionar o tipo desejado no menu que a sua inserção será habilitada.

#### Inserindo elementos do tipo linha

Uma vez que o mapa já possua elementos do tipo marcador no mapa, você poderá inserir **Cabos** e **Dutos**. Selecionando algum destes dois, será habilitado a sua inserção. Ao **clicar no mapa** se inicia a marcação das localidades por onde o elemento passará. Se o **clique for em um outro elemento**, este será **automaticamente associado/correlacionado**. Isso é percebível com a mudança do ícone do marcador.

!> Importante clicar no botão **Salvar** para salvar o elemento criado.

[markdown video](img/remessa-cabo.mp4 ':include :type=video') 

!> Quando o cabo está relacionado ao elemento, após clicar em salvar, o elemento (ex. **Poste**) muda sua cor para cinza. Se a borda do elemento continuar branca, este não está relacionado ao **Cabo**.

!> Quando um **Cabo** é relacionado com uma **Caixa de Emendas**, este é automaticamente dividido em dois.

!> Existe um fluxo alternativo, no qual você começa desenhando a sua rede a partir dos elementos do tipo linha. Para conhecer acesse aqui o [fluxo alternativo](primeiros_passos/desenho-zero-fluxo2.md).

## Próximos passos...

* [Edição de informações dos elementos](primeiros_passos/edicao-elementos.md)
* [Correlacionando elementos](primeiros_passos/correlacionando-elementos.md)
