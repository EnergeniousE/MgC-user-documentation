---
cover: ../.gitbook/assets/240_F_245393308_vuswgMmxuPQASLIJtPkLKgZNQrs7TXQE.jpg
coverY: 0
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

# Electric vehicle

**Concept:**

Microgrid networks integrate EVs as dynamic energy assets. They serve as both energy consumers and mobile storage units, charging during off-peak hours and discharging during peak demand. This feature optimizes energy usage, enhances grid stability, and facilitates the integration of renewable energy sources.

**MgC's capability in "Electric vehicle network" modeling:**

The EV Integration module within the MgC facilitates the seamless incorporation of EVs into microgrid networks. Leveraging EVs as flexible energy assets, users can optimize grid stability and energy usage patterns. By harnessing the potential of EVs, users can enhance the sustainability and efficiency of their microgrid systems using MgC.

1. **EV characteristics modeling**: Users can input detailed specifications of electric vehicles, including battery capacity, charging efficiency, and vehicle usage patterns.
2. **Simulation and analysis**: Users can simulate EV behavior within the microgrid network and analyze the results to evaluate different scenarios, assess performance metrics, and refine EV deployment strategies.
3. **Integration with renewable energy sources**: MgC integrates EV modeling with renewable energy sources such as solar and wind power, enabling users to leverage EV batteries for storing and utilizing renewable energy effectively.

{% hint style="info" %}
The following template guides through the public project's key aspects: objectives, resources, technologies, and loads for effective project modeling with electric vehicle elements.
{% endhint %}

{% tabs %}
{% tab title="Objective" %}
* Model an electric vehicle network including various resources, technologies, and loads to maintain stability in the grid.
* In the base scenario, a typical office and a factory-specific production demand need to be covered. Electricity from the grid is available with a flat tariff.&#x20;
* Two EVs are part of the company's car fleet and a charging station is to be installed at the premises. The factory operators are interested in optimizing their energy supply.
{% endtab %}

{% tab title="Resources" %}
* Weather data
* Electricity from grid
{% endtab %}

{% tab title="Loads" %}
* Production load
* EV 1 driving day
* EV 2 driving day
{% endtab %}

{% tab title="Technologies" %}
* Charging stations
* Electric vehicles
* Electrical loads
{% endtab %}
{% endtabs %}

<details>

<summary>Project setup</summary>

Follow the steps outlined in the [User interface navigation](../user-interface-ui-navigation/creating-a-project.md) to establish the project setup.

Proceed with the instructions provided within the user interface to configure the initial settings and parameters for the EV project. This typically involves navigating through various screens or menus to define project objectives, specify input data, and set preferences according to user requirements.&#x20;

</details>

<details>

<summary>Resources</summary>

In MgC's EV feature, information from resources like weather data(origin: here EPW) and consumer electricity is accessed to ensure system stability. The energy generated in the hub will be stored in batteries for EVs. Below is the network flowsheet of the EV system, presented through MgC.

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 6.39.30 PM.png" alt="" data-size="original">

Users can access comprehensive project details under the MgC ribbon "System design-details" section, offering thorough information on the technical, environmental (such as GHG emissions), and economic aspects (like base, operational, etc costs), as well as details on technologies, loads, and resources involved in the project.

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 6.40.12 PM.png" alt="" data-size="original">

To further explore MgC features, users can access them by clicking within the "Advanced" section.

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 6.40.35 PM.png" alt="" data-size="original">

**Weather data-** MgC automatically collects weather data like dry bulb temperature, wind speed, etc from the selected location.&#x20;

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 6.40.47 PM.png" alt="" data-size="original">

Detailed weather statistics can be found in the 'Advanced' section of the resource ribbon as explained in the previous projects.&#x20;

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 8.22.08 PM.png" alt="" data-size="original">

**Consumer electricity-** MgC users have the flexibility to adjust costs, energy, and power parameters for consumer electricity simply by double-clicking on the respective parameters, allowing for easy customization at any time as shown in the below image.

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 8.23.31 PM.png" alt="" data-size="original">

