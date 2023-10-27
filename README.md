# SharkMeatConsumption

This is for the code and data for the global shark meat consumption project


dag {
bb="0,0,1,1"
consumption [outcome,pos="0.440,0.407"]
culinary_traditions [exposure,pos="0.774,0.435"]
eating_habits [pos="0.691,0.343"]
fish_availability [pos="0.545,0.213"]
health_beliefs [pos="0.585,0.491"]
livelihood [pos="0.259,0.242"]
marketing [pos="0.675,0.672"]
measurement_error [pos="0.349,0.584"]
measurement_process [pos="0.213,0.669"]
mislabelling [pos="0.349,0.192"]
preparation [pos="0.241,0.348"]
price_perception [pos="0.456,0.622"]
religious_traditions [pos="0.748,0.187"]
self_efficacy [pos="0.301,0.476"]
sensory_perception [pos="0.453,0.146"]
culinary_traditions -> consumption
culinary_traditions -> eating_habits
eating_habits -> consumption
fish_availability -> consumption
fish_availability -> self_efficacy
health_beliefs -> consumption
livelihood -> consumption
marketing -> consumption
marketing -> eating_habits
marketing -> health_beliefs
measurement_error -> consumption
measurement_process -> measurement_error
mislabelling -> consumption
preparation -> consumption
preparation -> self_efficacy
price_perception -> consumption
religious_traditions -> consumption
religious_traditions -> culinary_traditions
self_efficacy -> consumption
sensory_perception -> consumption
}
