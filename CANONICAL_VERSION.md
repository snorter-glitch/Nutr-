# Nutrition Evidence Engine — canonical v7.2

Canonical artifact: `NUTRITION_ENGINE_CANONICAL_v7.2.zip`

SHA256: `e19ff96d6145c695d9eecc94b2b1ef1d319261952f6c4d0435c8acb558a9f8bc`
ZIP entries: 197
ZIP integrity: clean (`testzip = None`)

Canonical design decisions:
- One physiology profile per person; physiological targets do not change when the user moves between Spain and Russia.
- Spain and Russia affect food-composition sources, labels, fortification, product availability, laboratory reference context, and regulations—not the person's physiology.
- Quantitative nutrition core covers energy/calories, protein, fat, carbohydrates, fibre, free sugars, saturated fat, salt/sodium, hydration, fruit/vegetable pattern, and uncertainty/weekly averages.
- Micronutrient engine covers vitamins A, B-group, C, D, E, K; calcium, iron, magnesium, zinc, iodine, selenium, copper, manganese, phosphorus, potassium, sodium, choline and omega-3.
- Food-first gap solving; supplements only after indication, dose, safety/UL, interactions and marginal value.
- Cooking engine supports low-effort, no-cook, microwave, air-fryer, oven, one-pan, one-pot, batch/freezer and fridge-to-meal routes.
- Additional v7.2 coverage includes PCOS/lactation/thyroid interactions, advanced sports nutrition, lab interpretation, GLP-1 nutrition, meal timing/chrononutrition, sweeteners, microbiome/probiotics, hunger/satiety/cravings, food-drug interactions and broader supplement/functional-food evaluation.
- Russian-first UX, minimal unnecessary questioning, verdict-first, no food morality, no false precision.

This file is the version pointer. Do not silently modify the canonical v7.2 package; create a new version instead.
