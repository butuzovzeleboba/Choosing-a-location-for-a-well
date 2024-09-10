# Project Overview
Overview
Assume you work at the mining company "GlavRosGosNeft." You need to decide where to drill a new well.

You are provided with oil samples from three regions: each with 10,000 fields where oil quality and reserves were measured. Build a machine learning model to determine the region where mining will yield the highest profit. Analyze potential profit and risks using the Bootstrap technique.

Steps to select a location:
- In the chosen region, search for fields and determine feature values for each.
- Build a model and estimate reserves.
- Select fields with the highest estimated values. The number of fields depends on the company's budget and the cost of developing one well.
- Profit equals the total profit from the selected fields.

Conclusion
The second region proved to be the most profitable with an estimated average profit of 489.66 million rubles. Unlike other regions where the probability of losses exceeds 2.5%, region 2 shows a confident profitability with a 95% confidence interval that does not include negative values.

After preprocessing the data and conducting an initial analysis, a model was trained, showing that the average raw material reserves in all regions are below the break-even point of 111 thousand barrels. This indicates the unprofitability of developing all wells at once. However, by carefully analyzing and selecting the 200 most promising wells, region №2 stands out as the least risky in terms of potential losses. Thus, the strategy of focusing on selective development in region №2 appears to be the most reasonable for minimizing risks and optimizing financial results.
# Обзор проекта
Обзор
Предположим, вы работаете в добывающей компании "ГлавРосГосНефть". Нужно решить, где бурить новую скважину.

Вам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.

Шаги для выбора локации:
- В избранном регионе ищут месторождения, для каждого определяют значения признаков;
- Строят модель и оценивают объём запасов;
- Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.

Вывод
Второй регион оказался наиболее прибыльным с прогнозируемой средней прибылью в 489.66 млн. рублей. В отличие от других регионов, где вероятность убытков превышает 2.5%, регион 2 демонстрирует уверенную доходность с 95%-м доверительным интервалом, не включающим отрицательные значения.

После предобработки данных и проведения первичного анализа, была обучена модель, которая показала, что средний запас сырья во всех регионах ниже точки безубыточности в 111 тыс. баррелей. Это свидетельствует о нерентабельности разработки всех скважин сразу. Однако, при тщательном анализе и выборе 200 наиболее перспективных скважин, регион №2 выделяется как наименее рискованный с точки зрения возможных убытков. Таким образом, стратегия фокусировки на выборочной разработке в регионе №2 представляется наиболее целесообразной для минимизации рисков и оптимизации финансовых результатов.
