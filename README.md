# Kundbortfall hos en bank

Analys av varför bankkunder lämnar och vilka åtgärder som är mest rimliga.

**Verktyg:** Python, pandas, seaborn, matplotlib  
**Data:** Bank Customer Churn (ca 10 000 kunder)

## Syfte
Identifiera vilka kundgrupper som har högst risk att lämna och ta fram konkreta rekommendationer till verksamheten.

## Vad jag gjorde
- Kontrollerade saknade värden och uppenbara fel
- Jämförde kunder som stannat med kunder som lämnat
- Visualiserade churn mot ålder, antal produkter, saldo och aktivitet
- Sammanfattade insikter och åtgärder

## Viktigaste insikter
- Äldre kunder lämnar i högre utsträckning än yngre
- Kunder med 3–4 produkter har tydligt högre churn än kunder med 1–2 produkter
- Inaktiva medlemmar lämnar oftare än aktiva
- Kunder som lämnar har ofta högre saldo, vilket gör bortfallet extra kostsamt

## Rekommendationer
- Prioritera uppföljning av äldre, inaktiva kunder med högt saldo
- Undersök varför kunder med många produkter lämnar – erbjudandet kan vara felpackat
- Stärk aktivering av inaktiva kunder innan de hinner lämna
- Använd ålder, produktantal och aktivitet som tidiga risksignaler

## Struktur
- `Bankprojekt.ipynb` – analys, visualiseringar och slutsats
- https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn – underlag

## Begränsning
Det här är en explorativ analys, inte en färdig prediktionsmodell. Målet är att visa mönster som verksamheten kan agera på.
