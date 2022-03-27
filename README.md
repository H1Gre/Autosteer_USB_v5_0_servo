# Autosteer_USB_v5_0_servo
 Autosteer ino for AGopenGPS v.5 include LED-Pin and Servo-Pin
 
 
 =======================================================================

Deutsch:
Autosteer Sketch für AGopenGPS inklusive einem LED-Pin und einem Servo-Pin

Mit diesem Sketch versuche ich direkt am Autosteer Arduino eine LED oder ein Relay anzusteuern, dass bei aktiver Lenkung den PIN auf "high" setzt. In Verbindung mit einem Relay kann z.B. eine Magnetkupplung geschaltet werden. 
Zusätzlich ist auch ein Servo-Pin integriert. Dieser Pin muss ein PWM-Pin sein. Es sind zwei Winkel deffiniert. Ein Winkel für die "Ein"-Position und ein Winkel für die "Aus"-Position. Der Anschluss eines üblichen RC-Modelbauservos sollte über getrennte Spannungsversorgung erfolgen. Heißt, Masse und Signal-Pin an den Arduino und "+"-Leitung auf eine Spannungsquelle (BEC,DC/DC-Step Down...). Bitte die Zulässige Spannung des Servos beachten. In der Regel 4,6V bis 7,2V. Ich nutze einen Step Down mit 5V für den Arduino und das Servo und den WAS über ADS1115. 
Bitte beachten: Unterschiedliche Servos haben unterschiedliche Maximalwerte für den Links- und Rechts-Anschlag. Fangt in der "Mitte" an und testet verschiedene Werte nach links/rechts. Bie zu großen oder keinen Werten tut sich dann nichts mehr!

ACHTUNG: Ich übernehme keine Gewehr. Ich bin Anfänger in der Progrmiierung und freue mich auf konstruktive Kritik.
