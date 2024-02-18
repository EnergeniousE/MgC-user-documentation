# Rooftop system

**Rooftop System concept:**

The 'Rooftop system concept' refers to the design and implementation of solar panels on building rooftops to generate electricity from sunlight. By harnessing solar power directly from rooftops, this approach helps to reduce reliance on traditional energy sources, lower electricity bills, and contribute to a more sustainable and environmentally friendly energy system.

**MgC's capability in "Rooftop System" modeling:**

MgC stands out in the rooftop system by offering a unified platform for designing and managing integrated energy systems. Its functionalities encompass:

1. **Effortless Rooftop System design**: MgC simplifies the process of designing "Rooftop Systems" by providing intuitive tools and interfaces that guide users through the layout and configuration process.
2. **Optimized system sizing**: With MgC, users can accurately size Rooftop Systems to maximize energy generation potential while ensuring optimal utilization of available rooftop space.
3. **Performance simulation**: Users can simulate the performance of Rooftop Systems using MgC's advanced modeling capabilities, gaining insights into energy generation, system efficiency, and potential savings.
4. **Economic viability analysis**: MgC facilitates economic viability analysis of Rooftop Systems by providing tools to assess costs, returns on investment, and payback periods, helping users make informed decisions about solar PV installations.
5. **Environmental impact assessment**: MgC enables users to evaluate the environmental impact of Rooftop Systems by analyzing carbon emissions reduction, renewable energy generation, and overall sustainability benefits.

By leveraging these features, MgC empowers users to model Rooftop Systems with confidence, ensuring efficient design, optimal performance, and positive environmental and economic outcomes.

{% hint style="info" %}
The following template guides through the public project's key aspects: objectives, resources, technologies, and loads for effective rooftop system project modeling.
{% endhint %}

{% tabs %}
{% tab title="Objective" %}
* Model a PV system including various resources, technologies, and loads to maintain stability in the energy supply.
{% endtab %}

{% tab title="Resources" %}
* Weather data
* Electricity from grid
{% endtab %}

{% tab title="Technologies" %}
* Solar PV panels
* Grid connection
{% endtab %}

{% tab title="Loads" %}
* Battery, electrical loads.
{% endtab %}
{% endtabs %}

**Step 1:** To get the benefits of the rooftop system in MgC, simply click on the "New Project" option available in the MgC interface.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.13.26 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 2:** Choose the project location, allowing MgC to access energy sources at the selected location like weather data for wind, solar, and other parameters.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.02.31 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 3:** To activate the rooftop PV system feature in MgC, select the "Rooftop System" in MgC, which includes pre-modeled resources, loads, and technologies. This option saves users time by already having elements built into the network.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 3.48.14 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 4:** In the second step of project specifications, users can configure the initial settings of system components like resources, loads, and technologies to tailor the solar rooftop system to specific requirements. This customization ensures that the microgrid system is optimized to meet the unique needs and goals of the project.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 2.13.11 PM.png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 2.13.16 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 5:** Now, determine the project goal by adjusting the slide bar towards saving CO2 emissions for a more eco-friendly project, which may result in higher CAPEX/OPEX, or vice versa. The project goal of achieving 25% of CAPEX/OPEX has been selected here.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 3.53.52 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 6:** Finally, click on the "Submit" button after providing the project name and details.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.03.27 PM (2).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 7:** After initializing the project, the user can view the performance indicators, and here the project details such as fixed CAPEX, OPEX, interest, and inflation rates can be changed according to the requirements.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 3.58.16 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 8:** The default hub at the selected location will be created automatically, and the user can add additional hubs by following the steps outlined in [hub creation and setup](../user-interface-ui-navigation/project-setup-and-simulation/hub-creation-and-setup.md).

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.00.23 PM.png" alt="" width="375"><figcaption></figcaption></figure>

MgC provides flexibility and time-saving benefits to the user by offering templates with required technologies and loads. Users can easily modify attributes of selected elements and add new elements or loads as needed.&#x20;

### Resources

In MgC's rooftop system feature, information from resources like weather data and grid electricity is accessed to ensure system stability. Excess energy generated in the hub can be stored in batteries for later use during periods of high demand. Below is the network flowsheet of the rooftop system, presented through MgC's rooftop feature.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.01.43 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Users can access comprehensive project details in the system design's details section, offering thorough information on the technical, environmental, and economic aspects of technologies, loads, and resources involved in the project as shown below.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.06.11 PM.png" alt="" width="375"><figcaption></figcaption></figure>

