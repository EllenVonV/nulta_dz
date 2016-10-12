# JMBAG
0036494935

#Pitanje 1.:
  Nakon dodavanja class library kao reference, u Bin/Debug folderu je stvoren .dll file. Nakon uklanjanja istog, program se srušio pošto je u metapodacima .dll naveden kao ovisnost i izvođenje programa zahtjeva prisutnost .dll-a u sustavu.
  Ako bismo slali aplikaciju, bilo bi potrebno poslati .exe i .dll fileove.
  
#Pitanje 2.:
  Konzolna aplikacija je koristila novi string, jer se prilikom rebuilda konzolne aplikacije rebuildao i class library projekt.

#Pitanje 3.:
  Ispisalo se: "Pero: Hello World".

#Pitanje 4.:
  Unutar Bin/Debug foldera stvoren je još jedan .dll file.

#Pitanje 5.:
  Obrišemo li originalni .dll aplikacija i dalje radi. 

#Pitanje 6.:
  Aplikacija je uspješno buildana. U Packages direktoriju se nalazi NodaTime. 
