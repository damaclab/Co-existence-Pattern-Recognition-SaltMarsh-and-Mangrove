# Co-existence-Pattern-Recognition-SaltMarsh-and-Mangrove

This repository contains framework of an excessive salinity-affected mangrove community restoration approach where hypersalinity could be neutralized by growing suitable saltmarshes.

• Case study on Sundarban coastal area considering major environmental/habitat factors, such as salinity, pH, soil texture, tidal amplitude, along with the
occurrence data of mangroves, mangrove associates, and salt marshes and compile 3 different datasets for inner, middle, and outer estuarine species records.

• Establishing
– salt mash-salt marsh co-existence pattern along the salinity gradient
– salt marshes, mangroves, and mangrove associates co-existence patterns with varying environmental factors
– probable inter-species association from present co-existence data

Authors: Moumita Ghosh, Kartick Chandra Mondal, Anirban Roy

## Table of Contents

- [Introduction](#Introduction)
- [System Prerequisites](#Prerequisites)
- [Installation](#Installation)
- [Data Description](#DataDescription)
- [Association Rule Filtering](#AssociationRuleFiltering)
- [References](#References)

## Introduction
Climate-change driven sea level rise causes a increase in salinity in coastal wetlands accelerating the alteration of the species composition. It triggers the gradual extinction of species, particularly the mangrove population which is intolerant
of excessive salinity. Thus despite being crucial to a wide range of ecosystem services, mangroves have been identified
as a vulnerable coastal biome. Hence restoration strategy of mangroves is undergoing rigorous research and experiments
in literature at an interdisciplinary level. From a data-driven perspective, analysis of mangrove occurrence data could
be the key to comprehend and predict mangrove behavior along different environmental parameters, and it could be
important in formulating management strategy for mangrove rehabilitation and restoration. As salt marshes are the
natural salt-accumulating halophytes, mitigating excessive salinity could be achieved by incorporating salt-marshes in
mangrove restoration activities. This study intends to find a novel restoration strategy by assessing the frequent co-
existence status of salt marshes, with the mangroves, and mangrove associates in different zones of degraded mangrove
patches for species-rich plantation. To achieve this, we primarily design a novel methodological framework for the
practice of knowledge discovery concerning the coexistence pattern of salt marshes, mangroves, and mangrove associates
along with environmental parameters using a data mining paradigm of association rule mining. The proposed approach
has the capability to uncover underlying facts and forecast likely facts that could automate the study in the field of
ecological research to comprehend the occurrence of inter-species relationships. Our findings are based on published data
gathered on the Sundarban Mangrove Forest, one of the world’s most important littoral forests. The existing literature
reinforces the findings that include all the sets of frequently co-occurring mangroves, their associates, and salt marshes
along the salinity gradient of coastal Sundarbans. A detailed understanding of the occurrence patterns of all these, along
with the environmental variables, would be able to promote decision-making strategy. This framework is effective for
both academia and stakeholders, especially the foresters/ conservation planners, to regulate the spread of salt marshes
and the restoration of mangroves as well

## Datasets description

The occurrence records of 11 salt marshes along all the blocks are summarized in \textit{BSM} (dataset of blocks versus salt marshes), where the rows represent the 22 blocks and the columns represent the 11 salt marshes.
Besides the salt marsh records, three more datasets have been generated for inner, middle, and outer estuarine blocks \cite{danda2017state}.
These three datasets are denoted as OEBM, MEBM, and IEBM (dataset of outer estuarine blocks, middle estuarine blocks, and, inner estuarine blocks, respectively) where each of these contains the presence record of the estuary-specific distinct salt marshes, mangroves, and mangrove associates data, and other environmental parameters (such as salinity, pH, soil texture, and tidal amplitude) across the columns.
The rows represent the identified blocks for the outer, middle, and inner estuarine regions.
The list of salt marshes, mangroves, and mangrove associates, that have been considered in this study, are listed in Table \ref{table:mangrovelist}.