</details>

<details>

<summary>Technologies</summary>

For this project, essential technologies include electric grids, electric vehicles, and charging stations to achieve its objectives. The image below provides an overview of the technologies utilized in this project.

<img src="../.gitbook/assets/Screenshot 2024-04-07 at 8.09.54 PM.png" alt="" data-size="original">

For example EV 2 in the below image, technical, economic, and environmental specifications can be edited by double-clicking on the parameters. A round-trip efficiency of 81% is set as a realistic value, adjustable to project specifications. Investment costs include €9000 fixed and €340/kWh variable costs for CAPEX, while OPEX incurs a variable cost of €6.8/a/kWh aligning with the project's financial and operational requirements.

<img src="../.gitbook/assets/Screenshot 2024-04-07 at 8.14.23 PM.png" alt="" data-size="original">

To adjust the specifications of technologies, loads, and resources, users can follow the same procedure by double-clicking on the parameter. This ensures that MgC's flexibility and customization are in line with the project's specific requirements.

</details>

<details>

<summary>Loads</summary>

**Load setup-** To create loads according to the required quantity, simply click on "New Instance" as depicted in the image below.

<img src="../.gitbook/assets/Screenshot 2024-04-07 at 9.21.43 PM.png" alt="" data-size="original">

Next, provide the name of the element, such as "EV 2 driving day," and select the data source for the loads from the "office demand" library. Then, click on either the "Add Element" or "Add Element and Edit" option, as illustrated in the MgC interface.

<img src="../.gitbook/assets/Screenshot 2024-04-07 at 9.03.01 PM.png" alt="" data-size="original">

The current project includes 1 production load and 2 EV driving day loads requiring charging. Users can view all loads in the project at any time by accessing the loads section under the advanced ribbon in MgC.

<img src="../.gitbook/assets/Screenshot 2024-04-07 at 9.04.41 PM.png" alt="" data-size="original">

**Time domain-** The timestep, or interval between updates, influences how often weather data is refreshed and kW values are plotted over time. Smaller timesteps lead to more frequent updates, offering a detailed view of power changes. Conversely, larger timesteps result in less frequent updates, providing a broader perspective.

<img src="../.gitbook/assets/Screenshot 2024-04-07 at 8.57.34 PM.png" alt="" data-size="original">

The electricity demand profile can be visualized in the timestep vs power graph, as depicted in the screenshot below. One can observe that demand is highest during the winter season and lowest in the summer months.

**Value distribution**

Within MgC, users can benefit from accessing the value distribution feature to observe the profile distribution and yearly pattern of loads. This provides valuable insights into load behavior, showcasing the frequency of load values (kW) at different moments and variations throughout the year. By understanding these distributions, users can effectively plan energy management strategies and optimize resource utilization within their projects.

<img src="../.gitbook/assets/Screenshot 2024-04-07 at 8.49.46 PM.png" alt="" data-size="original">

</details>

<details>

<summary>Project saving and simulation</summary>

**Notifications?:** MgC notifies users to save the project when changes are made. In the image, one warning notification prompts the user to save the project. This feature helps users avoid losing any modifications or updates made to their project.

<img src="../.gitbook/assets/Screenshot 2024-04-21 at 7.50.04 PM.png" alt="" data-size="original">

**Project saving:** Saving a project in MgC is essential for preserving work progress. By clicking "Save," users securely store project data, ensuring easy retrieval and management.

<img src="../.gitbook/assets/Screenshot 2024-04-21 at 7.50.16 PM.png" alt="" data-size="original">

**Simulation:** In MgC, the project simulation is initiated by selecting the "Simulate" option, enabling users to analyze and evaluate the performance of their microgrid design. This process provides valuable insights into system behavior and assists in making informed decisions for optimal operation and efficiency.

</details>

<details>

<summary>Project results</summary>



</details>