The features of the MgC can be explored more by clicking on the respective feature under the section "Advanced".

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.09.29 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### Weather data

The weather data is gathered automatically from the selected location by the MgC. The weather profile such as global horizontal radiation for solar energy, dry bulb temperature, and wind speed can be seen as shown in the below screenshot.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.11.58 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Statistical details for the weather data at the Stuttgart location can be seen in the resource ribbon under the "Advanced" feature in the MgC.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.13.58 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### Consumer electricity

MgC users have the flexibility to adjust costs, energy, and power parameters for consumer electricity simply by double-clicking on the respective parameters, allowing for easy customization at any time.&#x20;

Here in the below image, the increase in the base cost of consumer electricity tariff composition likely aims to stabilize the grid by encouraging more efficient energy use. Adjusting the equivalent GHG emissions for a rooftop system without additional technologies ensures accurate environmental impact assessment, supporting informed decision-making and sustainability goals.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 5.56.48 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### Feed-in tariff

Innovatively, users can swiftly customize feed-in tariff parameters like details and compositions with a simple double-click on the respective parameters, enhancing flexibility and efficiency.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.03.58 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### Technologies

In MgC's rooftop system template, PV panel capacities are automatically generated for electricity domains, streamlining setup. Users can customize parameters like capacity and costs by double-clicking and tailoring characteristics to project needs. This flexibility extends beyond PV modules, allowing the modeling of additional technologies and loads, optimizing project design and alignment with goals.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.05.56 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Additional specifications like technical, economic, and environmental parameters can be easily edited based on available or required data, as demonstrated below.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.07.10 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### Loads

In the rooftop system template, initially only building and battery loads are selected, but users can choose additional loads such as heating and cooling before simulating the project. Peak values for electrical, cooling, and heating loads can be adjusted by double-clicking on the relevant element. MgC seamlessly manages changes in load data in the sector coupling model, offering intuitive interfaces for parameter updates and advanced algorithms for resource allocation. This ensures optimal microgrid operation and resilience, making MgC essential for effective sector coupling modeling.

#### Timestep:&#x20;

The timestep determines how often the weather data updates and plots the kW values on the diagram over time. If the timestep is smaller, we get more frequent updates and a finer view of power changes. With a larger timestep, updates are less frequent, giving a broader view.

The electricity demand profile can be visualized in the timestep vs power graph, as depicted in the screenshot below. Demand is highest during the winter season and lowest in the summer months.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.25.27 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Statistical details and values distribution for electricity demand can be seen in the resource ribbon under the drop-down feature in the MgC. This applies to all loads such as batteries, building, cold, and heat storage, within the electricity, heating, and cooling domains.

**Project saving:** Saving a project in MgC is essential for preserving work progress. By clicking "Save," users securely store project data, ensuring easy retrieval and management.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.34.53 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Project simulation:** In MgC, the project simulation is initiated by selecting the "Simulate" option, enabling users to analyze and evaluate the performance of their microgrid design. This process provides valuable insights into system behavior and assists in making informed decisions for optimal operation and efficiency.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.36.48 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### Results

After simulation, MgC provides users with the results section, allowing for flexible exploration of various simulation outcomes. This feature offers detailed data analysis, empowering users to optimize energy management strategies effectively.

**Summary**

The project summary, accessible on the results section's summary page, provides a comprehensive overview of key project metrics such as installed capacities, CO2 emissions, operation time, and asset costs. This allows users to quickly understand and assess the project's performance and financial implications.

**Initialized capacities:** According to the project specifications, the hot water tank capacity is the highest, while the wind turbine capacity is the lowest among the installed capacities.

**CO\_2 emissions:** As per the project specification, rooftop PV significantly reduces emissions, while cold storage minimally reduces emissions. Heat pumps, heating rods, and hot water tanks contribute to moderate emissions reduction.

**Operation time:** The power grid connection and heat pump operation time is higher compared to the wind turbine, PV, chiller, and loads such as hot water tank, cold storage, and heating rod, which have lower operation times.

