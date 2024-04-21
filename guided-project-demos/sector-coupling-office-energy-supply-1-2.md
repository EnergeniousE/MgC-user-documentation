---
cover: ../.gitbook/assets/Rooftop.jpeg
coverY: 80
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Rooftop system

**Concept:**

It refers to the design and implementation of solar panels on building rooftops to generate electricity from sunlight. By harnessing solar power directly from rooftops, this approach helps to reduce reliance on traditional energy sources, lower electricity bills, and contribute to a more sustainable and environmentally friendly energy system.

**MgC's capability in "Rooftop system" modeling:**

MgC stands out in the rooftop system by offering a unified platform for designing and managing integrated energy systems. Its functionalities encompass:

1. **Effortless design**: MgC simplifies the process of designing "Rooftop Systems" by providing intuitive tools and interfaces that guide users through the layout and configuration process.
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
Model a PV system including various resources, technologies, and loads to maintain stability in the energy supply.
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

<details>

<summary><strong>Template selection</strong></summary>

**Step 1:** To get the benefits of the rooftop system in MgC, simply click on the "New Project" option available in the MgC interface.

<img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.13.26 PM (1).png" alt="" data-size="original">

**Step 2:** Choose the project location, allowing MgC to access energy sources at the selected location like weather data for wind, solar, and other parameters.

<img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.02.31 PM (1).png" alt="" data-size="original">

**Step 3:** To activate the rooftop PV system feature in MgC, select the "Rooftop System" in MgC, which includes pre-modeled resources, loads, and technologies. This option saves users time by already having elements built into the network.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 3.48.14 PM.png" alt="" data-size="original">

**Step 4:** In the second step of project specifications, users can configure the initial settings of system components like resources, loads, and technologies to tailor the solar rooftop system to specific requirements. This customization ensures that the microgrid system is optimized to meet the unique needs and goals of the project.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 2.13.11 PM.png" alt="" data-size="original"><img src="../.gitbook/assets/Screenshot 2024-02-18 at 2.13.16 PM.png" alt="" data-size="original">

**Step 5:** Now, determine the project goal by adjusting the slide bar towards saving $$CO_{2}$$emissions for a more eco-friendly project, which may result in higher CAPEX/OPEX, or vice versa. The project goal of achieving 25% of CAPEX/OPEX has been selected here.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 3.53.52 PM.png" alt="" data-size="original">

**Step 6:** Finally, click on the "Submit" button after providing the project name and details.

<img src="../.gitbook/assets/Screenshot 2024-02-04 at 4.03.27 PM (2).png" alt="" data-size="original">

**Step 7:** After initializing the project, the user can view the performance indicators, and here the project details such as fixed CAPEX, OPEX, interest, and inflation rates can be changed according to the requirements.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 3.58.16 PM.png" alt="" data-size="original">

**Step 8:** The default hub at the selected location will be created automatically, and the user can add additional hubs by following the steps outlined in [hub creation and setup](../user-interface-ui-navigation/project-setup-and-simulation/hub-creation-and-setup.md).

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.00.23 PM.png" alt="" data-size="original">

MgC provides flexibility and time-saving benefits to the user by offering templates with required technologies and loads. Users can easily modify attributes of selected elements and add new elements or loads as needed.

</details>

<details>

<summary><strong>Resources</strong></summary>

MgC's rooftop system feature ensures network stability by utilizing weather data and grid electricity. Excess energy is stored in batteries for later use during high-demand periods. The network flowsheet that is shown below is accessible through MgC's rooftop feature.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.01.43 PM.png" alt="" data-size="original">

Users can access comprehensive project details in the system design's details section, offering thorough information on the technical, environmental, and economic aspects of technologies, loads, and resources involved in the project as shown below.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.06.11 PM.png" alt="" data-size="original">

The features of the MgC can be explored more by clicking on the respective feature under the section "Advanced".

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.09.29 PM.png" alt="" data-size="original">

**Weather data:** The weather data is gathered automatically from the selected location by the MgC. The weather profile such as global horizontal radiation for solar energy, dry bulb temperature, and wind speed can be seen as shown in the below screenshot.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.11.58 PM.png" alt="" data-size="original">

Statistical details for the weather data at the selected location can be seen in the resource ribbon under the "Advanced" feature in the MgC.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 4.13.58 PM.png" alt="" data-size="original">

**Consumer electricity:** MgC users have the flexibility to adjust costs, energy, and power parameters for consumer electricity simply by double-clicking on the respective parameters, allowing for easy customization at any time.

In the below image, the rise in the base cost of consumer electricity tariff composition aims to stabilize the grid by promoting more efficient energy use. Adjusting equivalent GHG emissions for a rooftop system without extra technologies ensures precise environmental impact assessment, aiding informed decision-making and sustainability objectives.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 5.56.48 PM.png" alt="" data-size="original">

**Feed-in-tariff:** Innovatively, users can swiftly customize feed-in tariff parameters like details and compositions with a simple double-click on the respective parameters, enhancing flexibility and efficiency.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.03.58 PM.png" alt="" data-size="original">

</details>

<details>

<summary><strong>Technologies</strong></summary>

In MgC's rooftop system template, PV panel capacities are automatically generated for electricity domains, streamlining setup. Users can customize parameters like capacity and costs by double-clicking and tailoring characteristics to project needs. This flexibility extends beyond PV modules, allowing the modeling of additional technologies and loads, optimizing project design and alignment with goals.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.05.56 PM.png" alt="" data-size="original">

Additional specifications like technical, economic, and environmental parameters can be easily edited based on available or required data, as demonstrated below.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.07.10 PM.png" alt="" data-size="original">

