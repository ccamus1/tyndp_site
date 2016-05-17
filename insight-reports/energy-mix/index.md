---
layout: pages
title: "Viability of the energy mix"
bumf: >
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. A alias ea aspernatur eaque veniam. Saepe rerum dolorum numquam quisquam animi perferendis fuga! Adipisci molestiae dicta, enim molestias voluptatum et alias corrupti autem perspiciatis libero provident ea assumenda, fugiat recusandae reprehenderit excepturi dolorem. Nemo sint aut ex hic illo unde labore sed magnam itaque deserunt blanditiis, eum, magni laudantium aliquam assumenda, cumque, accusamus architecto provident nam earum eos mollitia laboriosam dolor! Totam numquam nam animi omnis.
nav_tier1_active: "insights"
nav-breadcrumbs:
  - Insight Reports: "/insight-reports"
  - Viability of the energy mix: "/insight-reports/energy-mix"
---

The energy mix represents the combination of different type of generation sources that are necessary to meet demand over a given period. Figure 1 shows the annual energy mix as considered in TYNDP16 for the pan-European system and the five synchronous areas in the mid-term best estimate scenario of “Expected Progress 2020 (EP2020)”.

![]({{ "/assets/img/energy-mix/fig1.png" | prepend: site.baseurl }})

__Figure 1 EP2020 Energy mix. Annual split in ENTSO-E and the five synchronous areas.__

At any given time, a set of generating units will be providing the power necessary to meet demand. Market decisions and eventual technical restrictions will largely determine this set of generating units, which will vary considerably throughout the year. 

The European energy targets for 2020-2030 establish the share of renewable energy in the electricity sector to increase to at least 45% in 2030. Having in mind this future RES integration and the highly changing market decisions one can expect, in all systems, an increased number of hours with very high RES percentage and many different generation patterns in terms of source type and location. All those situations bring specific technical and economic challenges, which must be analysed in order to find the most adequate and timely measures to manage system operation.

The hourly energy mix reveals the technical challenges faced by TSOs. The annual energy mix, on the other hand, reveals the economic challenges and the profitability risk that thermal plants might face due to the reduction of equivalent full load hours and of marginal electricity price.

The following chapters present an insight into some of those aspects looking at the long-term 2030 TYNDP visions.

## Technical challenges

From a wide system perspective, reduction of total system inertia, voltage management, widespread voltage dips and balancing generation and demand are relevant challenges resulting from high shares of RES integration.

Next table presents an overview of challenges associated with high RES and the mitigation actions identified:

<table>
    <thead>
        <tr>
            <th>Challenges</th>
            <th>Issues</th>
            <th>Mitigating actions</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Reduction of system inertia</td>
            <td>Total system inertia<br>ROCOF<br>Frequency containment</td>
            <td>
                <ul>
                    <li>Synthetic inertia and frequency containment provision</li>
                    <li>Securing large imbalances</li>
                    <li>Implementation of NCs</li>
                    <li>Synchronous compensators</li>
                    <li>Must run units</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Voltage</td>
            <td>Voltage control means<br>Voltage dips</td>
            <td><ul>
                <li>Investments on the network side: synchronous condensers, SVCs</li>
                <li>Implementation of NCs</li>
            </ul>
            </td>
        </tr>
        <tr>
            <td>System strength</td>
            <td>Fault level for converter stable operation<br>Fault current for protections</td>
            <td>
            <ul>
                <li>Implementation of NCs - fault current contribution of converter-based sources</li>
                <li>Expectable evolution of transmission system protection schemes towards more differential protections</li>
            </ul>
            </td>
        </tr>
        <tr>
            <td>Need for flexibility</td>
            <td>Balancing</td>
            <td>
            <ul>
                <li>System interconnections</li>
                <li>New flexibility sources at relevant timescales</li>
            </ul>
            </td>
        </tr>
    </tbody>
</table>


## Reduction of system inertia

### Background

The energy stored in the rotating masses of the synchronous generating units, by virtue of their inertia, provides means of instantaneously balancing any mismatch between the raw energy supplied to generating units and the total system demand including losses.

The immediate inertia action results in a change in rotor speeds and, consequently, the system frequency. These frequency excursions are monitored by frequency response providers who will vary the power output of their plants to restore the balance between generation and demand.

Whereas inertia itself does not solve the power mismatch problem in a sustainable manner, it is essential for instantaneously balancing this mismatch until frequency response is able to catch up. With very low inertia, the system would experience high frequency excursions and may even blackout as result of a minor mismatch between generation and demand.

The rate of change of frequency (ROCOF) is determined by the initial mismatch in power and the total system inertia at the time the mismatch took place. The higher the mismatch between load and generation and the less the inertia, the higher becomes ROCOF, i.e. the steeper the frequency gradient.

### Foreseen trends
Unlike conventional generation technologies, RES are not intrinsically capable of providing the same inertial response. This is either because they have no rotating masses or because the energy stored in the rotating masses is decoupled from the system by power electronic converters.

As the connected capacity of RES increases, and as their contribution to the energy mix increases, the total inertia of the system will be reduced for extended periods of hours.



