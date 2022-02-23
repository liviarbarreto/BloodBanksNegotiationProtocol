### Instances
Repository containing the instances that were considered in the paper "***A MIXED-INTEGER LINEAR PROGRAMMING APPROACH TO SUPPORT BLOOD PRODUCTS NEGOTIATION***" by *Barreto, Livia Rodrigues Barreto*; *do Carmo, Breno Barros Telles*; *Fontes, Fábio Francisco da Costa*; *Costa, Luciano Carlos Azevedo*.

The generated instances represent three scenarios: ***state***, considering the blood banks in the state of Rio Grande do Norte/Brazil (RN); ***regional***, taking into account the blood banks in the nine states of the Brazilian Northeast region (NE); and ***national***, including the blood banks throughout Brazil (BR).

Each instance is named according to the scenario it represents. Hence, we have three instances groups: *RN-X*, *NE-X*, *BR-X*, where *X* represents the number of products considered in the instance.

Each instance file  is organized as follows:

- O: Matrix of supplies of blood product k at blood bank i 
- PO: Penalty two-dimensional vector associated with the offer of each blood product k (related to the expiration date) at blood bank i
- D: Matrix of demand for blood product k at blood bank j 
- PD: Penalty two-dimensional vector associated with the demand of each blood product k (related to stock level criticality) at blood bank j
- Z: Two-dimensional vector that is a function of the distance between the origin and destination 
