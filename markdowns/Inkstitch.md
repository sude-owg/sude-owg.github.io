# Inkstitch
- Inscape -> Einstellungen -> Knoten -> Zeige Pfadrichtungen an Außenlinie
- Zickzackstich
	- Bezierkurve
	- Linienbreite ist Breite der Zickzack
	- Inkstitch plugin -> Params -> Satin stich enabled; spacing einstellen
	- apply and quit
- gebogene Linie
	- gestrichelte Linie
	- Params - Satin stitch
- Bean stitch
	- genauso nur Bean stitch repeats angeben (1 = 3mal: hin, zurück, hin)
- manueller stich
	- jeder Knoten eines Pfades ist ein Einstich
	- Params -> manual stitch placement
- füllen (auto)
	- Pfad mit gefüllter Farbe
	- crtl + shift + K wenn man Lücken drin hat (z.B. zwei Kreise, die zusammen ausgewählt sind)
	- Pfade markieren
	- Params -> automatically routed
	- underlay tab -> inset: underly cannot be seen from outside if value is defined
	- start and end
		- commands -> attach commands to selected objects -> fill start position
- Satin columns
	- Pfade -> crtl +K: gruppieren
	- path directions have to be the same, if not:
		mark one node -> path reverse
	- Paramas -> Satin Column tab
	- winkel kann über weitere Knoten beeinflusst werden
	- mit einem Pfad machen:
		Pfaddicke angeben
		Satintools -> convert line to satin column
	- pull compensation: damit der Stoff nicht zusammengezogen wird -> experimentieren
	- underlay
		- für dünne columns: center
		- contour: beide Seiten -> schmale bis mittel breite columns
		- zigzag
	- E Stich: weicher; anklicken
