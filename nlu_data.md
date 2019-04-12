---
title: intents
has_children: false
---
<!--- Make sure to update this training data file with more training examples from https://forum.rasa.com/t/rasa-starter-pack/704 --> 

## intent:goodbye <!--- The label of the intent --> 
- Tschüss
- Servus
- Bis später
- Bye

## intent:greet
- Hi
- Hey
- Hi [Lesia](name)
- Hallo
- Guten Morgen
- Guten Abend

## intent:thanks
- Danke
- Danke dir
- Vielen Dank
- Danke bot
- Danke [Lesia](name)
- Super Danke
- Vielen Dank für deine Hilfe
- Danke für die Hilfe

## intent:affirm
- ja
- ja klar
- absolut
- sicher
- definitiv


## intent:name
- Mein Name ist [Juste](name)  <!--- Square brackets contain the value of entity while the text in parentheses is a a label of the entity --> 
- Ich bin [Josh](name)
- Ich heiße [Lucy](name)
- Ich heiße [Ben](name)
- Mein Name ist [John](name)
- Nenn mich [Sam](name)
- Bitte nenn mich [Linda](name)
- Ich bin [Richard](name)
- Nenn mich [Sally](name)
- Ich bin [Philipp](name)
- Ich bin [Charlie](name)
- Ich bin [Charlie](name)
- Ich bin [Ben](name)
- Nenn mich [Susan](name)
- [Lucy](name)
- [Peter](name)
- [Mark](name)
- [Joseph](name)
- [Tan](name)
- [Pete](name)
- [Elon](name)
- [Penny](name)
- [Andrew](name)
- [Lora](name)
- [Stan](name) ist mein Name
- [Susan](name) ist der Name
- [Ross](vorname) ist mein Vorname
- [Bing](nachname) ist mein Nachname
- Jeder nennt mich [Laura](name)
- Ich bin [Ganesh](name)
- Mein Name ist [Mike](name)
- Nenn mich einfach [Monika](name)
- Du kannst mich [Suraj](name) nennen
- Mein Name ist [Ajay](name)

## intent:joke
- Kannst du mir einen Witz erzählen?
- Ich würde gerne einen Witz hören.