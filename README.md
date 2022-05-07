# Ekonometria

Badanie istotności wpływu czynników na kształtowanie się przeciętnego wynagrodzenia brutto w polskich miastach. 
Celem badań było sprawdzenie jakie czynniki istotnie mają wpływ na wysokość średniego wynagrodzenia brutto w polskich miastach. 
Czy wielkość miasta, ludność czy też ośrodki innowacyjne lub z kapitałem zagranicznym mają wpływ na zmianę cen na rynku pracy?

Wyniki mogły posłużyć jako sygnał dla średnich i małych miast, aby zainwestować swoje środki w rozwój danej dziedziny, by ożywić gospodarczo swój rejon. 
Model ekonometryczny może również być wskazówką jakiej wypłaty możemy oczekiwać w danym rejonie. Badania przeprowadzone w pakiecie Gretl.


W większości dane pochodzą z BANKU DANYCH LOKALNYCH opracowanego dla Głównego Urzędu 
Statystycznego. Skompletowano dane dla 66 miast na prawach powiatu w Polsce dla 2018r. Informację na temat liczby firm z kapitałem zagranicznym znaleziono na stronie:
- Centralnego Ośrodka Informacji Gospodarczej
- www.polskawliczbach.pl


W celu opisania zjawiska wykorzystano model regresji wielorakiej postaci:
Wzór 1-Postać analityczna modelu

    y= α₀ + α₁x₁ + α₂x₂ + α₃x₃ + α₄x₄ + α₅x₅ + α₆x₆ + α₇x₇ + ε

gdzie:

• zmienna objaśniana: 

    y- przeciętne miesięczne wynagrodzenia brutto;
  
• zmienne objaśniające ilościowe: 

    x₁- ludność
    x₂-liczba nowoutworzonych miejsc pracy
    x₃-bezrobotny na ofertę pracy
    x₄-cena za 1m2 na rynku wtórnym
    x₅-liczba firm z kapitałem zagranicznym
    x₆-liczba przedsiębiorstw innowacyjnych
• zmienna objaśniająca binarna: 

    x₇- miasto wojewódzkie
