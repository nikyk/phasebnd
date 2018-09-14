# phasebnd
command line tool for specific area of polymer physics: computing phase boundaries and minimization of free energy

# Physics background in a few words
## EN
Free energy is thermodynamic function in molecular physics (see <https://en.wikipedia.org/wiki/Thermodynamic_free_energy>).
Some polymers can be in different phase states. As a rule, the more complex the polymer structure, the more phase states are possible. The most stable phase is the phase, the free energy of which is minimal. With a smooth change in temperature, the phases become less favorable and are replaced by others whose free energy is lower at a given temperature.
The condition of equilibrium (coexistence) of phases is the equality of free energies.
Phase diagram is picture of the change in the phase state with a change in the temperature and some parameter that governs polymer composition.
## RU (краткое пояснение по физике задачи)
Свободная энергия-- это термодинамическая функция в молекулярной физике.
Некоторые полимеры могут находиться в разных фазовых состояниях. Как правило, чем сложнее структура полимера, тем большее число фазовых состояний возможно. Наиболее устойчива та фаза, свободная энергия которой минимальна. При плавном изменении температуры, устойчивая фаза может стать неустойчивой её сменяет другая фаза, у которой свободная энергия при данной температуре ниже. При одинаковых условиях, возможно сосуществование нескольких фаз, если их свободная энергия близка. Чем сильнее разница в свободных энергиях фаз, тем быстреее произойдет переход от менее выгодной к более выгодной фазе. Условием равновесия (сосуществования) фаз является равенство свободных энергий.
Фазовая диаграмма -- это картина изменения фазового состояния полимера при изменении температуры и какого-либо параметра, характеризующего состав полимера.

# Math details:
## EN
There are M phases, each of which is given by its function of free energy.
There is a set of M functions F_m (X_m, p), where X_m is a vector of variables of dimension N_m, p is a vector of parameters of dimension P. The parameter vector is one for all functions F_m.
For different functions F_m, the dimension N_m can be different.
In the parameter set p, two parameters have a special meaning: omega (inverse temperature) and alpha ("composition parameter")
## RU
Имеется М фаз, каждая из которых задана своей функцией свободной энергии. Эти функции заданы в виде аналитических формул. Таким образом, имеется набор из M функций F_m(X_m,p), где X_m -- вектор переменных размерности N_m, p-- вектор параметров размерности P. Вектор параметров один для всех функций F_m.
Для разных функций F_m размерность N_m может быть разная. 
В наборе параметров p два параметра имеют особенный смысл: omega (обратная температура) и alpha ("параметр состава")

