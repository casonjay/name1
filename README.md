# Mein Markdown-Dokument

Dies ist ein Beispiel für Markdown-Code. Hier sind einige Formatierungsoptionen:

## Überschriften

Du kannst verschiedene Ebenen von Überschriften verwenden:

# Überschrift der ersten Ebene
## Überschrift der zweiten Ebene
### Überschrift der dritten Ebene

## Textformatierung

Du kannst Text *kursiv* oder **fett** formatieren.

## Aufzählungslisten

- Erster Punkt
- Zweiter Punkt
- Dritter Punkt

## Nummerierte Listen

1. Erster Punkt
2. Zweiter Punkt
3. Dritter Punkt

## Links

Du kannst auch Links einfügen, zum Beispiel zu einer Webseite: [OpenAI](https://openai.com/)

## Codeblöcke

Du kannst Codeblöcke erstellen, indem du den Code eingerückt schreibst oder indem du drei Backticks vor und nach dem Code verwendest:

mport requests

response = requests.get("https://api.example.com/data")
data = response.json()
print(data)

# Bedingte Anweisungen
if age < 18:
    print("Du bist minderjährig.")
elif age >= 18 and age < 65:
    print("Du bist erwachsen.")
else:
    print("Du bist im Rentenalter.")

# Schleifen
for i in range(1, 6):
    print(i)

while weight > 60:
    weight -= 1
    print("Gewicht reduziert sich um 1 kg.")
