# Produtos

Caberá ao fornecedor realizar a manutenção de seus produtos, mantendo estoque, e status do produto (_ativar se o produto estiver em linha ou inativar, caso o produto saia de linha_) utilizando como base comum o Código de Fornecedor. Caberá ao ERP, através do integrador ERP/Plataforma E-commerce, enviar a informação de estoque as plataformas de vendas da ConnectParts (00k e Vtex). Após integrado e exposto o anuncio no site, ao ser feita uma venda destes itens, o integrador ERP/Plataforma E-commerce consome esta compra e imputa no ERP normalmente o pedido.

Após a produção do anúncio for finalizada, o GA deverá inserir na planilha de ativação de anúncios do DOCS e antes do comercial realizar a ativação do anúncio deverá inserir na planilha ‘’Produtos Dropshipping’’ para que o departamento de frete da Connect Parts realize a validação do produto e insira no modal correto.

Neste momento as regras de frete serão inseridas em todos os canais de vendas da ConnectParts.

Quando o fornecedor atualizar em tempo real a quantidade de estoque de determinado produto e o estoque for igual ou menor que 02 unidades, iremos zerar o estoque do produto no nosso sistema para não corrermos o risco de vender e não conseguirmos atender o cliente e ao incluir estoque acima de 2 unidades nosso estoque deverá ser atualizado com quantidade real.

**Casos**

- Caso o fornecedor seja fabricante, poderemos optar por trabalhar com estoque fictício.

- Caso o fornecedor seja revendedor deverá manter atualizado em tempo real o sistema de estoque. 

Dentro do Sigeco 2.0 em **T.I/Admin> Integrações > Log Dropshipping>** existe o controle dos status de cada etapa do Dropshipping. Se um status não alterar em 24hs úteis (_exceto sábado, domingo e feriado_) ficará em vermelho para acompanhamento e cobrança.

![produtos](http://developers.connectparts.com.br/imagens/drop2/dropforn06.png)

