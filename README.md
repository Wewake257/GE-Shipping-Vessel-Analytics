# GE Shipping Commercial Voyage Economics & Fleet Analytics

## Overview
Institutional commercial maritime analytics modeling fleet operations, voyage TCE (Time Charter Equivalent) economics, and bunker fuel consumption across dynamic port networks.

## Architecture & Data Assets
- **Fact_Fleet_Operations.csv**: Granular vessel movements, nautical mileage, speed knots, and cargo metric tons.
- **commercial_voyage_economics_data.csv**: Daily bunker fuel burn, gross revenue, net voyage margin, and demurrage calculations.
- **essel_financial_model_output.csv**: TCE return rate per deadweight tonnage across vessel classes (Aframax, Suezmax, Capesize).
- **Dim_Vessel.csv & Dim_Port.csv**: Dimensional hierarchy mapping port coordinates, draft limits, and fleet specifications.

## Key Performance Indicators
- **TCE Daily Return**: $\text{TCE} = \frac{\text{Gross Freight} - \text{Voyage Costs}}{\text{Duration (Days)}}$
- **Bunker Fuel Efficiency**: Metric tons consumed per nautical mile at service speed vs laden speed.
- **Port Turnaround Latency**: Demurrage exposure and berthing turnaround time.
