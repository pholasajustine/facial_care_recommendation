<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project - Facial care recommendation : 
Justine PHOL-ASA

*[Data analytics PT, Paris & 26/07/2021 - 14/08/2021]*

## Summary
- [Context](#context)
- [Content](#content)
- [Links](#links)

<a name="context"></a>

## Context

In 2005, an Envoyé Spécial documentary denounced the use of certain components in conventional cosmetics (the famous “parabens”). It was from this moment that a large part of consumers began to wonder about cosmetic ingredients and the impact they could have on their health. I am part of this population who would like to use products that have a minimum impact on my health while being effective and at reasonable prices.
Since then, many brands display products with claims on the composition of their products: "Without endocrine disruptors", "Without parabens", "Without allergens", etc. However, these claims often have no rigorous definition or are too general. Carefully checking the list of ingredients is ultimately the safest way to learn about the product and identify the ingredients you want to avoid. However, it's a bit complicated when you're not a chemist and moreover the list of ingredients to avoid is growing longer each year and it's hard to keep in mind each ingredient to be avoided. This project aims to map cosmetic items based on their ingredients similarities and giving content-based filtering recommendation taking into account harmful chemicals and price. 

<a name="content"></a>

## Content

The dataset used was web-scrapped from beaute-test.com, a website where more than 50,000 products are referenced. It was combined with another dataset which was web-scrapped fom incibeauty.com. It is to date the most complete platform to decipher the cosmetic ingredients used in cosmetics.
The incibeauty dataset has 13004 rows and 4 columns (the name of the ingredient, the link to it, its harmfulness, its functions).
The beautetest dataset has 10 585 rows and 14 columns.
[Codebook](https://docs.google.com/spreadsheets/d/1bzCd4d_5kn-yGemK4vH3AGz4vBzbZecii_6GM-sI0Gw/edit?usp=sharing)
For the machine lerning section, we had to reduce the beautetest dataset to 5,885 rows as the list of ingredients was not as thoroughly cleaned as it could have been and we had to drop all the row which didn't have ingredients matching the one from incibeauty.


<a name="links"></a>

## Links

[Repository](https://github.com/pholasajustine/facial_care_recommendation)  

[Slides](https://docs.google.com/presentation/d/1fGHfo0mNQVIJsGMCUy0xJdrLo-l8XDMBPKZzN9xHTRk/edit?usp=sharing) 




   
