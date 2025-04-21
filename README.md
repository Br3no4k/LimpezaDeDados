🛠️ Etapas e Ações Realizadas
✅ 1. Padronização de Formatos e Tipos de Dados
📄 Limpeza de Texto com Expressões Regulares
Utilização da biblioteca re para eliminar caracteres especiais indesejados de colunas como produto e vendedor.

Remoção de espaços extras e símbolos não alfanuméricos para garantir consistência textual.

🔢 Campos Numéricos
Conversão de colunas como valor, quantidade, frete e total para os tipos numéricos (int ou float).

Remoção de símbolos como R$, pontos e vírgulas, padronizando para o separador decimal ponto (.), garantindo cálculos precisos.

📅 Datas
Conversão das datas para o formato internacional (YYYY-MM-DD), facilitando ordenações e comparações temporais.

🕒 Horários
Uniformização dos registros de hora no formato HH:MM:SS, assegurando integridade nas análises temporais.

🧩 2. Tratamento de Dados Inconsistentes
❌ Dados Ausentes
Registros com campos obrigatórios vazios (como valor e quantidade) foram descartados.

Campos não essenciais, como frete e datas nulas, foram preenchidos com valores calculados, como a média ou moda (valor mais frequente).

🧯 Remoção de Duplicatas
Entradas duplicadas foram identificadas e eliminadas, mantendo a versão mais recente ou completa por ocorrência.

📐 Correção de Cálculo no Campo Total
A fórmula total = valor * quantidade + frete foi verificada e corrigida onde necessário.

Registros com inconsistência no campo total foram recalculados corretamente.

👤 3. Padronização de Nomes de Vendedores
Nomes com grafias diferentes, incompletas ou inconsistentes foram revisados.

Quando não identificado, o campo foi padronizado como "DESCONHECIDO", assegurando coerência nas análises futuras.

🔎 Outras Etapas Importantes Realizadas
🧽 Remoção de Colunas Irrelevantes
Exclusão de colunas vazias ou que não agregavam valor analítico ao processo.

✏️ Renomeação de Colunas
Padronização e clareza dos nomes das colunas (ex: Data_Cadastro → Data de Cadastro).

🧮 Criação de Colunas Derivadas
Inserção de colunas auxiliares com valores calculados ou categorias derivadas, como:

Faixas de valor

Ano/Mês/Dia extraídos da data

Classificações condicionais

📤 Verificação Final
Após todas as etapas, foi feita uma validação geral:

Verificação de integridade

Pré-visualizações em tabelas e gráficos

Garantia de que os dados estavam prontos para análise

🧰 Ferramentas Utilizadas
Ferramentas de tratamento e visualização (ex: Power Query, Excel, Power BI ou scripts em Python)

Expressões regulares (RegEx) para limpeza de texto

Conversores de tipo e transformações manuais/automáticas

✅ Conclusão
A limpeza de dados foi executada com sucesso, resultando em um dataset limpo, padronizado, sem duplicidades e pronto para ser utilizado em relatórios, dashboards e análises aprofundadas. Todas as inconsistências foram tratadas com critérios técnicos bem definidos, garantindo confiabilidade e qualidade nos resultados futuros.

