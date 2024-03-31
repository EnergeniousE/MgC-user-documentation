---
description: >-
  Sensitivity analysis assesses how input variable changes impact model or
  system output, aiding in decision-making and reliability assessment.
---

# Sensitivity analysis

In MgC, users have the flexibility to conduct sensitivity analysis for their projects by accessing the project list from the dropdown menu in the bottom-left corner of the application. By selecting "Show All" or specific projects, they can initiate sensitivity analysis. This empowers users with the ability to assess how various parameters impact their projects, enhancing their decision-making capabilities.

<figure><img src="../.gitbook/assets/2023-11-04 18_59_41-MgC.png" alt="" width="279"><figcaption></figcaption></figure>

Upon selecting the desired project, duplicating it for project modification or sensitivity analysis becomes a simple task. Just click on the **"Duplicate"** button, easily visible in the interface. Confirm the duplication by selecting "OK" in the ensuing pop-up window, streamlining the process and enabling you to make the necessary adjustments or conduct sensitivity analysis effortlessly.

<figure><img src="../.gitbook/assets/2023-11-04 19_00_46-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

To edit the required parameter, select a domain from the advanced features panel. For instance, adjust the consumer electricity price to perform "**sensitivity analysis".** This functionality offers flexibility and empowers users to customize project parameters for data-driven decision-making and project optimization.

<figure><img src="../.gitbook/assets/2023-11-04 19_01_54-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

In the past, the base cost for the consumer electricity tariff stood at 100 €/a. Modifying this cost is a straightforward process: just double-click on the base cost value and enter the desired assumed value. This user-friendly interface offers efficient control over project variables and parameter adjustments.

<figure><img src="../.gitbook/assets/2023-11-04 19_02_19-Window.png" alt="" width="375"><figcaption></figcaption></figure>

To perform sensitivity analysis, **adjust the selling price** to stakeholders from 0.05 to 0.4 €/kWh. This step empowers the users to gain insights into the project's **financial dynamics and optimize outcomes**.&#x20;

<figure><img src="../.gitbook/assets/2023-11-04 19_03_58-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/2023-11-04 19_04_33-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

Users can precisely **adjust parameters** for loads, technologies, and resources, including [investment and operation costs, installed capacities, and asset lifetime](../glossary/definitions.md#reference-for-kpi-formulas). This control empowers users to customize key project aspects for optimal performance and financial efficiency.&#x20;

<figure><img src="../.gitbook/assets/2023-11-04 19_05_26-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

MgC allows the users to **evaluate the project's overall impact** by changing the investment cost of components such as standard PV modules from 200 to 1800 €/kWp. This precise adjustment provides valuable insights into how it influences the project's financial and operational aspects, aiding data-driven decision-making and optimization.

<figure><img src="../.gitbook/assets/2023-11-04 19_05_49-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

Users can **alter technical, economic, and environmental specifications** for components within technologies, loads, and resources by duplicating the project. For instance, change the standard PV panel's fixed cost from 1000 to 2000 € and OPEX from 60 to 90 €/a/kWp. This precise modification empowers MgC users to perform detailed analysis and data-driven decision-making for the project at any time.

<figure><img src="../.gitbook/assets/2023-11-04 19_06_45-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

Similarly, **environmental parameters** such as variable [GHG emissions](../glossary/definitions.md#reference-for-kpi-formulas) can be adjusted to analyze the project's sensitivity to this parameter. This dynamic feature provides users with a deeper understanding of the [Key Performance Indicators](key-performance-indicators-kpi-s.md), enabling more informed decision-making and a holistic view of project performance. With MgC's capabilities, users gain a valuable tool for exploring project dynamics and optimizing its environmental impact and sustainability.&#x20;

<figure><img src="../.gitbook/assets/2023-11-04 19_07_42-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

Upon completing the project modifications and entering parameters for the duplicated project, MgC will initiate a fresh project simulation upon selecting the **"Submit"** button. This streamlined procedure facilitates an updated evaluation of the entire system, providing users with the opportunity to assess the project's performance innovatively and efficiently.

<figure><img src="../.gitbook/assets/2023-11-04 19_08_01-MgC.png" alt="" width="375"><figcaption></figcaption></figure>

This presents an overview of the system both before and following the simulation of the project with the necessary adjustments.

<figure><img src="../.gitbook/assets/image (3).png" alt="" width="375"><figcaption><p>System overview before sensitivity analysis</p></figcaption></figure>

<figure><img src="../.gitbook/assets/2023-11-04 19_16_44-Scenario 2 - output report.png" alt="" width="375"><figcaption><p>System overview after sensitivity analysis</p></figcaption></figure>

**Key changes observed from the MgCs Sensitivity analysis**

* Notably, investment costs saw a significant increase, rising from 38k€ to 56k€.
* The total grid export experienced a substantial drop, now standing at approximately 4 MWh, whereas it was 42.6 MWh previously.
* This transformation showcases MgC's exceptional capability, as its intelligent solver efficiently computed investment costs and emissions based on project inputs.
* As the investment costs rose, there was a noticeable decrease in the renewable share, emphasizing the [solver's](../modeling-and-optimization/milp-mathematical-modeling.md) role in optimizing system efficiency and sustainability.&#x20;

These dynamic changes highlight MgC's effectiveness in adapting to project modifications and delivering insightful results.