**Asset costs:** Rooftop PV incurs high CAPEX and OPEX costs, placing it at the top in terms of economic parameters. Heat pumps, chiller, and wind turbines have medium economic parameters, while cold storage and heating rod asset costs are comparatively lower than other elements in the project.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 7.41.04 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Energy mix**

In this section, users can analyze the distribution of energy production and demands within the microgrid, gaining insights into the balance between sources and demands. This helps in optimizing resource allocation and enhancing the sustainability of the microgrid system.

**Electricity generation:** Consumer electricity comprises 84% of the energy mix, indicating its substantial role in meeting demand, while rooftop PV contributes 16%, highlighting its growing importance in renewable energy integration.&#x20;

**Heat generation:** The heat pump generates approximately 99.6% of the heat, with the remaining heat generated by the heating rod.&#x20;

**Cold generation:** The chiller provides 100% of the cooling energy required to meet cooling demand.&#x20;

**Electricity demand:** Approximately 79% of the electricity demand is met by loads or buildings, with the wind turbine supplying the remaining 21% for its operation. This breakdown highlights the significant contribution of loads to electricity demand and the wind turbine's role in renewable energy generation.&#x20;

**Heat demand:** The hot water demand represents the highest at 77%, followed by space heating demand at 20%, with the hot water tank accounting for the least demand at 3%. This distribution underscores the importance of hot water supply within the microgrid.&#x20;

**Cold demand:** Building space cooling accounts for 99.4% of the total cooling demand, with the remaining allocated to cold storage. This breakdown highlights the primary role of building space cooling within the microgrid's cooling system.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 7.41.17 PM.png" alt="" width="375"><figcaption></figcaption></figure>

MgC offers users clear and intuitive visualizations of energy generation, demand, and system performance, aiding in informed decision-making. With MgC's real-time monitoring capabilities, users can track system performance and make timely adjustments for optimal efficiency. Its scenario analysis tools enable users to explore different configurations and strategies, ensuring cost-effective and sustainable solutions for microgrid management.

**Optimal operation graphs**

The parameters of the domains are displayed on the left (kW) and right (kWh) axes, with a set point ranging from -50 to +50 kW for each domain.

**Electricity domain**

The graph illustrates high electricity demand input into the sector coupling system during the winter season, decreasing in the summer months. Despite these fluctuations, the output from consumer electricity, wind turbines, and rooftop PV consistently meets this demand, ensuring system stability and preventing blackouts.&#x20;

This highlights MgC's significance in effectively managing energy supply and demand dynamics, optimizing resource utilization, and maintaining grid reliability throughout changing seasons and demand patterns.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 7.44.11 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Heating domain**

The graph below depicts the heating domain, with parameters represented. During the winter season, the hot water tank and space heating demand peak, while the output from the heat pump, space heating, and heating rod sufficiently meets this demand, contributing to grid stabilization.&#x20;

MgC's significance lies in its ability to accurately model and optimize the microgrid's heating system, ensuring reliable supply and demand balancing. By simulating various scenarios and optimizing system parameters, MgC empowers users to improve energy efficiency, reduce costs, and enhance overall system performance.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 7.44.18 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Cooling domain**

The graph below illustrates the cooling domain of the microgrid. Cooling demand peaks between May and September, coinciding with warmer temperatures, while the chiller output consistently meets this demand. The State of Charge (SOC) of the cold storage fluctuates between 0 and 20 kWh, indicating variations in stored cold energy over time. This fluctuation in SOC can be attributed to factors such as variations in cooling demand, chiller efficiency, and renewable energy availability.&#x20;

MgC's significance lies in its ability to accurately model and optimize the microgrid's cooling system, allowing users to efficiently manage energy resources, ensure reliable cooling supply, and optimize system performance.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 7.44.25 PM.png" alt="" width="375"><figcaption></figcaption></figure>

MgC simplifies energy project planning, providing clear financial insights and resource optimization. With its user-friendly tools, informed decisions are made, promoting cost-effectiveness and sustainability. MgC leads the way in efficient energy management, shaping a greener and more resilient future.

{% hint style="info" %}
MgC users can easily switch the visibility of graphs from duration curves to line charts by clicking on the icon located at the top left corner of each graph. This flexibility allows for instant customization of graph displays at any time during analysis.
{% endhint %}

MgC furnishes users with comprehensive project reports, which can be exported in MS Excel, or PDF format from the [results section.](../data-analysis-and-visualization/save-and-exporting-the-project.md)
