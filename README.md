# 🧪 Clients A/B/C/D Experiment Analysis

## 🎯 Project Objective

This project analyzes an A/B/C/D experiment conducted on the Eniac homepage to evaluate which button design performs best in terms of user engagement.

The tested variants were:
- White “SHOP NOW”
- Red “SHOP NOW”
- White “SEE DEALS”
- Red “SEE DEALS”

The main goal is to determine whether design changes (color + copy) significantly affect user Click-Through Rate (CTR).

---

## 📊 Dataset Description

The dataset contains aggregated click interaction data from four homepage variants (A, B, C, D).

Each CSV file includes:

- `Element ID` – unique identifier of UI elements  
- `Tag name` – HTML tag type  
- `Name` – element label (e.g. Mac, iPhone, Accessories)  
- `No. clicks` – number of clicks per element  
- `Visible?` – visibility status of the element  
- `Snapshot information` – experiment metadata  

### Data scope:
- Total homepage visits: **50,061**
- 4 experimental variants (A, B, C, D)

---

## ⚠️ Limitations

- No user-level or session-level tracking
- No funnel or path analysis available
- Missing metrics:
  - Drop-off rate
  - Homepage-return rate

As a result, the analysis focuses on CTR and click distribution only.

---

## 🧪 Methodology

- Primary metric: Click-Through Rate (CTR)
- Statistical test: Chi-square test (χ²)
- Significance level: α = 0.05

CTR formula:
CTR = clicks / visits

---

## 📈 Key Output

- CTR comparison across all variants
- Statistical significance testing (χ²)
- Identification of best-performing variant

---

## 🚀 Business Value

This analysis supports product decisions by:
- identifying the most effective UI design,
- quantifying impact of design changes,
- enabling data-driven A/B testing decisions for homepage optimization.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SciPy

---

## 📌 Author

UX / Product Analytics Case Study – Client Experiment


PL


🧪 Analiza eksperymentu A/B/C/D – Klient
📌 Opis projektu

Projekt dotyczy analizy eksperymentu A/B/C/D przeprowadzonego na stronie głównej Klienta w celu oceny wpływu różnych wariantów przycisku CTA (Call-To-Action) na zaangażowanie użytkowników.

Testowane warianty:

White “SHOP NOW”
Red “SHOP NOW”
White “SEE DEALS”
Red “SEE DEALS”

Celem było sprawdzenie, czy zmiany w kolorze i treści przycisku wpływają na zachowanie użytkowników.

🎯 Cel analizy

Główne cele analizy:

porównanie Click-Through Rate (CTR) dla wszystkich wariantów
sprawdzenie, czy różnice są istotne statystycznie
identyfikacja najlepszej wersji
wsparcie decyzji produktowych opartych na danych
📊 Dane

Dane składają się z czterech plików CSV odpowiadających wariantom A, B, C i D.

Każdy plik zawiera zagregowane dane o interakcjach użytkowników.

Struktura danych:
Element ID – identyfikator elementu interfejsu
Tag name – typ elementu HTML
Name – nazwa elementu (np. Mac, iPhone, Accessories)
No. clicks – liczba kliknięć w element
Visible? – czy element był widoczny
Snapshot information – metadane eksperymentu
Założenia:
liczba wizyt na wariant: 50 061
dane zagregowane (brak danych o użytkownikach)
⚠️ Ograniczenia
brak danych na poziomie użytkownika (user/session)
brak ścieżek użytkownika (user journey)
brak możliwości bezpośredniego obliczenia:
drop-off rate
homepage-return rate

Analiza skupia się więc głównie na:

CTR
rozkładzie kliknięć
🧪 Metodyka
Główna metryka:
Click-Through Rate (CTR)
𝐶
𝑇
𝑅
=
kliknięcia
wizyty
CTR=
wizyty
kliknięcia
	​

Test statystyczny:
test chi-kwadrat (χ²)
Hipotezy:
H₀: wszystkie warianty mają taki sam CTR
H₁: istnieje różnica w CTR między wariantami
Poziom istotności:
α = 0.05 (95%)
📈 Wyniki

Analiza obejmuje:

obliczenie CTR dla każdej wersji
budowę tabeli kontyngencji (kliknięcia vs brak kliknięć)
test chi-kwadrat
ranking wariantów
💡 Wnioski
Design (kolor + tekst przycisku) może wpływać na zachowanie użytkowników
CTR to tylko część obrazu — warto analizować także metryki dalszych etapów
Wyniki należy interpretować w kontekście biznesowym
🚀 Wartość biznesowa

Analiza pozwala:

wybrać najlepszy wariant interfejsu
mierzyć wpływ zmian UX
podejmować decyzje oparte na danych
🛠️ Technologie
Python
Pandas
NumPy
SciPy
Matplotlib
📂 Struktura projektu
├── data/
│   ├── eniac_a.csv
│   ├── eniac_b.csv
│   ├── eniac_c.csv
│   └── eniac_d.csv
├── notebooks/
│   └── analysis.ipynb
├── README.md
👤 Autor

Case study z zakresu analityki produktu i testów A/B
Analiza eksperymentu
