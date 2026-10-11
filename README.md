Einfaches xG-Modell (Bundesliga 2024/25)

Dies ist ein einfaches xG-Modell, das mit Schussdaten von [Understat](https://understat.com) arbeitet. Dafür wurden alle 7.944 Schüsse aus 306 Spielen der Bundesliga-Saison 2024/25 gescrapt. Anschließend wurden die Schusskoordinaten in Meter umgerechnet und für jeden Schuss die Distanz und der Schusswinkel zum Tor berechnet.

Als nächster Schritt soll mit diesen Merkmalen eine logistische Regression trainiert und mit dem xG von Understat verglichen werden.

Verwendet wurden Python, Jupyter, requests, BeautifulSoup, pandas, NumPy und matplotlib.



