# Hertta

<p align="center" width="100%">
    <img width="33%" src="assets/Hertta_logo.svg"> 
</p>

# What is it?

# A short introduction to Hertta

# Know more
|                                                | Total Scoring                                     | 90.5     | 85       | 82    | 68.5    | 65.5     | 62       | 59.5  | 57            | 50.5     |
| ---------------------------------------------- | ------------------------------------------------- | -------- | -------- | ----- | ------- | -------- | -------- | ----- | ------------- | -------- |
| Function<br>class                              | Function                                          | Spineopt | Backbone | TIMES | DER-CAM | oSeMoSYS | Calliope | PyPSA | oemof (SoLPH) | Balmorel |
| objective<br>function                          | Total system costs                                | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Emissions                                         | 🔴        | 🟢        | 🔴     | 🟢       | 🔴        | 🟢        | 🔴     | 🟢             | 🔴        |
|                                                | Weighted <br>multi-objective<br>function          | 🔴        | 🟢        | 🔴     | 🟢       | 🔴        | 🟢        | 🔴     | 🟢             | 🔴        |
| Temporal<br>representation                     | Hourly operation <br>time step                    | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Variable operation <br>time step                  | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🔴     | 🟢             | 🟢        |
|                                                | Flexible resolution <br>over horizon              | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🔴     | 🟢             | 🔴        |
|                                                | Flexible resolution <br>over sectors              | 🟢        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Flexible resolution <br>over space                | 🟢        | 🔴        | 🟢     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Time series <br>aggregation                       | 🟢        | 🟡        | 🔴     | 🔴       | 🔴        | 🟢        | 🔴     | 🔴             | 🟡        |
|                                                | Multi-stage <br>investment                        | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🟢        |
|                                                | Variable investment <br>time step                 | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🟢        |
|                                                | Perfect foresight                                 | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | Myopic                                            | 🟢        | 🟢        | 🟢     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🟢        |
| Technical<br>representation of<br>technologies | Technology agnostic                               | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🔴        |
|                                                | Integer technology <br>units                      | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Multiple <br>inputs/outputs                       | 🟢        | 🟢        | 🟢     | 🟡       | 🟢        | 🟢        | 🟢     | 🟢             | 🟡        |
|                                                | Alternative modes <br>of operation                | 🔴        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🔴     | 🟡             | 🔴        |
|                                                | Fuel switching                                    | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🔴     | 🔴             | 🔴        |
|                                                | Part-load efficiencies                            | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Time-step dependent <br>efficiency                | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🟢        | 🟢     | 🟢             | 🔴        |
|                                                | Technology derating                               | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        |          | 🟢     | 🔴             | 🟢        |
|                                                | Ramp up/down <br>constraints                      | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🟢        | 🟢     | 🔴             | 🔴        |
|                                                | Start-up/Shut-Down <br>constraints                | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Minimum operation <br>level                       | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🟢        | 🟢     | 🔴             | 🔴        |
|                                                | Minimum up/down <br>time or cyclic<br>constraints | 🟢        | 🟢        | 🟢     | 🔴       | 🔴        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | Technology improvement                            | 🟡        | 🟡        | 🟢     | 🔴       | 🟡        | 🔴        | 🟡     | 🔴             | 🔴        |
|                                                | Technology degradation                            | 🔴        | 🔴        | 🟢     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
| Technical<br>representation<br>of storage      | Storage                                           | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Storage agnostic                                  | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🟢     | 🟢             | 🟡        |
|                                                | Integer storage units                             | 🟢        | 🟢        | 🔴     | 🟢       | 🔴        | 🟢        | 🔴     | 🔴             | 🔴        |
|                                                | Max storage level                                 | 🟢        | 🟢        | 🔴     | 🔴       | 🟢        | 🔴        | 🔴     | 🟢             | 🟢        |
|                                                | Discharge depth                                   | 🟢        | 🟢        | 🔴     | 🟢       | 🟢        | 🟢        | 🔴     | 🟢             | 🟢        |
|                                                | Charge/Discharge rate                             | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Charge/Discharge <br>efficiency                   | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Self-discharge                                    | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🟢        | 🟢     | 🟢             | 🔴        |
|                                                | Energy/Power ratio                                | 🔴        | 🔴        | 🟢     | 🔴       | 🔴        | 🟢        | 🔴     | 🟢             | 🟢        |
|                                                | Maximum number of <br>cycles over a  period       | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | Maximum number of <br>cycles in life              | 🔴        | 🔴        | 🟢     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Storage degradation                               | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Daily storage                                     | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Seasonal storage                                  | 🟢        | 🔴        | 🟢     | 🔴       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Thermal storage                                   | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🟡        |
|                                                | Vehicle-to-grid                                   | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🟢     | 🔴             | 🔴        |
| Technical  <br>representation <br>of networks  | Network connections                               | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Connection efficiency                             | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | oPF                                               | 🔴        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | DCoPF (LoPF)                                      | 🟢        | 🟢        | 🟡     | 🟢       | 🔴        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | SCoPF                                             | 🟢        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | Thermal networks                                  | 🟢        | 🟡        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Gas networks                                      | 🟢        | 🔴        | 🟡     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
| Costs                                          | Variable <br>operation costs                      | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Fixed costs                                       | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Investments costs                                 | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Ramp-up/down costs                                | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Start-up/Shut-Down <br>costs                      | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | Investment in <br>storage capacity                | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Investment in <br>storage power<br>capacity       | 🟢        | 🟢        | 🔴     | 🟢       | 🔴        | 🔴        | 🟢     | 🟢             | 🔴        |
|                                                | Storage operation<br>costs                        | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🟢        | 🟢     | 🔴             | 🔴        |
|                                                | Network investment<br>costs                       | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Network operation<br>costs                        | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Year-dependent <br>variable<br>operation costs    | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🟢        |
|                                                | Year-dependent <br>fixed costs                    | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | Year-dependent <br>investment costs               | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🔴        |
|                                                | Economy of scale                                  | 🔴        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🟢             | 🔴        |
|                                                | Emission penalty                                  | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Year-dependent <br>emission penalty               | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🔴     | 🔴             | 🟢        |
| Demand  <br>and demand <br>management          | Electricity demand                                | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Heating demand                                    | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Cooling demand                                    | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🔴     | 🟢             | 🔴        |
|                                                | Transport demand                                  | 🟢        | 🟢        | 🟢     | 🟡       | 🟢        | 🟢        | 🟢     | 🟢             | 🟡        |
|                                                | other demand                                      | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🔴     | 🟢             | 🔴        |
|                                                | Year-dependent <br>demand                         | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        |       | 🔴             | 🟢        |
|                                                | Energy efficiency <br>measures                    | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🔴     | 🟢             | 🔴        |
|                                                | Building retrofit                                 | 🔴        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Load shedding                                     | 🔴        | 🟢        |       | 🟢       | 🔴        | 🔴        | 🔴     | 🟢             | 🔴        |
|                                                | Load shifting                                     | 🔴        | 🔴        | 🟢     | 🟢       | 🔴        | 🔴        | 🔴     | 🟢             | 🔴        |
| Electricity  <br>sale/purchase <br>tariffs     | Simple tariff                                     | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
| Purchase                                       | Fixed charge tariff                               | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🔴     | 🟢             | 🔴        |
| Purchase                                       | Time of use tariff                                | 🟢        | 🟢        | 🟢     | 🟢       | 🔴        | 🟢        | 🔴     | 🟢             | 🔴        |
| Purchase                                       | Electricity tiers<br>tariff                       | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🟡        |
| Purchase                                       | Peak demand tariff                                | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
| Sale                                           | Electricity sales                                 | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Simple tariff                                     | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Time of use tariff                                | 🟢        | 🟢        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Electricity tiers <br>tariff                      | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🟡        |
|                                                | Export cap                                        | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
| Targets and <br>constraints                    | Resource cap                                      | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🔴     | 🟢             | 🟢        |
|                                                | Renewable target                                  | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🔴     | 🟢             | 🟢        |
|                                                | Self generation                                   | 🔴        | 🟢        | 🔴     | 🟢       | 🔴        | 🟢        | 🔴     | 🟡             | 🟢        |
|                                                | Emission cap                                      | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🔴        | 🟢     | 🟢             | 🟢        |
|                                                | Year-dependent <br>emission cap                   | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🟢        |
|                                                | Land occupation                                   | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🟢        | 🔴     | 🟡             | 🔴        |
|                                                | Budget constraints                                | 🔴        | 🟢        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
| Uncertainties                                  | Capacity margin                                   | 🔴        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🔴     | 🔴             | 🟢        |
|                                                | Modelling to <br>generate alternatives            | 🟢        | 🔴        | 🔴     | 🔴       | 🔴        | 🟢        | 🔴     | 🔴             | 🔴        |
|                                                | Stochastic programming                            | 🟢        | 🟢        | 🟢     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Monte Carlo analysis                              | 🔴        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Robust optimisation                               | 🔴        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
| other                                          | Exogenous emissions                               | 🔴        | 🔴        | 🔴     | 🔴       | 🟢        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Early technology <br>decommissioning              | 🔴        | 🔴        | 🟢     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Planned technology<br>decommissioning             | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🔴        | 🟢     | 🔴             | 🟢        |
|                                                | Planned capacity                                  | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🔴        |
|                                                | Existing capacity                                 | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Year-dependent <br>emission factor                | 🟢        | 🔴        | 🟢     | 🔴       | 🟢        | 🔴        | 🔴     | 🔴             | 🔴        |
| Advanced  operation                            | Unit commitment                                   | 🟢        | 🟢        | 🟡     | 🔴       | 🔴        | 🔴        | 🟢     | 🔴             | 🟡        |
|                                                | Secondary reserves                                | 🟢        | 🟢        | 🟡     | 🟢       | 🔴        | 🔴        | 🔴     | 🟢             | 🟡        |
|                                                | Rolling Horizon<br>operation                      | 🟢        | 🟢        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Problem decomposition                             | 🟢        | 🔴        | 🔴     | 🔴       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
| Availability <br>and usability                 | open source                                       | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🟢     | 🟢             | 🟢        |
|                                                | Free of charge                                    | 🟢        | 🔴        | 🔴     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🔴        |
|                                                | GUI                                               | 🟢        | 🟢        | 🟢     | 🟢       | 🟢        | 🔴        | 🔴     | 🔴             | 🟢        |
|                                                | Load profile <br>generation                       | 🔴        | 🔴        | 🔴     | 🟢       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | GIS representation                                | 🔴        | 🔴        | 🔴     | 🔴       | 🔴        | 🟢        | 🟢     | 🔴             | 🔴        |
|                                                | GIS data                                          | 🔴        | 🔴        | 🔴     | 🟡       | 🔴        | 🔴        | 🔴     | 🔴             | 🔴        |
|                                                | Handle large <br>number of scenarios              | 🟢        | 🟢        | 🟢     | 🔴       | 🔴        | 🟢        | 🔴     | 🔴             | 🔴        |
|                                                | Post-processing<br>/Reporting                     | 🟢        | 🔴        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🔴             | 🟢        |
|                                                | Documentation                                     | 🟢        | 🟡        | 🟢     | 🟢       | 🟢        | 🟢        | 🟢     | 🟡             | 🟢        |
|                                                | Examples and<br>tutorials                         | 🟢        | 🟢        | 🔴     | 🟢       | 🟢        | 🟢        | 🟢     | 🟢             | 🔴        |
|                                                | Active forum                                      | 🟢        | 🟢        | 🟢     | 🔴       | 🟢        | 🟢        | 🟢     | 🟢             | 🔴        |
|                                                | online courses                                    | 🟢        | 🔴        | 🟢     | 🟢       | 🟢        | 🔴        | 🔴     | 🔴             | 🔴        |
