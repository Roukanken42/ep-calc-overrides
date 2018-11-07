# ep-calc-overrides
Overrides of parsed data for EM Enhancement calc

Full jsons can be found [here](https://essentialmana.com/enchancement-calc/talents_full/): 

Overriding is simple: key must be talent id (can either find it in jsons, or from url when you click on it on webpage) and then the object must be whatever you want to override - see other overrides made.
Eg, most overrides will look:

    "{id}" : {
        "name": "{name}",
        "tooltip": "{tooltip}"
    }
    
Overrides must be **valid JSON !** Run them trough https://jsonlint.com/ if not sure ! (Notably: can't be `,` after last parameter but before `}`)

Note that `{value1}` trough `{value4}` strings in tooltips get replaced with actual values from the levels of the talent, 
you can change these if you want, but be completly sure you're changing the values to be more correct.
