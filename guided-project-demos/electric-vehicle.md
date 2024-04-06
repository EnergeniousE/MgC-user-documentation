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

**Weather data**

MgC automatically collects weather data from the selected location.&#x20;

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 6.40.47 PM.png" alt="" data-size="original">

Detailed weather statistics can be found in the 'Advanced' section of the resource ribbon as explained in the previous projects.&#x20;

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 8.22.08 PM.png" alt="" data-size="original">

**Consumer electricity-** MgC users have the flexibility to adjust costs, energy, and power parameters for consumer electricity simply by double-clicking on the respective parameters, allowing for easy customization at any time as shown in the below image.

<img src="../.gitbook/assets/Screenshot 2024-04-06 at 8.23.31 PM.png" alt="" data-size="original">

</details>

<details>

<summary>Technologies</summary>



</details>

<details>

<summary>Loads</summary>



</details>

<details>

<summary>Project saving and simulation</summary>



</details>

<details>

<summary>Project results</summary>



</details>
