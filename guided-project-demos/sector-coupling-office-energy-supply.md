# Sector coupling-office energy supply

**Sector coupling concept:**

Sector coupling refers to the integration and coordination of different energy sectors, such as electricity, heating, and transportation, to enhance overall efficiency and sustainability. The aim is to create synergies between traditionally isolated sectors, allowing them to interact and complement each other. For instance, surplus electricity generated from renewable sources can be used to produce heat or power electric vehicles, contributing to a more integrated and flexible energy system.

**MgC's capability in sector coupling:**

MgC excels in facilitating sector coupling by providing a unified platform for the design and management of integrated energy systems. Its capabilities include:

1. **Multi-sector integration:** MgC allows users to model and optimize the integration of various energy sectors, enabling a holistic approach to energy management.
2. **Renewable energy integration:** MgC supports the efficient integration of renewable energy sources, ensuring that surplus energy can be intelligently utilized across different sectors.
3. **Load balancing:** MgC's capabilities extend to optimizing energy distribution and balancing loads between sectors to enhance overall efficiency and minimize waste.
4. **Scenario modeling:** Users can simulate different sector coupling scenarios within MgC, allowing for thorough analysis and decision-making based on specific project goals and requirements.
5. **Flexibility and adaptability:** MgC's flexibility enables users to adapt and tailor sector coupling configurations based on evolving energy needs and technological advancements.

By harnessing these capabilities, MgC empowers users to design and implement sector-coupled systems that contribute to a more sustainable and interconnected energy landscape.

{% hint style="info" %}
The following template guides through the public project's key aspects: objectives, resources, technologies, and loads for effective sector coupling project modeling.
{% endhint %}

{% tabs %}
{% tab title="Objective" %}
* Design a comprehensive energy supply system for a modern office in Berlin.
* Model a sector coupling energy system including various resources, technologies, and loads to maintain stability in the energy supply.
{% endtab %}

{% tab title="Resources" %}
* Weather data
* Natural gas
* Fuel
* Electricity from grid
{% endtab %}

{% tab title="Technologies" %}
* Solar PV panels
* Wind turbines
* Grid connection
* CHP(combined heat and power)
* Boiler
* Heat pump
* Electric heater
* Compression chiller
{% endtab %}

{% tab title="Loads" %}
* Battery, electrical loads.
* Heat storage, heat loads.
* Cold storage, cold loads.
{% endtab %}
{% endtabs %}

**Step 1:** To start a new project in MgC, simply click on the "New Project" option available in the software interface.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.13.26 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 2:** Choose the project location, allowing MgC to access energy sources like weather data for wind, solar, and other parameters.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.02.31 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 3:** To activate the sector coupling feature in MgC, select the pre-modeled sector coupling-office model, which includes pre-modeled resources, loads, and technologies. This option saves users time by already having elements built into the network.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.02.37 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 4:** In the second step of project specifications, users can configure the initial settings of system components like resources, loads, and technologies to tailor the sector coupling to specific requirements. This customization ensures that the microgrid system is optimized to meet the unique needs and goals of the project.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 2.13.11 PM.png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2024-02-18 at 2.13.16 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 5:** Now, determine the project goal by adjusting the slide bar towards saving CO2 emissions for a more eco-friendly project, which may result in higher CAPEX/OPEX, or vice versa. The project goal of achieving a 75% reduction in emissions has been selected here.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.03.01 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 6:** Finally, click on the "Submit" button after providing the project name and details.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.03.27 PM (2).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 7:** After initializing the project, the user can view the performance indicators, and here the project details such as fixed CAPEX, OPEX, interest, and inflation rates can be changed by the user.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.52.01 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 8:** The default hub at the selected location will be created automatically, and the user can add additional hubs by following the steps outlined in [hub creation and setup](../user-interface-ui-navigation/project-setup-and-simulation/hub-creation-and-setup.md).

<div data-full-width="true">

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.54.15 PM.png" alt="" width="375"><figcaption></figcaption></figure>

</div>

MgC provides flexibility and time-saving benefits to the user by offering templates with required technologies and loads. Users can easily modify attributes of selected elements and add new elements or loads as needed.&#x20;

