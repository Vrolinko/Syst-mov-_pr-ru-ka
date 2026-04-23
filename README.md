# Systemova príručka 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Vstupné dáta nie sú priamo súčasťou repozitára, keďže ich veľkosť presahuje limity. Z tohto dôvodu je potrebné ich stiahnuť z externého odkazu: [DOPLŇ LINK]. Po stiahnutí je potrebné zachovať štruktúru, kde sa všetky obrázky nachádzajú v priečinku img.

Pred samotným použitím fúzie je potrebné najskôr natrénovať jednotlivé modely. Ide o textové modely (BERT, ELECTRA, RoBERTa) a obrazové modely (SimpleCNN, ResNet50, ViT). Po ich natrénovaní a uložení je možné spustiť skript LateFusion.py, ktorý kombinuje ich výstupy.

Pred spustením fúzie je nutné upraviť cesty k modelom BERT a RoBERTa v konfigurácii TEXT_CONFIG, aby ukazovali na správne uložené checkpointy. Bez tejto úpravy skript nebude fungovať správne.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
