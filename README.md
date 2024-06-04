# LD Nr. 3. Prognozavimo uždavinių EVS sprendimas

Šio projekto tikslas yra išmokti taikyti dirbtinio intelekto metodus duomenų analizei ir prognozavimui, taip pat suprasti, kaip šie metodai gali būti pritaikyti sprendžiant realaus pasaulio elektroninio verslo problemas.
## Projekto Struktūra

Šis projektas susideda iš kelių etapų:

1. **Duomenų Paruošimas**:
    - Duomenų nuskaitymas ir apdorojimas.
    - Trūkstamų duomenų tvarkymas.
    - Duomenų normalizavimas.
2. **Duomenų tyrinėjimas ir analizė**
3. **Modelio Mokymas**:
    - Inkrementinis modelio mokymas naudojant SGDClassifier.
4. **Prognozės**:
    - Prognozės atlikimas konkrečiam vartotojui.

## Projekto Failai
- `LD3PrognozavimoUzdavinys.ipynb`: Colab užrašinė su visa Duomenų paruošimo, analizės eiga ir modelio mokymu.
- `encoder_sku.pkl`: SKU koduotojas.
- `encoder_category.pkl`: Kategorijų koduotojas.
- `sku_prediction_model.pkl`: Apmokytas modelis.
- `label_encoder.pkl`: Žymenų koduotojas.
