SkinSafe AI – Dataset Documentation

This folder contains datasets used for cosmetic product information, ingredient identification and personalised skincare recommendations.

1. Open Beauty Facts

- File: "en.openbeautyfacts.org.products.csv.gz"
- Source: https://world.openbeautyfacts.org/
- Licence: Open Database Licence (ODbL 1.0)

Purpose:
Provides cosmetic and beauty product information for product analysis and recommendation.

Expected fields:

- Product name
- Brand
- Ingredient list
- Product category (where available)

Preprocessing:

- Extract compressed CSV
- Remove duplicate records
- Handle missing values
- Clean ingredient names
- Filter products with ingredient information

2. Skincare Ingredients Dataset

- File: "ingredients.csv"
- Source: https://github.com/bsyilmaz/skincare-ingredients-dataset
- Licence: MIT

Purpose:
Provides structured cosmetic ingredient information for ingredient identification and explanation.

Available information includes:

- INCI names and synonyms
- Ingredient categories and functions
- Benefits and descriptions
- Skin-type information
- Comedogenic ratings
- Irritancy information
- Ingredient compatibility information
- Evidence-level labels

Preprocessing:

- Standardise ingredient names
- Match ingredient synonyms
- Check missing values
- Verify important ingredient information against reliable references

Dataset Limitations

- Product records may contain incomplete ingredient lists.
- Ingredient information does not guarantee individual skin compatibility.
- Compatibility and irritancy information requires scientific verification.
- Ingredient lists alone cannot establish the safety of a finished product.

Project Usage

These datasets will support:

1. Cosmetic ingredient identification
2. Ingredient information lookup
3. Personalised ingredient analysis
4. Product comparison
5. Alternative product recommendation

Note: SkinSafe AI is an informational decision-support platform, not a medical diagnosis or product safety certification system.