### Resources

In MgC's sector coupling feature, data from resources such as weather data, natural gas, oil, and grid electricity are utilized to maintain stability. If excess energy is produced in the hub, it can be exported, allowing users to benefit from feed-in tariffs.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.55.29 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

The features of the MgC can be explored more by clicking on the respective feature under the ribbon advanced.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.03.40 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### Weather data

The weather data is gathered automatically from the selected location by the use of the MgC. The weather profile such as global horizontal radiation for solar energy, dry bulb temperature, and wind speed can be seen as shown in the below screenshot.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.42.14 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Statistical details for the weather data can be seen in the resource ribbon under the advanced feature in the MgC.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.21.31 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

#### Consumer electricity

MgC users can adjust the details and composition of costs, energy, and power parameters for consumer electricity by double-clicking on the respective parameters at any time, offering flexibility.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.03.55 PM.png" alt="" width="563"><figcaption></figcaption></figure>

#### Natural gas

Different from conventional methods, MgC users can effortlessly adjust natural gas' technical, tariff, details, compositions, and environmental parameters by simply double-clicking on the respective parameters.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.04.04 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### Diesel

In MgC, users can easily adjust diesel's technical specs, tariffs, details, compositions, and environmental parameters with a simple double-click.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.04.13 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### Feed-in tariff

Innovatively, users can adjust feed-in tariff parameters like details and compositions with a simple double-click on the respective parameters whenever needed.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.04.20 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### Technologies

Under the sector coupling template, resource capacities for PV panels, wind turbines, CHP, heating rods, boilers, heat pumps, and chillers in the electricity, heating, and cooling domains are automatically generated. Users simply need to select the appropriate data, such as capacity, asset lifetime, investment, operational costs, and technical, economic, and environmental parameters by double-clicking on the respective parameter.

Users can edit the basic parameters of technologies, like capacity and lifetime, as well as financial figures such as feed-in tariff, investment, and operational costs, by double-clicking on the specific parameter. By editing these basic parameters, users can tailor the characteristics of technologies to suit their project requirements. Adjusting parameters such as capacity, lifetime, feed-in tariff, investment, and operational costs enables users to fine-tune the project design, optimize financial planning, and align with specific project goals efficiently.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 7.00.52 PM.png" alt="" width="375"><figcaption></figcaption></figure>

The additional specifications such as technical, economic, and environmental parameters can be edited according to the data available or required and can be seen as shown below.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 7.08.13 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

### Loads

In the sector coupling template, all loads except for EV vehicles and charging stations are initially unselected but can be chosen by the user at any point before simulating the project. Users can set electrical, cooling, and heating peak values in kW for loads by selecting the relevant element and double-clicking on the parameter as demonstrated below.&#x20;

MgC efficiently handles changes in load data within the sector coupling model by providing intuitive interfaces for updating parameters and employing sophisticated algorithms for dynamic resource allocation. This ensures optimal operation and resilience of the microgrid, making MgC indispensable for effective sector coupling modeling.

#### Timestep:&#x20;

The timestep determines how often the weather data updates and plots the kW values on the diagram over time. If the timestep is smaller, we get more frequent updates and a finer view of power changes. With a larger timestep, updates are less frequent, giving a broader view.

The electricity demand profile for the timestep vs power can be visualized in the timestep vs power as shown in the below screenshot.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 5.58.44 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Statistical details and values distribution for electricity demand can be seen in the resource ribbon under the drop-down feature in the MgC. This applies to all loads such as batteries, building, cold, and heat storage, within the electricity, heating, and cooling domains.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-11 at 6.06.10 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**Project saving:** Saving a project in MgC is essential for preserving work progress. By clicking "Save," users securely store project data, ensuring easy retrieval and management.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 5.01.28 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

**Project simulation:** In MgC, the project simulation is initiated by selecting the "Simulate" option, enabling users to analyze and evaluate the performance of their microgrid design. This process provides valuable insights into system behavior and assists in making informed decisions for optimal operation and efficiency.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-04 at 5.01.39 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

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
