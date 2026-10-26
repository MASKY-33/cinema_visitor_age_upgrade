film = int(input("Minimumleeftijd van de film (18, 16, 12 of 1): "))
bezoeker_age = int(input("Leeftijd van de bezoeker: "))


if film >= 18 and bezoeker_age >= 18:
    print("Bezoeker is oud genoeg voor de film. " "(18+)") # <-- Om aan te geven dat het duidelijk is dat het om de (18+) film gaat
elif film >= 18 and bezoeker_age < 18:
    print("Bezoeker is te jong voor de film. " "(18+)")


elif film >= 16 and bezoeker_age >= 16:
    print("Bezoeker is oud genoeg voor de film. " "(16+)") # <-- Om aan te geven dat het duidelijk is dat het om de (16+) film gaat
elif film >= 16 and bezoeker_age < 16:
    print("Bezoeker is te jong voor de film. " "(16+)")


elif film >= 12 and bezoeker_age >= 12:
    print("Bezoeker is oud genoeg voor de film. " "(12+)") # <-- Om aan te geven dat het duidelijk is dat het om de (12+) film gaat
elif film >= 12 and bezoeker_age < 12:
    print("Bezoeker is te jong voor de film. " "(12+)")


elif film >= 1 and bezoeker_age >= 1:
    print("Bezoeker is oud genoeg voor de film. " "(Alle leeftijden)") # <-- Om aan te geven dat het duidelijk is dat het voor 'Alle leeftijden' beschikbaar is
else:
    print("Foutieve leeftijdsingeving!") # Lager dan (1) is een 'Foutieve leeftijdsingeving'
