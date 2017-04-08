# Numbers in Ads

Experimental procedure in [Inquisit] to evaluate if numbers in specifications are interpreted according to the same heuristics used at prices.

Procedure written by **Krzysztof Kutt**. Stimuli prepared by **Konrad Szklarski**. Docs prepared by **Krzysztof Kutt**, **Joanna Nowak**, **Konrad Szklarski** & **Anna Szlezynger**. The project was prepared as a part of "Eksperymentalna psychologia reklamy" (Experimental psychology of advertising) course at Jagiellonian University / [Institute of Psychology] during Winter term 2015/2016.

### How does it work?
##### Stimuli
Notebook advertisement with the same image and price (2000 PLN).
They differ with CPU frequency. There were 6 different values in accurate and round versions:

|  Rounded: | 1600 | 1650 | 1700 | 2000 | 2050 | 2100 |
|:---------:|:-:|:-:|:-:|:-:|:-:|:-:|
| Accurate: | 1616 | 1659 | 1721 | 2018 | 2054 | 2111 |

Each of them was written with normal and bigger font size (what sums up to 24 different stimuli).

##### Groups
There were 4 groups. In each group 6 stimulus was presented (only one stimuli from each of "levels"), e.g. in the 1st group values `1600`, `1650_`, `1700_`, `2018_`, `2054`, `2100` was presented (`_` represents value with bigger font size).

##### Procedure
 1. One training trial is given (without CPU frequency).
 2. User is informed that "Notebooks at the price of 2000 PLN usually have 2 core processors 1700-2000 MHz".
 3. 6 different stimulus (notebook ads) is presented in random order. For each of them, the user evaluates the attractiveness on 1-11 Likert scale. Response time is also measured.

### Our hypotheses
If numbers in specifications are interpreted according to the same heuristics used at prices (but in different direction beacuse better price = lower price and better specification = bigger value) then:
- *H1:* **rounded** values will be evaluated as **better**
- *H2a:* **bigger font-size** values will be evaluated as **better**
- *H2b:* consistent positive interaction **rounded** \* **bigger font-size** will be evaluated as **better** than inconsistent interactions **rounded** \* **normal font-size** and **accurate** \* **bigger font-size**
- *H2c:* consistent negative interaction **accurate** \* **normal font-size** will be evaluated as **worse** than inconsistent interactions (as above)
- *H3:* consistent interactions (**rounded** \* **bigger font-size** and **accurate** \* **normal font-size**) will be evaluated **faster** than inconsistent interactions (as above)

### Files
- [atrakcyjnoscReklam.iqx] -- Inquisit procedure
- [images in procedure directory] -- set of stimuli
- [data directory] -- raw results (`*.iqdat`) and analysis (`wyniki.xls`) 
- [Problem.pdf] -- problem description (with slides about heuristics used at prices) (in Polish)
- [Raport.pdf] -- final raport from the project (in Polish)

[Institute of Psychology]: <http://www.psychologia.uj.edu.pl/index.php/eng/>
[Inquisit]: <http://www.millisecond.com/products/inquisit5/weboverview.aspx>
[atrakcyjnoscReklam.iqx]: <procedure/atrakcyjnoscReklam.iqx>
[images in procedure directory]: <procedure/>
[data directory]: <data/>
[Problem.pdf]: <Problem.pdf>
[Raport.pdf]: <Raport.pdf>

