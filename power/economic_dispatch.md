@def title = "Economic Dispatch - Mambo Power"
@def tags = ["syntax", "code"]

# Economic Dispatch

\tableofcontents <!-- you can use \toc as well -->

## Generation of electrical energy

The generation of electrical energy involves the conversion of different natural forms of energy into electrical power. Electrical energy is unique as it must be produced and transmitted instantly when needed, which presents distinctive technical and economic challenges in the power industry.

**Key Points:**

- Electrical energy, like other commodities, is manufactured from natural energy sources.
- Unlike most commodities, electrical energy must be produced and delivered instantly when required, which is a process that takes only a fraction of a second.
- Various natural sources provide different forms of energy, such as water pressure, chemical energy from fuels, and nuclear energy, all of which can be converted into electrical energy using suitable arrangements.
- A typical setup includes an alternator connected to a prime mover, with the prime mover being powered by energy sources like fuel combustion, water pressure, or wind force.
- For example, the chemical energy in coal can be used to produce high-temperature and high-pressure steam, which drives a steam engine or turbine, converting heat energy into mechanical energy and, ultimately, into electrical energy.
- Similar machinery and equipment can be employed to convert various forms of energy into electrical power.

In essence, the generation of electrical energy is the process of transforming natural energy sources into a vital and instantly accessible form of power.

## Efficient economic operation of electric power generation 

Efficient and economically optimal operation and planning of electric power generation systems are crucial in the electric power industry. Before 1973, U.S. electric utilities spent around 20% of their total revenues on fuel for electricity production. However, by 1980, this figure had surged to over 40% due to a rapid escalation in fuel prices triggered by the oil embargo. The efficient use of available fuel is becoming increasingly significant, both economically and in terms of preserving finite natural resources.[^1]

Even a minor percentage of savings in the system's operation can result in significant cost reductions and fuel consumption. Given these implications, the efficient operation of electric power generation systems has been a focus of attention for engineers over the years.

Periodic fluctuations in fuel prices and the impact of inflation further emphasize the economic importance of this area and the necessity for developing methods and techniques for cost-effective power generation system operation.


## Economic Dispatch problem

Economic Dispatch is a critical aspect of power system operations that aims to minimize the cost of generating electricity while meeting the load demand. 

The primary goal of Economic Dispatch is to determine the optimal generation levels for each power generator within a power system. This optimization problem involves finding the generation schedule that minimizes the total generation cost, considering factors such as fuel costs, generator constraints, and system load.


The Economic Dispatch problem can be mathematically formulated as follows:

**Minimize:**

\[
\sum_{i=1}^{n} C_i(P_i)
\]

Where:
- $C_i(P_i)$ represents the cost of generation for generator $i$ as a function of its output $P_i$.
- $n$ is the total number of generators.

**Subject to:**

1. **Power Balance Equation:**

\[
\sum_{i=1}^{n} P_i = P_{\text{load}}
\]

Where:
- $P_i$ is the power output of generator $i$.
- $P_{\text{load}}$ is the total system load.

2. **Generator Output Limits:**

\[
P_i^{\text{min}} \leq P_i \leq P_i^{\text{max}}, \quad \text{for } i = 1, 2, \ldots, n
\]

Where:
- $P_i^{\text{min}}$ and $P_i^{\text{max}}$ are the minimum and maximum power output limits for generator $i$.



## References
[^1]: Wood Allen, J Bruce, F Wollenberg, and Sheblé Gerald B. 2014. Power Generation Operation and Control Third ed. Hoboken New Jersey: Wiley-Interscience.

