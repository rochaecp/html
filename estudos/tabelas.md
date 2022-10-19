# Tabelas:

- tr=linha, td=coluna, th=col cabeçalho, thead=cabeçalho, tbody=corpo, tfoot=rodapé row=linha
- <td rowspan="2">Coluna ocupando duas linhas</td>
- <td colspan="4">linha ocupando quatro colunas</td> 

~~~html
<table border="2">
  <caption>Legenda tabela</caption>
  <thead>
    <tr>
      <th>Cabeçalho, Coluna 1</th>
      <th>Cabeçalho, Coluna 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Linha 1 Coluna 1</td>
      <td>Linha 1 Coluna 2</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Rodapé, Coluna 1</td>
      <td>Rodapé, Coluna 2</td>
    </tr>
  </tfoot>
</table>
~~~

