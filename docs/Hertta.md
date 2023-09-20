# Hertta

<p align="center" width="100%">
    <img width="33%" src="assets/Hertta_logo.svg"> 
</p>

# What is it?

# A short introduction to Hertta

# Know more


|                                                |      |      | Total Scoring                               | 90.5     | 85       | 82    | 68.5    | 65.5     | 62       | 59.5  | 57            | 50.5     |
| ---------------------------------------------- | ---- | ---- | ------------------------------------------- | -------- | -------- | ----- | ------- | -------- | -------- | ----- | ------------- | -------- |
| Function  class                                |      |      | Function                                    | Spineopt | Backbone | TIMES | DER-CAM | oSeMoSYS | Calliope | PyPSA | oemof (SoLPH) | Balmorel |
| objective  function                            |      |      | objective: Total system costs               | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | objective: Emissions                        | 🔴        | 1        | 0     | 1       | 0        | 1        | 0     | 1             | 0        |
|                                                |      |      | Weighted multi-objective  function          | 🔴        | 1        | 0     | 1       | 0        | 1        | 0     | 1             | 0        |
| Temporal  representation                       |      |      | Hourly operation time step                  | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Variable operation time step                | 1        | 1        | 1     | 0       | 1        | 1        | 0     | 1             | 1        |
|                                                |      |      | Fle1ible resolution over horizon            | 1        | 1        | 1     | 0       | 1        | 0        | 0     | 1             | 🔴        |
|                                                |      |      | Fle1ible resolution over sectors            | 1        | 0        | 0     | 0       | 0        | 0        | 0     | 0             | 🔴        |
|                                                |      |      | Fle1ible resolution over space              | 1        | 0        | 1     | 0       | 0        | 0        | 0     | 0             | 🔴        |
|                                                |      |      | Time series aggregation                     | 1        | 0.5      | 0     | 0       | 0        | 1        | 0     | 0             | 0.5      |
|                                                |      |      | Multi-stage investment                      | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 1        |
|                                                |      |      | Variable investment time step               | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 1        |
|                                                |      |      | Perfect foresight                           | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 🔴        |
|                                                |      |      | Myopic                                      | 1        | 1        | 1     | 0       | 0        | 0        | 0     | 0             | 1        |
| Technical  representation of      technologies |      |      | Technology agnostic                         | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 🔴        |
|                                                |      |      | Integer technology units                    | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Multiple inputs/outputs                     | 1        | 1        | 1     | 0.5     | 1        | 1        | 1     | 1             | 0.5      |
|                                                |      |      | Alternative modes of operation              | 0        | 1        | 1     | 0       | 1        | 1        | 0     | 0.5           | 0        |
|                                                |      |      | Fuel switching                              | 1        | 1        | 1     | 0       | 1        | 1        | 0     | 0             | 0        |
|                                                |      |      | Part-load efficiencies                      | 1        | 1        | 1     | 1       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Time-step dependent efficiency              | 1        | 1        | 1     | 1       | 0        | 1        | 1     | 1             | 0        |
|                                                |      |      | Technology derating                         | 1        | 1        | 1     | 1       | 0        |          | 1     | 0             | 1        |
|                                                |      |      | Ramp up/down constraints                    | 1        | 1        | 1     | 1       | 0        | 1        | 1     | 0             | 0        |
|                                                |      |      | Start-up/Shut-Down constraints              | 1        | 1        | 1     | 1       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Minimum operation level                     | 1        | 1        | 1     | 1       | 0        | 1        | 1     | 0             | 0        |
|                                                |      |      | Minimum up/down time or cyclic  constraints | 1        | 1        | 1     | 0       | 0        | 0        | 1     | 0             | 0        |
|                                                |      |      | Technology improvement                      | 0.5      | 0.5      | 1     | 0       | 0.5      | 0        | 0.5   | 0             | 0        |
|                                                |      |      | Technology degradation                      | 0        | 0        | 1     | 0       | 0        | 0        | 0     | 0             | 0        |
| Technical  representation of storage           |      |      | Storage                                     | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Storage agnostic                            | 1        | 1        | 1     | 0       | 1        | 1        | 1     | 1             | 0.5      |
|                                                |      |      | Integer storage units                       | 1        | 1        | 0     | 1       | 0        | 1        | 0     | 0             | 0        |
|                                                |      |      | Ma1 storage level                           | 1        | 1        | 0     | 0       | 1        | 0        | 0     | 1             | 1        |
|                                                |      |      | Discharge depth                             | 1        | 1        | 0     | 1       | 1        | 1        | 0     | 1             | 1        |
|                                                |      |      | Charge/Discharge rate                       | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Charge/Discharge efficiency                 | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Self-discharge                              | 1        | 1        | 1     | 1       | 0        | 1        | 1     | 1             | 0        |
|                                                |      |      | Energy/Power ratio                          | 0        | 0        | 1     | 0       | 0        | 1        | 0     | 1             | 1        |
|                                                |      |      | Ma1imum number of cycles over a  period     | 0        | 0        | 0     | 1       | 0        | 0        | 1     | 0             | 0        |
|                                                |      |      | Ma1imum number of cycles in life            | 0        | 0        | 1     | 0       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Storage degradation                         | 0        | 0        | 0     | 1       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Daily storage                               | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Seasonal storage                            | 1        | 0        | 1     | 0       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Thermal storage                             | 0        | 0        | 0     | 1       | 0        | 0        | 0     | 0             | 0.5      |
|                                                |      |      | Vehicle-to-grid                             | 0        | 0        | 0     | 1       | 0        | 0        | 1     | 0             | 0        |
| Technical  representation of networks          |      |      | Network connections                         | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Connection efficiency                       | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | oPF                                         | 0        | 0        | 0     | 0       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | DCoPF (LoPF)                                | 1        | 1        | 0.5   | 1       | 0        | 0        | 1     | 0             | 0        |
|                                                |      |      | SCoPF                                       | 1        | 0        | 0     | 0       | 0        | 0        | 1     | 0             | 0        |
|                                                |      |      | Thermal networks                            | 1        | 0.5      | 0     | 1       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Gas networks                                | 1        | 0        | 0.5   | 0       | 0        | 0        | 0     | 0             | 0        |
| Costs                                          |      |      | Variable operation costs                    | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Fi1ed costs                                 | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Investments costs                           | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Ramp-up/down costs                          | 1        | 1        | 1     | 0       | 1        | 0        | 0     | 0             | 0        |
|                                                |      |      | Start-up/Shut-Down costs                    | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 0        |
|                                                |      |      | Investment in storage capacity              | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Investment in storage power  capacity       | 1        | 1        | 0     | 1       | 0        | 0        | 1     | 1             | 0        |
|                                                |      |      | Storage operation costs                     | 1        | 1        | 1     | 1       | 0        | 1        | 1     | 0             | 0        |
|                                                |      |      | Network investment costs                    | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Network operation costs                     | 1        | 1        | 1     | 0       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Year-dependent variable  operation costs    | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 1        |
|                                                |      |      | Year-dependent fi1ed costs                  | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 0        |
|                                                |      |      | Year-dependent investment costs             | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 0        |
|                                                |      |      | Economy of scale                            | 0        | 0        | 0     | 0       | 0        | 0        | 0     | 1             | 0        |
|                                                |      |      | Emission penalty                            | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Year-dependent emission penalty             | 1        | 1        | 1     | 0       | 1        | 0        | 0     | 0             | 1        |
| Demand  and demand management                  |      |      | Electricity demand                          | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Heating demand                              | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Cooling demand                              | 1        | 1        | 1     | 1       | 1        | 1        | 0     | 1             | 0        |
|                                                |      |      | Transport demand                            | 1        | 1        | 1     | 0.5     | 1        | 1        | 1     | 1             | 0.5      |
|                                                |      |      | other demand                                | 1        | 1        | 1     | 0       | 1        | 1        | 0     | 1             | 0        |
|                                                |      |      | Year-dependent demand                       | 1        | 1        | 1     | 0       | 1        | 0        |       | 0             | 1        |
|                                                |      |      | Energy efficiency measures                  | 1        | 1        | 1     | 1       | 1        | 1        | 0     | 1             | 0        |
|                                                |      |      | Building retrofit                           | 0        | 0        | 0     | 0       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Load shedding                               | 0        | 1        |       | 1       | 0        | 0        | 0     | 1             | 0        |
|                                                |      |      | Load shifting                               | 0        | 0        | 1     | 1       | 0        | 0        | 0     | 1             | 0        |
| Electricity  sale/purchase tariffs             |      |      | Purchase - Simple tariff                    | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Purchase - Fi1ed charge tariff              | 1        | 1        | 1     | 1       | 1        | 1        | 0     | 1             | 0        |
|                                                |      |      | Puchase - Time of use tariff                | 1        | 1        | 1     | 1       | 0        | 1        | 0     | 1             | 0        |
|                                                |      |      | Purchase - Electricity tiers  tariff        | 0        | 0        | 0     | 1       | 0        | 0        | 0     | 0             | 0.5      |
|                                                |      |      | Purchase - Peak demand tariff               | 0        | 0        | 0     | 1       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Sale - Electricity sales                    | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Sale - Simple tariff                        | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Sale - Time of use tariff                   | 1        | 1        | 0     | 1       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Sale - Electricity tiers tariff             | 0        | 0        | 0     | 1       | 0        | 0        | 0     | 0             | 0.5      |
|                                                |      |      | Sale - E1port cap                           | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
| Targets  and constraints                       |      |      | Resource cap                                | 1        | 1        | 1     | 1       | 1        | 1        | 0     | 1             | 1        |
|                                                |      |      | Renewable target                            | 1        | 1        | 1     | 0       | 1        | 1        | 0     | 1             | 1        |
|                                                |      |      | Self generation                             | 0        | 1        | 0     | 1       | 0        | 1        | 0     | 0.5           | 1        |
|                                                |      |      | Emission cap                                | 1        | 1        | 1     | 1       | 1        | 0        | 1     | 1             | 1        |
|                                                |      |      | Year-dependent emission cap                 | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 1        |
|                                                |      |      | Land occupation                             | 0        | 0        | 0     | 1       | 0        | 1        | 0     | 0.5           | 0        |
|                                                |      |      | Budget constraints                          | 0        | 1        | 0     | 1       | 0        | 0        | 0     | 0             | 0        |
| Uncertainties                                  |      |      | Capacity margin                             | 0        | 1        | 1     | 1       | 1        | 1        | 0     | 0             | 1        |
|                                                |      |      | Modelling to generate  alternatives         | 1        | 0        | 0     | 0       | 0        | 1        | 0     | 0             | 0        |
|                                                |      |      | Stochastic programming                      | 1        | 1        | 1     | 0       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Monte Carlo analysis                        | 0        | 0        | 0     | 0       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Robust optimisation                         | 0        | 0        | 0     | 0       | 0        | 0        | 0     | 0             | 0        |
| other                                          |      |      | E1ogenous emissions                         | 0        | 0        | 0     | 0       | 1        | 0        | 0     | 0             | 0        |
|                                                |      |      | Early technology decommissioning            | 0        | 0        | 1     | 0       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Planned technology  decommissioning         | 1        | 1        | 1     | 0       | 1        | 0        | 1     | 0             | 1        |
|                                                |      |      | Planned capacity                            | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 0        |
|                                                |      |      | E1isting capacity                           | 1        | 1        | 1     | 1       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Year-dependent emission factor              | 1        | 0        | 1     | 0       | 1        | 0        | 0     | 0             | 0        |
| Advanced  operation                            |      |      | Unit commitment                             | 1        | 1        | 0.5   | 0       | 0        | 0        | 1     | 0             | 0.5      |
|                                                |      |      | Secondary reserves                          | 1        | 1        | 0.5   | 1       | 0        | 0        | 0     | 1             | 0.5      |
|                                                |      |      | Rolling Horizon - operation                 | 1        | 1        | 0     | 0       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Problem decomposition                       | 1        | 0        | 0     | 0       | 0        | 0        | 0     | 0             | 0        |
| Availability  and usability                    |      |      | open source                                 | 1        | 1        | 1     | 0       | 1        | 1        | 1     | 1             | 1        |
|                                                |      |      | Free of charge                              | 1        | 0        | 0     | 1       | 1        | 1        | 1     | 1             | 0        |
|                                                |      |      | GUI                                         | 1        | 1        | 1     | 1       | 1        | 0        | 0     | 0             | 1        |
|                                                |      |      | Load profile generation                     | 0        | 0        | 0     | 1       | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | GIS representation                          | 0        | 0        | 0     | 0       | 0        | 1        | 1     | 0             | 0        |
|                                                |      |      | GIS data                                    | 0        | 0        | 0     | 0.5     | 0        | 0        | 0     | 0             | 0        |
|                                                |      |      | Handle large number of scenarios            | 1        | 1        | 1     | 0       | 0        | 1        | 0     | 0             | 0        |
|                                                |      |      | Post-processing/Reporting                   | 1        | 0        | 1     | 1       | 1        | 1        | 1     | 0             | 1        |
|                                                |      |      | Documentation                               | 1        | 0.5      | 1     | 1       | 1        | 1        | 1     | 0.5           | 1        |
|                                                |      |      | E1amples and tutorials                      | 1        | 1        | 0     | 1       | 1        | 1        | 1     | 1             | 0        |
|                                                |      |      | Active forum                                | 1        | 1        | 1     | 0       | 1        | 1        | 1     | 1             | 0        |
|                                                |      |      | online courses                              | 1        | 0        | 1     | 1       | 1        | 0        | 0     | 0             | 0        |
