## Descrição Exercicio:

Um clube de uma associação possui duas sedes campestres, uma em Florianópolis e outra em Itapema. 
Todas as sedes possuem em torno de 5.000m2 de área que é utilizada como área de lazer por todos os seus 
associados. Atualmente conta com 5.500 associados, mas esse número cresce a cada ano devido a políticas de 
incentivo à adesão de novos associados promovidas pelo presidente da entidade. Deseja-se automatizar os 
seguintes procedimentos:
Cadastro dos Associados – O cadastro dos associados deverá ser feito através do armazenamento de suas 
informações básicas de cadastro (nome, RG, CPF, telefones para contato), endereço, o banco, a agência e conta 
para o débito das mensalidades e ainda o tipo do associado. No caso de associados do tipo “Dependente”, deverá 
ser guardado o identificador do associado que é o seu “Patrocinador” ou “Responsável”;
Geração, Emissão e Controle de Mensalidades dos Associados – para cada tipo de associado é gerado uma 
mensalidade com um valor a ser cobrado do associado. As mensalidades são caracterizadas pela sua referência, 
valor a ser pago, e ainda a data do vencimento. O pagamento das mensalidades também deverá ser registrado no 
sistema.
Controle de Entrada – A cada entrada na sede o associado deverá informar o seu identificador e a sua senha 
pessoal. O sistema deverá verificar se o associado está cadastrado. Caso o associado esteja com mensalidades em 
aberto o sistema deverá rejeitar a entrada desse associado. O sistema deverá ter uma tolerância de 15 dias após o 
vencimento da mensalidade. Caso todas as validações estejam corretas o sistema deverá registrar a entrada do 
associado, assinalando a data e a hora da entrada bem como assinalar que ele encontra-se dentro da sede do 
clube. No momento da saída o sistema deverá registrar a data e a hora da saída do clube e ainda assinalar que ele 
se encontra fora da sede do clube. O sistema somente libera a saída para associados que estão com as contas no 
bar em situação “fechadas”; ou seja, que ele quitou todas as suas compras realizadas no clube. O sistema deverá 
guardar o histórico das movimentações de entrada e saída.
Conta Financeira – O sistema controlará a conta de gastos de cada um dos associados. Para isso o sistema deverá 
receber depósitos de valores na conta de cada associado. Durante o dia, a cada compra realizada o sistema debita 
o valor da compra na conta do associado e ao final do dia ele poderá sacar o saldo restante;
Vendas – O associado poderá, através do seu identificador e senha, realizar compras de produtos na dependência 
da associação. O total da venda é debitado da conta do associado. Caso ele não tenha saldo suficiente, o sistema 
deverá emitir um aviso; exceto nos casos em que o associado tenha um “limite de gastos”. Nesses casos o sistema 
deverá permitir a venda sem saldo para esse associado, gerando um saldo negativo que deverá ser quitado ao final 
do período;
Controle de Estoque – O sistema deverá controlar todo o estoque dos produtos comercializados no clube. O 
controle de estoque deverá conter o cadastro dos produtos comercializados no clube, relatórios de posição de 
estoque, entrada e saída de mercadorias; A entrada das mercadorias deverá ser feita através da digitação da nota 
fiscal das mercadorias. A nota fiscal deverá ser gravada relacionada a uma pessoa jurídica, que faz parte do 
cadastro dos associados, mas faz parte do tipo dos associados que não movimentam contas financeiras no clube.
O sistema ainda deverá controlar todos os cadastros básicos das funcionalidades a serem automatizadas

## Funcionalidades

1. **Cadastro dos Associados**
   - Armazenamento de informações básicas: nome, RG, CPF, telefones, endereço, dados bancários e tipo de associado.
   - Para associados do tipo "Dependente", registrar o identificador do associado responsável.

2. **Geração e Controle de Mensalidades**
   - Gerar mensalidades com referência, valor e data de vencimento.
   - Registro de pagamentos de mensalidades.

3. **Controle de Entrada e Saída**
   - Controle de acesso com identificador e senha.
   - Verificação de status de mensalidades e controle de tolerância de 15 dias após o vencimento.
   - Registro de data e hora de entrada e saída.
   - Permissão de saída somente se as contas no bar estiverem "fechadas".

4. **Conta Financeira**
   - Controle de depósitos e débitos na conta de cada associado.
   - Permissão para saque do saldo restante.

5. **Vendas**
   - Realização de compras e débito na conta do associado.
   - Aviso em caso de saldo insuficiente, com exceção para associados com limite de gastos.

6. **Controle de Estoque**
   - Cadastro de produtos e controle de entrada/saída de mercadorias.
   - Relatórios de posição de estoque.
   - Registro de notas fiscais de mercadorias associadas a pessoas jurídicas.

## Links

- **Casos de Uso:** [Acesse aqui](https://trello.com/invite/b/66be7c26e95f89b9f1a1533b/ATTI191352e50d3745cd667b7e4405eed9de8DF50B75/requisitos)
- **Diagrama:** [Visualize o diagrama](https://lucid.app/lucidchart/258f40f1-48fc-4e9b-b237-7ced3a1564e2/edit?viewport_loc=-2770%2C-444%2C3923%2C1903%2C0_0&invitationId=inv_7cd032d9-ef1a-438e-9be4-d82b76819ae8)
