I am trying to calculate total USD Sales using the following formula

SUMX('Cost of Product Offering',[Per Unit Sales price]*RELATED('Sales Transactions'[Qty])*RELATED('USD-CAD Exchange Rates'[USD]))

Keep getting the following error messages "Parameter is not the correct type" and "Cannot find name [Qty]"