__Figure 2__ presents the estimates of system inertia in the four 2030 visions for CE and GB synchronous areas. A set of assumptions was taken to make this estimates, hence values should be seen as an indication of the trend and of the range between maximum and minimum values.


![]({{ "/assets/img/energy-mix/fig2.1.png" | prepend: site.baseurl }})

![]({{ "/assets/img/energy-mix/fig2.2.png" | prepend: site.baseurl }})

__Figure 2 Percentage of hours in a full year where inertia is above a given value. Synchronous area inertia H[s] is calculated on the basis of total demand served by synchronous area generators. Examples of Continental Europe and Great Britain synchronous areas. TYNDP16 2030 Visions: V1 “Slowest Progress”; V2 “Constrained Progress”; V3 “National Green Transition”; V4 “European Green Revolution”__


Taking into account 2030 TYNDP market results, exemplified above for Continental Europe and Great Britain, system inertia reduces in all synchronous areas from Vision 1 “Slowest progress” (situation closest to today) to Vision 4 “Green revolution”. Even in Continental Europe, reduction of inertia is clearly noticeable in visions with a higher integration of RES. In Great Britain, where number of hours with very low inertia is higher, concerns due to reduced inertia have a larger impact.

In all cases, frequency sensitivity (ROCOF and frequency excursion) to generation-demand unbalance incidents is expected to increase.

Inertia is gaining time for the sustaining adaption of power infeed into the network which is given by the frequency containment means (‘Frequency Sensitivity Mode’ or ‘Limited Frequency Sensitivity Mode’) responding proportionally to the frequency deviation. If inertia is decreasing, less time is gained and as a result, the frequency containment reserves must be activated faster to avoid excessive frequency excursions.

###  Solution needs and mitigation measures
Different solutions and mitigation measures contribute to securing the power system performance.

- Frequency containment provision by other sources than synchronous generation: converter-connected generation, demand side response, storage and reserve shared between synchronous areas using HVDC.
- Implementation of the Connection Codes: critical to ensure that the necessary technical requirements related to synthetic inertia, frequency sensitive mode and robustness against high ROCOF are put in place. The capabilities required by the network codes provide solutions that should be understood in a holistic and balanced approach in terms of its implementation both at transmission and distribution level. 
- Limit the size of the largest imbalances: large imbalances will become increasingly more challenging to secure and is an issue with cross-border impact.
- Use synchronous compensators (SCs): even decoupling generators to become SCs under changing operating conditions in real time from generators such as GTs and CCGTs or permanently from decommissioned nuclear (Germany).
- Constraining RES and placing synchronous generation in the unit commitment: While synchronous generation at technical minimums provides inertia to the system, constraining RES might be a less efficient solution (maybe a short-term solution).

###  Voltage management
For highly meshed areas with an “optimal” distribution of synchronous generation units around the consumption areas, static limits, like thermal ratings and over/under voltage in substations have usually been the limiting factors.

The increase of penetration of electronic driven and controlled sources and penetration of decentralized generation combined with increased cross-border energy exchanges has been leading to new kind of voltage related issues.

<table>
<thead>
<tr><th>In case of:</th><th>Effects:</th><th>Consequences:</th></tr>
</thead>
<tbody>
<tr>
    <td>High RES infeed</td>
    <td>Less automatic reactive reserve in the system from synchronous units;<br>Reduced voltage support in case of short circuits</td>
    <td rowspan="3">
        The voltage restoration ability is reduced;<br>
        In case of short circuits, the affected area becomes larger.<br>
        The interdependency in voltage and short-circuit support among areas/TSOs is increased.<br>
        The uncertainty regarding power flow directions and the spread between low load and very high load put extra needs in voltage control;<br>
        Considering weaker voltage sources directly connected to the transmission system, maximum transmissible power will become more and more important and represent a cross-TSO issue.
    </td>
</tr>
<tr>
    <td>High penetration of decentralized generation</td>
    <td>Less automatic reactive reserve in the system from synchronous units;<br>Reduced voltage support in case of short circuits Active power flow across the transmission system is reduced; <br>Reactive power flow pattern exchanged with the transmission system changes</td>
</tr>
<tr>
    <td>High imports into a region</td>
    <td>Less automatic reactive reserve in the system from synchronous units;<br>Reduced voltage support in case of short circuits</td>
    <td></td>
</tr>
</tbody>
</table>

## Need for flexibility
High RES installed capacity and zero marginal costs of RES tend to displace conventional generator units from the market. Unlike conventional generators, RES has an intermittent and variable nature, cannot follow demand and is not completely predictable. Hence, RES deviations due to under or over supply, must be balanced in order to maintain the frequency equilibrium.

The following graphs show residual load ramps (load minus RES) for different scenarios and specific regions being either synchronous areas, or some so called electric peninsulas with limited interconnection capacity to other countries, Scenarios with high RES integration display strong ramps of available conventional generation and demonstrate the need for new flexibility sources.

<table>
<thead>
    <tr>
    <td>[MW/h]</td>
    <td>Iberian peninsula</td>
    <td>Nordics</td>
    <td>Baltics</td>
    <td>UK</td>
    <td>Italy</td>
