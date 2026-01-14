O modelo de cobrança adotado por padrão pela AWS é o de "pagar pelo uso". Por exemplo, enquando uma instância [[EC2]] estiver sendo executada, a cobrança será efetuada pelos minutos de execução com base na CPU e RAM utilizadas; caso a instância seja parada, a cobrança ainda pode ocorrer se houver discos adicionais de armazenamento.
No caso temos a cobrança por:
- uso de CPU
- uso de RAM
- uso de armazenamento
- uso de espaço alocado em volumes [[EBS]]
- volume de dados de saída (tráfego de saída) de uma região ou zona (volume de tráfego de entrada não é cobrado)

O segundo modelo é o de "reserva e planejamento", destinado a contratação previsível de uma capacidade de recurso por um preço fixado, assumindo um compromisso de ao menos um ano e podendo obter um desconto de até 75% do valor padrão da capacidade contratada no modelo "on-demand" ou #pay-as-you-go. Este modelo se associa com o desconto progressivo por volume de uso adicional necessário (mais significativo caso o pagamento seja realizado antecipadamente). Sendo assim, é um preço cobrado por volume, escalonado, em que quanto mais se usa, menos se paga unitariamente.