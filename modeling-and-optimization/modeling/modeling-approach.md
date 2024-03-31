# Modeling approach

MgC's modeling approach is both simple and potent, emphasizing the extensive linearization of system models. This linearization strikes a crucial balance, providing adequacy for decision support while simplifying the modeling process. This streamlined approach ensures that problem-solving takes place within a reasonable timeframe, making it an efficient and effective tool for microgrid design and optimization.&#x20;

MgC customizes the model based on user specifications and objectives, which may include economic and environmental factors. It meets the user objectives using the following methods:

<details>

<summary>Linearization of system models</summary>

System model linearization is a captivating process that transforms intricate, non-linear relationships within a system into simplified, linear approximations. This technique enhances the modeling and analysis of the system, allowing for more straightforward problem-solving, decision support, and optimization.

</details>

<details>

<summary>MILP (Mixed Integer Linear Programming)</summary>

MgC uses the MILP techniques which are popular in Operations Research. MILP is a widely used mathematical optimization technique that addresses problems with both continuous and discrete variables, making it valuable for complex decision-making and resource allocation.

</details>

<details>

<summary>Decision and operation related variables</summary>

**Continuous variables:** in the context of mathematical optimization, are numerical values that can take any real number within a specified range. They provide a wide spectrum of possibilities and are used to represent parameters like capacity, efficiency, and performance characteristics in microgrid design.

**Integers+Binaries:** In microgrid modeling, they are used to depict quantities, such as the number of units of a particular component or the on/off state of a device.

In the MgC tool, the inclusion of continuous variables allows for precise adjustment of parameters like the capacity of energy sources or the efficiency of storage systems. Integers and binaries are utilized to control discrete aspects, such as deciding how many units of a specific component to include in the microgrid or whether a particular component is activated (1) or deactivated (0).

This combination of variable types in MgC enhances the flexibility and granularity of microgrid design, enabling users to make detailed and optimized decisions while considering both continuous and discrete factors.

</details>

<details>

<summary>Constraints + Boundaries</summary>

In microgrid modeling, constraints, and boundaries are critical limitations that guide technical design and operation. They encompass factors such as physical specifications, operational restrictions, and safety requirements, ensuring that the microgrid operates within defined parameters.

**Technical design constraints:** These constraints restrict the microgrid's design based on physical and operational characteristics, such as the maximum capacity of components, voltage limits, and temperature thresholds. MgC incorporates these limitations to maintain compliance with technical specifications.

**Operational constraints:** Operational constraints define how the microgrid functions, accounting for factors like load demands and energy source availability. MgC considers these constraints to ensure effective microgrid operation within operational boundaries.

**Safety and regulatory boundaries:** These boundaries encompass legal and safety requirements, including environmental standards and regulatory policies. MgC adheres to these boundaries to guarantee microgrid designs and operations align with safety and compliance standards.

</details>

Through the use of MILP techniques, MgC offers an optimized model that closely approximates the objectives set by the user.

MgC's modeling approach is both methodical and user-friendly, allowing for efficient and effective application in various contexts.&#x20;

As shown in the below graph, It begins with linear programming, represented in grey, and then seamlessly transitions to integer programming, illustrating feasible solutions with black dots on the x and y axes. The next step involves plotting user-specified objective planes, and pinpointing the exact intersection point where two lines meet. This point of convergence, closely matching the user's objective, is highlighted as a blue line in the graph below.&#x20;

<figure><img src="../../.gitbook/assets/2023-10-28 11_41_55-MicroGrid-Creator_Modeling-Optimization.pdf - Adobe Acrobat Reader (32-bit) (1).png" alt="" width="272"><figcaption><p>MgC modeling approach</p></figcaption></figure>

MgC's approach is distinctive, combining both network and process-oriented modeling. This integration provides a comprehensive understanding of microgrid dynamics, optimizing configurations based on a complete view of the network structure and operational processes. MgC ensures the efficient design and reliable operation of microgrids, meeting user-defined objectives for cost-efficiency and performance reliability.

**Network-oriented modeling approach**

MgC harnesses network-oriented modeling to map the intricate web of connections between energy sources, loads, and storage within a microgrid. This approach resembles creating a digital blueprint of technical component interactions, optimizing the microgrid for enhanced performance and cost-effectiveness.

<figure><img src="../../.gitbook/assets/Picture6 (1).png" alt="" width="375"><figcaption><p>MgC´s network-oriented modeling approach</p></figcaption></figure>

**Process-oriented modeling approach**

In the MgC framework, a process-oriented modeling approach involves visualizing the step-by-step workflow of various components and operations within a microgrid. It's like creating a roadmap that outlines the journey of energy from generation to consumption. MgC employs this approach to simplify microgrid design and operation, resulting in a more efficient and dependable energy system.

<figure><img src="../../.gitbook/assets/Picture8 (1).png" alt="" width="375"><figcaption></figcaption></figure>
