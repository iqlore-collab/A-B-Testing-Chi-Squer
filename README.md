📊 A/B/n Testing: CTR & Statistical Decision Analysis
🚀 Project Summary

This project demonstrates an end-to-end A/B/n testing framework used to evaluate and compare multiple website variants based on user click behavior. The analysis combines CTR metrics, Chi-Square statistical testing, and post-hoc comparisons to support data-driven product decisions.

The goal is not only to identify performance differences but also to determine whether those differences are statistically significant and business-relevant.

🎯 Key Objectives
Measure and compare Click-Through Rate (CTR) across multiple web variants (A, B, C, D)
Apply Chi-Square statistical testing to evaluate significance
Perform pairwise comparisons with Bonferroni correction
Identify whether a clear winning variant exists
Support product decisions using both statistics and user behavior signals
📊 Dataset

Each variant contains:

Clicks – number of CTA interactions (e.g. “SHOP NOW”, “SEE DEALS”)
Visits – total page visits
Derived metric:
CTR = Clicks / Visits
🧠 Methodology
1. CTR Analysis

CTR is computed per variant to measure engagement performance.

2. Chi-Square Test

Used to test whether click distributions differ significantly across variants.

H0 (null hypothesis): All variants perform equally
H1 (alternative hypothesis): At least one variant differs
3. Post-hoc Pairwise Testing

All variant pairs are compared using Chi-Square tests with Bonferroni correction to control for multiple comparisons.

📈 Key Insights
CTR differences alone are not sufficient for decision-making
Statistical significance determines whether observed differences are reliable
Behavioral metrics (e.g. drop-off rate, return rate) provide additional context for UX quality
🏁 Example Outcome
Some variants may show higher CTR but also higher drop-off rates
Other variants may show more stable engagement and better retention signals

👉 Final product decisions are based on a combination of:

statistical significance
performance ranking
user behavior patterns
💡 Business Impact

This analysis enables:

Data-driven A/B testing decisions
Reduction of subjective product choices
Identification of UX patterns affecting user retention and engagement
Clear framework for selecting or rejecting UI variants
🛠️ Tools & Technologies
Python (Pandas, SciPy)
Chi-Square statistical testing
Bonferroni correction
Jupyter Notebook
📌 Key Skills Demonstrated
A/B/n testing design and analysis
Hypothesis testing (Chi-Square)
Multiple comparison correction
Product analytics thinking
Data-driven decision-making
📁 Repository File
Statistical_Analysis_of_Web_Variants_(CTR_&_Chi_Square_Test).ipynb
🧾 Conclusion

This project shows how statistical testing and behavioral analytics can be combined to make reliable product decisions beyond simple CTR comparisons. It highlights the importance of balancing statistical significance with real user behavior metrics to choose the most effective product variant.

POLISH

📊 A/B/n Testing: Analiza CTR i testy statystyczne (Chi-Square)
🚀 Podsumowanie projektu

Projekt przedstawia kompletną analizę testu A/B/n, którego celem jest porównanie kilku wariantów strony internetowej pod kątem skuteczności generowania kliknięć (CTR).

Analiza łączy metryki biznesowe (CTR) z testami statystycznymi (Chi-Square) oraz korektą wielokrotnych porównań (Bonferroni), aby podejmować decyzje oparte na danych, a nie intuicji.

🎯 Cele projektu
Porównanie CTR dla wariantów A, B, C, D
Sprawdzenie istotności statystycznej różnic między wariantami
Identyfikacja potencjalnego „zwycięzcy” testu A/B/n
Wsparcie decyzji produktowych na podstawie danych
📊 Dane

Każdy wariant zawiera:

Clicks – liczba kliknięć w elementy CTA (np. „SHOP NOW”, „SEE DEALS”)
Visits – liczba wizyt na stronie
Wyliczana metryka:
CTR = Clicks / Visits
🧠 Metodologia
1. Analiza CTR

Obliczenie współczynnika CTR dla każdego wariantu w celu porównania ich skuteczności.

2. Test Chi-Square

Test sprawdzający, czy różnice w liczbie kliknięć między wariantami są istotne statystycznie.

H0 (hipoteza zerowa): wszystkie warianty mają taki sam CTR
H1 (hipoteza alternatywna): co najmniej jeden wariant różni się istotnie
3. Porównania parami (post-hoc)

Wykonano testy parowe między wszystkimi wariantami z zastosowaniem korekty Bonferroniego, aby ograniczyć ryzyko błędu wielokrotnych porównań.

📈 Kluczowe wnioski
Sama różnica CTR nie wystarcza do podjęcia decyzji
Istotność statystyczna pokazuje, czy różnice są „realne”, czy przypadkowe
Dodatkowe metryki (drop-off rate, return rate) pomagają ocenić jakość doświadczenia użytkownika
🏁 Przykład interpretacji
Niektóre warianty mogą mieć wyższy CTR, ale jednocześnie gorsze wskaźniki zaangażowania (np. większy drop-off)
Inne warianty mogą oferować bardziej stabilne zachowanie użytkowników

👉 Ostateczna decyzja powinna uwzględniać:

istotność statystyczną
ranking CTR
zachowanie użytkowników
💡 Wpływ biznesowy

Projekt pozwala:

podejmować decyzje produktowe oparte na danych
unikać błędnych wniosków opartych wyłącznie na CTR
lepiej rozumieć zachowanie użytkowników
wybierać warianty o najlepszym realnym wpływie na UX i konwersję
🛠️ Technologie
Python (Pandas, SciPy)
Test Chi-Square
Korekta Bonferroniego
Jupyter Notebook
📌 Umiejętności
Analiza A/B/n testów
Testowanie hipotez statystycznych
Analiza CTR i metryk UX
Myślenie produktowe (product analytics)
Podejmowanie decyzji na podstawie danych
🧾 Podsumowanie

Projekt pokazuje, jak łączyć analizę statystyczną z metrykami biznesowymi, aby podejmować wiarygodne decyzje produktowe. Kluczowym elementem jest nie tylko CTR, ale także jego istotność statystyczna oraz wpływ na zachowanie użytkowników.
