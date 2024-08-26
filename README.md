# A repository of reference genome-scale metabolic models of marine microbes


__Reconstruction of GEMs from core models__

e.g. Synechococcus,

1. Start with generic model with minimal imports
2. Obtain set of imports from MAG
3. Add import reactions and required pathways to utilized imported compounds if not present in generic model
4. Add imports/exports required for the model to work (e.g. minerals, etc.)