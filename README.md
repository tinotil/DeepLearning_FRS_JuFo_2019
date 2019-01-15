# DeepLearning_FRS_JuFo_2019
Beitrag zu Jugend forscht 2019 von Constantin Tilman Schott

Einsatz von Methoden der Künstlichen Intelligenz in der kephalometrischen Röntgendiagnostik

In der Kephalometrie (Kopfvermessungskunde) müssen  auf Fernröntgenbilden des Schädels seitlich (FRS) strukturelle Punkte detektiert und ausgewertet werden. Diese Arbeit erfolgt z.Zt. manuell und ist somit personal und zeitintensiv. Das Ziel dieser Arbeit ist die automatisierte Bestimmung des für diese Analyse wesentlichen Sella-Punktes, der als imaginärer Mittelpunkt der Sella turcica auf der Schädelbasis anzusehen ist, so dass sowohl Ärzte zeitlich entlastet werden als auch Patienten von einer höheren Standardisierung der Diagnostik profitieren können.

Mithilfe von Verfahren der künstlichen Intelligenz, im Speziellen dem Einsatz von Convolutional Neural Networks, wurden dabei von selbstlernenden Programmen die dafür notwendigen Strukturen erkannt und der Sella-Punkt gesetzt. Dabei wurde eine neue Herangehensweise entwickelt, die teilweise auf bereits bekannten Verfahren aufbaut, diese kombiniert und weiterentwickelt. Die selbstlernenden Neuronalen Netze passen ihre Parameter dabei schrittweise autonom so an, dass die Abweichung des durch das Netz prognostizierten Ergebnisses zu dem fachärztlich gesetzten Sella-Punkt minimiert wird. Dabei ist es gelungen, den Sella-Punkt mit einer durchschnittlichen Abweichung von weniger als 1% der Größe der Röntgenbilder zu den manuell gesetzten Punkten zu bestimmen -  eine absolute Abweichung von 0,6 Millimetern. Mit der entwickelten Methodik einer Kombination aus einem Sliding-Window-Verfahren, einem Klassifizierungsnetz und einem Key-Point-Detection-Netz können künftig auch weitere Punkte der kephalometrischen Analyse bestimmt werden.