</tr>
</thead>
<tbody>
    <tr>
        <th>EP2020</th><td>6120</td><td>4637</td><td>544</td><td>8830</td><td>8060</td>
    </tr>
    <tr><th>Vision 1</th><td>6893</td>
<td>4624</td>
<td>656</td>
<td>8201</td>
<td>8723</td>
</tr>
    <tr><th>Vision 2</th><td>9350</td>
<td>4326</td>
<td>572</td>
<td>10355</td>
<td>7438</td>
</tr>
    <tr><th>Vision 3</th><td>7387</td>
<td>4179</td>
<td>552</td>
<td>13788</td>
<td>9003</td>
</tr>
    <tr><th>Vision 4</th><td>14340</td>
<td>4366</td>
<td>584</td>
<td>10460</td>
<td>9429</td>
</tr>
</tbody>
</table>

![]({{ "/assets/img/energy-mix/ramps.png" | prepend: site.baseurl }})

### Solution needs and mitigation measures

Different mitigation options are necessary:

- System interconnections – Interconnection relieves strong ramping since deviations are balanced over a network covering a wider territory. In this case, intermittence, variability and predictability challenges of RES sources dilute, which in turn reduces uncertainty and flexibility needs.
- New flexibility sources at relevant timescales – Classical sources of flexibility (classical generation) are displaced due to RES. In order to cope with this situation new flexibility sources may enter into play both from the offer and demand side, e.g.: new roles for thermal plants, RES participation, demand side response, storage.

Mitigation options will be complementary. In a system highly interconnected, it is likely that flexibility needs disperse. Conversely, in a system with weaker interconnection flexibility needs will see increased procurement. Transmission projects may provide additional benefits in terms of flexibility means.

Investments to allow large power flows covering vast distances and flexibility rewards to providers will be central aspects to the solution.

## Additional perspectives on the generation mix
The development of generation and demand scenarios built for the TYNDP start with the definition of the storyline of each scenario through an extensive stakeholder involvement. The next steps include: assumptions, data collections, quality checks, pan-European methodologies, and final market simulations to quantify energy outputs.

The scenarios are built to be adequate which means sufficient generation is available in every hour of the year to cover the ENTSO-E electricity demand assuming normal conditions (weather, outages) take place. This characteristic is essential to ensure scenarios can be used for a sound Cost Benefit Analysis. However, questions have already been raised at the time of TYNDP 2014 on the risk for the profitability of the generation portfolio included in these scenarios. 

The increase of RES installed capacity puts out of the merit order the most expensive thermal generation technologies. Several technologies see their full-load hours going down, being replaced by RES-based electricity generation. The magnitude and generation technology impacted varies depending on the CO2 price assumed within each scenario. In addition, the number of hours with zero marginal cost increases from 2020 to 2030, correlated with a higher coverage of electricity production from RES with zero marginal cost.

These two aspects are shown on Figure 3 taking GB as an example with the marginal cost curves displayed for both 2020 and a 2030 scenario (Vision 3). Compared to 2020, the 2030 scenario sees an increase by around 30 GW of wind and solar installed capacity in GB combined with an increase of the CO2 price and electricity demand. Globally, the marginal cost curve is moved upward as well as shifted to the left, with a significant increase of the number of hours with zero marginal cost. This is a trend seen in most of the countries with see the same change of generation technologies.  

![]({{ "/assets/img/energy-mix/fig3.png" | prepend: site.baseurl }})

__Figure 3 Marginal cost duration curve in GB for 2020 and a high-RES 2030 scenario (Vision 3)__

![]({{ "/assets/img/energy-mix/fig4.png" | prepend: site.baseurl }})

__Figure 4 Number of hours with at least one zero-marginal cost country__

These figures open the question of the profitability of the energy mix assumed in the scenarios. It is worth noting the models currently used consider only the day-ahead market, but do not value the additional services provided by both generation and transmission assets (e.g. capacity contribution to SoS, flexibility..,). By comparing the revenues modelled in the tools for the complete generation portfolio investment cost, one finds the revenues are in the same order of magnitude than the investments costs. Considering as well the remuneration of the capital, the OPEX and other costs incurred, the revenues from the spot market tends not to be sufficient to cover the total investment costs. __(+ some figures)__

## Conclusions
The system is evolving in a complex manner and with increased cross-border interdependency hence, a systematic approach from the planning perspective in analysis including inertia, voltage and flexibility is advisable in order to ensure the correct measure of the emerging challenges and the maintenance of system security. This analysis should provide comparable results among the TSOs and could help to take timely and economical solutions or mitigation measures. TYNDP is an opportunity to bring that coordination together, provide objective assessments and highlight the most relevant challenges and solutions.

TYNDP 16 delivers the necessary transmission infrastructure but in order to make the energy mix viable it is essential to look at the future from a system perspective. The implementation of the Connection Codes to ensure the necessary technical requirements to grid users and the implementation of Europe’s electricity market to ensure aspects such as reward to system flexibility and incentives for market participants to act in line with system needs are also key priorities.
