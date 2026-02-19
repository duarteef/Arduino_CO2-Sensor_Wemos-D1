Avaliação prévia do CO₂ no recipiente:

1. Colocar duas folhas de papel mata-borrão umedecidas com água destilada, volume equivalente a 2,5 vezes a massa do papel, no interior do recipiente.
2. Fechar do recipiente de poliestireno transparente de forma lenta, para evitar o aumento da pressão interna (evitar aumento da concentração de gases, incluindo do CO₂).
3. Conectar uma fonte de alimentação de energia externa bivolt (tensão de saída 6-20 Volts) que esteja previamente ligada na rede elétrica, no Conector DC do controlador Wemos D1.
4. Desconectar o computador do controlador (cabo USB-MiniUSB).
5. Colocar o recipiente em condições de temperatura controlada à 25˚C no interior de uma câmara germinadora, com fotoperíodo de 12 horas.
6. Acompanhar de forma remota a emissão de CO₂ registrada a cada 5 minutos no canal previamente criado no site ThingSpeak.
7. Ao final, avaliar os dados baixados do ThingSpeak, em arquivo no formato CSV, retirar os “outliers”, obtendo-se os resultados médios a cada hora.

Avaliação do CO2 produzido pelas sementes:

8. As sementes devem ser previamente homogenizadas para obtenção de submostras de trabalho compostas por 25 sementes (o número de sementes pode ser reduzido quando as sementes forem grandes), as quais foi pesada em balança analítica. Será feito o desconto da umidade das sementes, determinado em outra subamostra de trabalho, da massa das sementes usadas na determinação do CO2. Para determinar a umidade seguimos recomendações apresentadas nas Regras para Análise de Sementes (https://wikisda.agricultura.gov.br/pt-br/Laborat%C3%B3rios/Metodologia/Sementes/RAS_2025/ras_2024_umidade).
9. Realizar a higienização do recipiente com álcool 70%, colocar as sementes sobre o substrato, constituído por novas folhas de papel mata-borrão umedecidas.
10. Fechar do recipiente de poliestireno transparente de forma lenta, para evitar o aumento da pressão interna (evitar aumento da concentração de gases, incluindo o CO₂).
11. Conectar a fonte de alimentação de energia externa bivolt (tensão de saída 6-20 Volts) que deve estar previamente ligada na rede elétrica, no Conector DC do controlador Wemos D1.
12. Desconectar o computador do controlador (cabo USB-MiniUSB).
13. Colocar a amostra em condições de temperatura controlada à 25˚C no interior de uma câmara germinadora, com fotoperíodo de 12 horas.
14. Acompanhar de forma remota a emissão de CO₂ registrada a cada 5 minutos no canal previamente criado no ThingSpeak.
15. Ao final da avaliação os dados devem ser baixados do ThingSpeak, em arquivo no formato CSV, sendo posteriormente tratados e retirados os “outliers”, obtendo-se os resultados médios a cada hora.
16. Fazer a normalização dos resultados, pela subtração dos valores de CO₂ do substrato úmido dos valores do CO₂ das sementes, isso é necessário pelo recipiente não ser totalmente hermético.
17. Apresentar os dados em mg^-1.L^-1.g^-1 de matéria seca, dividindo os valores do CO₂ normalizado, pela massa seca das sementes (descontar o percentual de umidade da subamostra usada para determinar o CO₂). Desconsiderar valores menores que zero.
