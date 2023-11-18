# MILP mathematical modeling

MgC enhances decision-making and optimization in microgrid design, MILP serves as a valuable tool for optimization and decision support in various fields. It allows for efficient resource allocation, cost reduction, and improved operations, making MgC a pro in addressing complex real-world challenges across different domains.

**Weighted multi-objective**

The MgC uses weighted multi-objective approach to evaluate and optimize microgrid designs. It calculates a single metric, "F," by considering various components (F\_1, F\_2, ..., F\_k) and their importance. The weights (α\_1, α\_2, ..., α\_k) are assigned to these components, and "F\_1,ref," "F\_2,ref," ..., "F\_k,ref" serve as reference values. This formula allows for a customized evaluation of microgrid designs and facilitates decision-making by producing a clear and objective result.&#x20;

$$
min\ F = (α_1\frac{F_1}{F_1,ref}+α_2\frac{F_2}{F_2,ref}+....α_k\frac{F_k}{F_k,ref}); 
\\∑_{}^kα_k=1(k=1,2,...K)
$$

This is crucial for microgrid design because it enables:

* Customization of designs based on specific requirements.
* Evaluation of performance and optimization of microgrid solutions.
* Objective decision-making by providing a single, quantifiable metric (MgC).

**Economical modeling**

A core feature of MgC, it ensures economic viability in microgrid design, optimizing component choices, energy management, and income generation. It balances costs and income for efficient economic management. This formula is crucial for optimizing economic efficiency in microgrid design by minimizing costs and maximizing income.

MgC minimizes total economic cost, consisting of component costs, energy costs and income from energy production by this approach.

$$
min\:F_{ecn} =∑_{\substack{i}}C_{Cmp,i}+∑_{\substack{n}}C_{Ene,n}-∑_{\substack{i}}B_{Ene,i} \\\ \\∑_{\substack{i}}C_{Cmp,i} \:is\:component\:cost
\\∑_{\substack{n}}C_{Ene,n} \:is\:Energy\:cost 
\\∑_{\substack{i}}B_{Ene,i} \:is\:Energy\:income
$$

MgC approaches for precise **component cost evaluation**, ensuring economic considerations in microgrid design. It is crucial for comprehensive cost assessment, considering all economic aspects of individual components.

It calculates the total cost of a microgrid component "i," including investment cost, financing cost, incentives, and operational and maintenance costs.

$$
C_{cmp,i} =γ_iC_{Cmp,i}+γ_iC_{Fnc,i}-γ_{i}ρ_{Inc,i}+∑_{\substack{v}}C_{OM,v,i} \\\ Where\:(γ_iC_{Cmp,i})\:is\:Investment\:cost
\\(γ_iC_{Fnc,i}) \:is\:Financing\:cost 
\\(γ_{i}ρ_{Inc,i} )\:is\:Incentives  
\\(∑_{\substack{v}}C_{OM,v,i})\:is\:OMC
$$

Mgc cleverly calculates the **operational and maintenance cost (OMC)** of a microgrid component "i" by considering three key components: size-independent OMC, size-dependent OMC, and operation-dependent OMC.&#x20;

It provides a detailed breakdown of the costs associated with maintaining and operating the component. In MgC, this approach plays a vital role in precisely estimating OMC, aiding in cost assessment and informed decision-making during microgrid design.

$$
∑_{\substack{v}}C_{OM,v,i}=μ_ic_{OM,1,i}+γ_ic_{OM,2,i}+∑_{\substack{t}}P_{in,i,t}c_{OM,3,i}\varDelta t\\Where\:(μ_ic_{OM,1,i})\:is\:Size-independent\:OMC\\(γ_ic_{OM,2,i})\:is\:Size-dependent\:OMC\\(∑_{\substack{t}}P_{in,i,t}c_{OM,3,i}\varDelta t)\:is\:Operation-dependent\:OMC
$$

MgC adeptly quantifies the **"import cost"** for a specific energy source within a microgrid by considering the total cost incurred from "importing power" over a given time period. It serves as a crucial tool in the economic analysis of microgrid operations, helping to evaluate the expenses associated with "importing energy" and aiding in informed decision-making regarding energy sourcing and utilization.

$$
Import\: cost\: C_{Ene,n}=∑_{\substack{t}}P_{imp,n}c_{imp,n}\varDelta t
$$

Mgc calculates the **"energy income"** for a specific microgrid component "i" by taking into account the revenue generated from "exporting power" and "self-consumption" over a specified time period. It is a vital tool in the economic analysis of microgrid components, providing insights into the income earned from exporting excess power and self-consuming generated energy, thus supporting sound financial decision-making within the context of MgC (Microgrid Control).

$$
B_{Ene,i}=∑_{\substack{t}}P_{exp,i}b_{exp,i}\varDelta t-∑_{\substack{t}}P_{sfc,i}b_{sfc,i}\varDelta t

\\\\Where (∑_{\substack{t}}P_{exp,i}b_{exp,i}\varDelta t)\:is\:Export\:income\\
(∑_{\substack{t}}P_{sfc,i}b_{sfc,i}\varDelta t)\:is\:Self-consumption\:income
$$

**Environmental modeling**

An integral feature of MgC is its capability to incorporate environmental modeling, employing mathematical and computational techniques to predict and assess environmental changes, such as climate shifts and pollution dispersion. This feature is vital in enhancing the microgrid's resilience and sustainability, supporting informed decision-making for environmental resource management and policy development within the system.

An intriguing feature of MgC is its ability to calculate the **"Fraction of Primary Energy"**, allowing you to uncover the intriguing dynamics of energy consumption within a system. By determining the proportion of primary energy used from various sources, MgC offers a captivating perspective on energy efficiency and resource distribution, making it an indispensable tool for enhancing sustainability and informed energy management decisions.

$$
f_{PE}=\frac{\displaystyle\sum_{t=1}^T\displaystyle\sum_{n=1}^NPE_{n,t}}{\displaystyle\sum_{t=1}^T\displaystyle\sum_{k=1}^KNE_{k,t}}
$$

MgC quantifies the **proportion of final energy**(FE) used within a system´s net energy(NE), aiding energy efficiency assessments and sustainable decision-making. As a MgC feature, it optimizes final energy utilization in the microgrid, fostering eco-friendly practices for efficiency and sustainability.

$$
f_{FE}=\frac{\displaystyle\sum_{t=1}^T\displaystyle\sum_{f=1}^MFE_{m,t}}{\displaystyle\sum_{t=1}^T\displaystyle\sum_{k=1}^KNE_{k,t}}
$$

MgC calculates the **total greenhouse gas emissions** within a system by summing emissions from various sources over a specific time period. It's crucial for assessing the system's environmental impact, understanding emissions of greenhouse gases, and promoting environmental sustainability within the microgrid, making it an integral feature of MgC.

$$
Em_{CO_2-equ}=\displaystyle\sum_{t=1}^T\displaystyle\sum_{n=1}^NEm_{CO_2,equ,n,t}
$$
