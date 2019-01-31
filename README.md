# ContentConfigurations
This repository contains various different configurations for the SIW project. The configuration files in the repository are strictly configuration for content that is displayed to the user on SIW and has no baring on how things are deployed or run in the production env.

## Claim configuration
This section handles the configuration for the claims. This file provides a mapping between the claim number and code and a label.

## Core Standards Configuration
This file handles the mapping between different information and the standards. This file allows SIW to map standards to different grands and subjects as well as provide a description for each standard.

## InteractionType Configurations
This section Handles the information needed for each interaction type. This maps the interaction types to names and labels.

## Installation To SIW
As mentioned above this project is used to configure information for SIW. As such it is installed on the SIW project as part of the project set up. This is done by installing this repository as a submodule.
```
> git submodule init
> git submodule update
```