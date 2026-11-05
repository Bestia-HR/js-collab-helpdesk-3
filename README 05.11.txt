trzeba strukutre DOM strony zbudowac 

Brak elementu <form>: W pliku main.html sekcja dodawania zgłoszenia to zwykły div (id="panel-dodawania"), a nie tag <form>. Przez to m.in. nie działa poprawnie domyślna obsługa klawisza [Enter] dla formularzy.

Brak atrybutu name="title": Input tematu ma id="input-temat", ale brakuje mu wymaganego w instrukcji atrybutu name="title".

Brak komunikatu role=status: W całym pliku main.html nie ma żadnego elementu z atrybutem role="status".

#
