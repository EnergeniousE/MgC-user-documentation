---
description: >-
  The key advantage of MgC is its ability to leverage mathematical models for
  precise and efficient microgrid design and operation.
---

# MILP modeling and optimization models

**MILP - Examples of constraints**

Mathematical models are abstract representations of real-world systems, processes, or phenomena, formulated using mathematical equations. These models enable quantitative analysis, prediction, and optimization, making them invaluable tools across diverse domains, from science and engineering to economics and social sciences.

**Mgc choice of technologies and capacities**

MgC makes the decisions regarding the selection of specific technologies (e.g., solar panels, batteries, energy management systems) and their respective capacities within the microgrid design. These choices are essential for optimizing the microgrid's performance, ensuring it meets energy demands efficiently and effectively.&#x20;

The solver efficiently computes the energy source and its associated capacities, as depicted in the formula provided below.

$$
μ_i γ_{min,i}≤ γ_{i}≤ μ_i γ_{max,i}
\:\:\:\:\:\:(i=1,2,3....,I)\\μ_i ∈ [0,1] \:\:\:\:\:( i=1,2,3....,I)
$$

In MgC, this formula defines constraints on the variable ($$γ_{i}$$) representing specific conditions for a component (i). It ensures that ($$γ_{i}$$) falls within a range defined by the parameter ($$μ_{i}$$), which is limited to values between 0 and 1. This constraint is applied to various component types (i) within the microgrid.

{% hint style="info" %}
_Where_

* _**μ** is to indicate configuration choices of certain energy sources (e.g., solar panels) (1 for active, 0 for inactive)._
* _**γ** is the min and max capacities of the technology._
{% endhint %}

**Operational characteristics components/system**

MgC encompasses the efficient functioning of components like energy sources, storage, and load management, as well as the system's response to grid conditions. These aspects are vital for optimizing microgrid performance and ensuring cost-effective, reliable operation.

The MgC solver utilizes the provided mathematical models to compute and oversee the system's behavior and responses.

$$
P_{ex,i,t}=η_iP_{in,i,t}  \:\:\:\:\:\:(i=1,2,3....,I;t=1,2,3....,T)
$$

The power leaving($$P_{ex}$$) the system is determined by multiplying the component's efficiency(η) with the power input($$P_{in}$$) for the time(t) into the system.

$$
v_{i,t} P_{in,min,i}(γ_{i})≤ P_{in,t,i} ≤ v_{i,t}P_{in,max,i}(γ_{i})
\:\:\:\:\:\:(i=1,2,3....,I;t=1,2,3....,T)
$$

This formula imposes constraints on the power input of a component (i) at a given time (t) in a microgrid. It ensures that the power input falls within the predefined minimum and maximum limits based on the binary variable, which determines whether the component is active (1) or inactive (0). These constraints are applied across various component types (i) and periods (t). The parameter gamma (γ) may represent specific conditions or states associated with each component (i).

$$
P_{in,i,t-1}-\boldsymbol{\nabla}_{Pdown,i} P_{in,max,i}(γ_{i}) ≤ P_{in,i,t}≤P_{in,i,t-1}+\boldsymbol{\nabla}_{Pup,i}P_{in,max,i}(γ_{i})
\\(i=1,2,3....,I;t=1,2,3....,T)
$$

In MgC, this formula constrains the power input ($$P_{in,i,t}$$) of a specific component (i) at a given time ((t)) to be within a range determined by the power input at the previous time step ($$P_{in,i,t-1}$$) adjusted by factors represented by $$\boldsymbol{\nabla}_{P{down,i}}$$) and $$\boldsymbol{\nabla}_{Pup,i}$$). These constraints are associated with the component's maximum power input ($$P_{in,max,i}$$) under specific conditions ($$γ_{i}$$) and are applicable across various components (i) and periods (t) in the microgrid.

$$
ν_{i,t} ∈ [0,1]  \:\:\:\:\:( i=1,2,3....,I; t=1,2,3,...T)
$$

{% hint style="info" %}
$$"ν_{i,t}"​$$_is a binary switch \[0,1] for including or excluding specific microgrid components for the component(i), at the time(t)._

$$"\boldsymbol{\nabla}"$$ is the rate of change of a scalar field or function for its variables. In microgrid modeling, this can be crucial for understanding how various parameters, such as power consumption or renewable energy generation, change concerning spatial or temporal variables._
{% endhint %}

**Balancing of coupled components and overall system by MgC**

MgC precisely manages the coordination of components in a microgrid through [mathematical modeling](milp-mathematical-modeling.md). It optimizes the interaction between renewable energy sources, energy storage, and loads, ensuring efficient, reliable, and cost-effective microgrid operation, thereby enhancing energy supply and sustainability.

The following mathematical expression describes how various components within the microgrid system are balanced to ensure its overall stability and efficiency.

$$
∑ P_{i,n,t}=0,\:\:\:\:\:( i=1,2,3....,I;n=1,2,3,...N;t=1,2,3,...T)
$$

{% hint style="info" %}
_Where,_&#x20;

* _**P:** represents the power in the whole system._
* _**i:** represents different types of components within a microgrid, such as solar panels, battery storage, or loads._
* _**n:** represents different instances or units of those components, like individual solar panels or batteries._
* _**t:** represents discrete time intervals or time steps used to model the behavior of the microgrid components over time._
{% endhint %}

To balance the system, the MgC solver provides a flexible and precise way to comprehensively analyze, optimize, and assess the performance of microgrid components, instances, and time intervals, ensuring efficient and cost-effective designs.

**Balancing of components with storage characteristics**

MgC effectively balances components with storage characteristics within a microgrid through precise mathematical modeling. This optimization ensures efficient and reliable microgrid operation, particularly regarding energy storage, enhancing overall system performance.

MgC can efficiently achieve balance within components equipped with storage systems using the formula outlined below.

$$
E_{i,t}=η_{st,i}E_{i,t-1}+(η_{ch,i}P_{in,i}-(1/η_{ds,i})P_{ex,i})Δt
$$

{% hint style="info" %}


_Where,_

* _**E:** Energy_
* _**η:** Efficiency of the component_
* _**P:** Power input and output to the system_
* _**Δt:** Time difference between operation periods_
* _**ch:** Component characteristics_
* _**t:** Periods_
* _**i:** Component type_
* _**st:** Component's storage_
{% endhint %}

MgC integrates key parameters like energy, efficiency, power, time intervals, and component characteristics to optimize the operation of various components within a microgrid system, ensuring efficient and effective performance.