</details>

<details>

<summary><strong>Loads</strong></summary>

In the rooftop system template, initially only building and battery loads are selected, but users can choose additional loads such as heating and cooling before simulating the project. Peak values for electrical, cooling, and heating loads can be adjusted by double-clicking on the relevant element.&#x20;

MgC seamlessly manages changes in load data in the sector coupling model, offering intuitive interfaces for parameter updates and advanced algorithms for resource allocation. This ensures optimal microgrid operation and resilience, making MgC essential for effective sector coupling modeling.

**Timestep:** The timestep determines how often the weather data updates and plots the kW values on the diagram over time. If the timestep is smaller, we get more frequent updates and a finer view of power changes. With a larger timestep, updates are less frequent, giving a broader view.

The electricity demand profile can be visualized in the timestep vs power graph, as depicted in the screenshot below. One can observe that demand is highest during the winter season and lowest in the summer months.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.25.27 PM.png" alt="" data-size="original">

Statistical details and values distribution for electricity demand can be seen in the resource ribbon under the drop-down feature in the MgC. This applies to all loads such as batteries, building, cold, and heat storage, within the electricity, heating, and cooling domains.

</details>

<details>

<summary><strong>Project saving and simulation</strong></summary>

**Project saving:** Saving a project in MgC is essential for preserving work progress. By clicking "Save," users securely store project data, ensuring easy retrieval and management.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.34.53 PM.png" alt="" data-size="original">

**Project simulation:** In MgC, the project simulation is initiated by selecting the "Simulate" option, enabling users to analyze and evaluate the performance of their microgrid design. This process provides valuable insights into system behavior and assists in making informed decisions for optimal operation and efficiency.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.36.48 PM.png" alt="" data-size="original">

</details>

<details>

<summary><strong>Results</strong></summary>

Following simulation, MgC presents users with a results section for flexible exploration of simulation outcomes. This feature facilitates detailed data analysis, empowering users to optimize energy management strategies effectively.

**Summary**

&#x20;Accessible within the results section's summary page, the project summary in MgC offers a comprehensive overview of key metrics including installed capacities, $$CO_{2}$$ emissions, operation time, and asset costs. This enables users to swiftly grasp the project's performance and financial implications.

**Installed capacities:** As per the project specifications, the grid connection capacity is highest at approximately 68 kW, while the capacity of PV modules is lowest at 30 kW among installed capacities. This aligns with the expectation that PV generation occurs primarily during daylight hours.

$$CO_{2}$$**emissions:** In line with project specifications, rooftop PV substantially cuts emissions by about 0.7 tonnes, making a meaningful impact on reducing the overall environmental footprint.

**Operation time:** The power grid connection maintains a longer operational time, approximately 8300 hours, compared to PV, which operates for about 4900 hours. This difference stems from the grid's continuous availability, contrasting with PV's reliance on daylight hours for generation.

**Asset costs:** Rooftop PV incurs high CAPEX 3000 € and OPEX 2000 € costs, positioning it as the top economic parameter due to its initial installation expenses and ongoing operational costs associated with maintenance and electricity generation.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.39.18 PM.png" alt="" data-size="original">

**Energy mix**

Within this section, users can examine how energy production and demand are distributed within the "Rooftop System," gaining valuable insights into the balance between sources and requirements. This analysis aids in optimizing resource allocation and strengthening the sustainability of the microgrid system.

**Electricity generation:** Consumer electricity comprises 84% of the energy mix, indicating its substantial role in meeting demand, while rooftop PV contributes 16%, highlighting its growing importance in renewable energy integration.

**Electricity demand:** The electricity demand solely originates from the building loads, accounting for 100% of the overall demand within the system.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.39.59 PM.png" alt="" data-size="original">

MgC offers users clear and intuitive energy visualizations, aiding decision-making. Real-time monitoring allows for timely adjustments, while scenario analysis tools ensure cost-effective, sustainable microgrid solutions.

**Optimal operation graphs**

The parameters of the domains are displayed on the left (kW) and right (kWh) axes, with a set point ranging from -50 to +50 kW for each domain.

**Electricity domain**

The graph illustrates variations in building demand throughout seasons, peaking in winter and decreasing in summer. Despite these fluctuations, both consumer electricity and Standard PV module outputs consistently meet demand, ensuring system stability and mitigating blackout risks.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.41.58 PM.png" alt="" data-size="original">

This highlights MgC's significance in effectively managing energy supply and demand dynamics, optimizing resource utilization, and maintaining grid reliability throughout changing seasons and demand patterns.

Visualization of heating and cooling domain loads data is accessible upon modeling specific loads and generation technologies within their respective domains.

**Cost analysis**

The project lifetime vs expenses graph typically depicts high CAPEX and OPEX during the initial period, consistent with standard project financing trends. NPV, or net present value, represents the present value of all cash inflows and outflows over the project's lifetime, adjusted for the time value of money.

<img src="../.gitbook/assets/Screenshot 2024-02-18 at 6.45.08 PM.png" alt="" data-size="original">

Users can adjust the discount rate above the graph to reflect changes in project financing conditions, influencing NPV calculations accordingly.

</details>

{% hint style="info" %}
MgC users can swiftly toggle between duration curves and line charts by clicking the icon located at the top left corner of each graph, providing instant customization options during analysis.
{% endhint %}

MgC furnishes users with comprehensive project reports, which can be exported in MS Excel of specific data, or PDF format from the [results section.](../data-analysis-and-visualization/save-and-exporting-the-project.md)
