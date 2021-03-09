# Valeo-AOI
ENS Data challenge competition for a Valeo subsidiary

This is a data challenge proposed by ENS Challenge data
https://challengedata.ens.fr/participants/challenges/58/

The goal of this challenge was to confirm the presence of defects on parts based on pictures taken during
production in a Valeo plant in France.
During module assembly, an Automatic Optical Inspection (AOI) is done after a wire bonding process
to check the conformity and the quality of the parts. This inspection is based on pictures taken by camera
and basic algorithms used to measure some specific parameters on the parts. The AOI machine is efficient 
to measure dimensions on the parts (width of bonding wire for example) but much less for aspect
defects. This difficulty to properly analyze this type of defect leads to a large number of parts that must
be confirmed manually by operators. In certain conditions, the rate of false defect (parts
considered KO by machine but OK by operator) could reach 10 or 20% of the production.

The target of this challenge was to define a model that could provide a better result than AOI 
to discriminate between good and bad parts for aspect defects. 

For this analysis, I implemented a deep learning model using VGG-16 algorithm.
