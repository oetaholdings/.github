# About Oeta Holdings
Oeta Holdings is a fictional entity used to demonstrate technology solutions in a near real world context.

## Vision
The vision of Oeta Holdings is three fold:

1. To contain a reproducable DEMO environment
2. Provide consultants with a SANDBOX enviroment
3. Incorporate a safe DEV space to implement solutions for Oeta

## Components
### DEMO Environment
The demo environment is intended to house readily available, IaC controlled demonstrations of Azure capabilities.

Intedended to be usable by sales pods and consultant to quickly learn about our delivered best-practice capabilities and show case working solutions.

Capabilities within the environment are quickly reproduceable via Infrastructure as Code (IaC) pipelines as content and service showcases drift from source-control.

This environment is tightly controlled with limited to no real direct owner/contributor access unless required for demo purposes.

### Sandbox Environment
The sandbox enviroment's purpose is to be the play area/learning area for consultants.  These environments could be destroyed as needed.  Not all implemented capabilities may be in source control, so beware if workloads here should be 'preserved' you must either IaC resources/configuration, or determine an alternate way to preserve the environment.

Baseline sandbox environments can be independent or based on the as-built demo environment.

### Dev Environment
The dev environment's purpose is to develop code, demonstrable features, or other assets that are under development for eventual inclusion in the demo environment.

Code/assets created here may include greenfield or PRs to be merged into master branches of demo environment repos.

