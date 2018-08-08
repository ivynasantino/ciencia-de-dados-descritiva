# departamentos-ufcg

A base de dados foi vinda do dump de abril dos dados abertos do governo federal sobre seus servidores, publicados no portal de transparência do governo federal.

Contém apenas informações de pessoal nas Unidades Acadêmicas da UFCG, excluindo pessoal de administração nos Centros. Também possui menos colunas, focando no que provavelmente é de interesse para alguém analisando apenas a UFCG.
 
* UORG_LOTACAO Unidade acadêmica de lotação do funcionário
* Outro Número de funcionários na UA que não são professores
* Professor 20h Número de professores com carga horária 20h/semana na UA
* Professor 40h ou DE Número de professores com carga horária 40h/semana na UA, sejam eles Dedicação Exclusiva ou não
* idade_25perc, idade_mediana e idade_75perc : 25, 50 e 75 percentil da idade dos funcionários no cargo (ex: idade_25perc = 10 significa que 25% dos funcionários, sejam eles professores ou não, da UA tem 10 anos ou menos na profissão.)
