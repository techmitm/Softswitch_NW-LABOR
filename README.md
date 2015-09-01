# Softswitch NW-LABOR
Ein ohne Druck zu bedienender Schalter

Die Idee ist es, einen behindertengerechten Schalter zu entwickeln,
welcher nicht optisch bzw. haptisch ausgelöst wird, sondern durch
ein einfaches näheren an den Schalter. Dies soll so umgesetzt werden,
dass die Emmitierung von Elektronen aus der Hand verstärkt und
gemessen wird. Dazu soll nachher ein Darlington-Array dienen, welches
an einem Mikrokontroller angeschlossen ist, dieser wird höchstwahr-
scheinlich ein ATTINY13/45 sein. Die Aufgabe des ATTiny's wird es sein
die Messwerte ein zu lesen und dann zu verarbeiten.

Es soll später 2 verschiedene Modi geben. Der Erste stellt einen Taster
dar und der Zweite stellt einen Schalter dar d.h.: das wenn man die
Hand im ersten modus vor den Schalter hält, schaltet er solange wie
sie davor ist und im Zweite wird einfach umgeschaltet.
