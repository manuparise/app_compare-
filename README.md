Será um aplicaitvo voltado em gerar registroreqs(requisição),chamada  de um  registros que pode servir tanto pra uma pesquisa de produto ou  registro de Historico
O BLoC recebe o evento e aplica alguma lógica de negócio; A saída do evento é colocada na stream; Todos que estejam "ouvindo" a stream do nosso BLoC são notificados de que há um novo valor para ela.
Por ser um componente lógico, o BLoC não se preocupa com a interface e nem com a sua camada de dados ou API. Ele entende "apenas" de eventos. Os widgets emitem eventos e outros widgets podem respondem à estes eventos. Com este padrão é possível separar a lógica de negócio e a interface..
..Eventos são emitidos para o nosso BLoc
