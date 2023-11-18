# Nodal networks examples

The image represents a nodal network encompassing various energy domains: electric power, heat, and cooling in MgC network modeling. Within each domain, medium and low energy networks are interconnected. These networks draw energy from sources like the power grid, natural gas grid, and on-site renewables. Technical components like transformers, PV plants, co-generation units, and others efficiently transfer energy to their respective domains. MgC manages this energy distribution seamlessly through nodal networks, ensuring an efficient and stable grid. This approach guarantees uninterrupted operations, making it possible to achieve project objectives successfully.

<figure><img src="../../../.gitbook/assets/2023-10-29 09_48_07-MicroGrid-Creator_Modeling-Optimization.pdf - Adobe Acrobat Reader (32-bit).png" alt=""><figcaption><p>a). MgC 3-node-system network modeling</p></figcaption></figure>

MgC intelligently models nodes using domain layers, as depicted in image 'b', while taking into account constraints and pertinent parameters. The top two domain layers cater to Alternating Current(AC) with both Medium and Low voltages(MV & LV). Subsequently, the heating and cooling domains are represented. Notably, the black dots signify nodes where energy inputs and outputs facilitate the exchange of energy and information. This interconnected approach ensures an efficient and stable network system.

**Electric power domain**

This is how MgC establishes the nodal network: It begins with the external power distribution grid, injecting energy into node1 (n1). From there, energy is seamlessly transferred to node2 (n2), and node 3 (n3) serving as a central junction for MV and LV connections. This facilitates the interaction of technical components t2 and t3 within the electric power domain. Additionally, t4 and load l1, along with natural gas supply to the co-generation plant (t4), operate within this domain layer. MgC's design ensures an efficient and interconnected nodal network for energy distribution.

**Heating domain**

The electric power domain layer is followed by the heating domain layer, where different heating equipment, such as t5, and loads, like l2 and l3, are found. Additionally, an external load, l4, connects to another node in a separate nodal network, ensuring versatile integration within the system. This arrangement is structured to allow the system to be efficiently and effectively operated, creating a well-organized and interconnected energy ecosystem, all facilitated by MgC.

**Cooling domain**

The heating domain layer is succeeded by the cooling domain layer, housing a nodal network with cooling equipment, including t6, t7, and a load labeled as l5. Notation for each domain layer is provided in the image description, ensuring clarity and organization within the system's structure.&#x20;

This approach, guided by MgC, allows for the systematic and efficient operation of various components, creating a well-coordinated and interconnected energy ecosystem.



<figure><img src="../../../.gitbook/assets/2023-10-29 09_48_53-MicroGrid-Creator_Modeling-Optimization.pdf - Adobe Acrobat Reader (32-bit).png" alt=""><figcaption><p>b). MgC decentralized Multi-energy systems</p></figcaption></figure>
