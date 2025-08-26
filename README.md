# FCG
Progetto Pacman FCG

N.B. Come si vede dal risultato finale nel video tutti gli elementi sono colorati usando lo shading, nei file inviati (a partire da un certo file) sono disattivati, ma si possono attivare perfettamente usando lo viewport shading.

#ProgettoP1

![immagine1](https://github.com/user-attachments/assets/fda84b3b-e409-46dc-b7fe-fcaddf2caeed)

Ho iniziato creando un semplice uvsphere(che ho tagliato a metà e applicato il modifier mirror per semplificare molto il lavoro,l'ho anche usato sulle braccia,gambe etc.) per la testa, successivamente per le braccia ho usato un cube che ho trasformato con crtl+2 in una specie di sphere che poi ho allungato con grab,e dopo due tagli e uno extrude e extrude faces along normal(lavorando sulle facce) ho creato quello che dovrebbe essere parte del guanto.

#ProgettoP2


![immagine3](https://github.com/user-attachments/assets/17a0cb00-392c-4729-bc34-b84c35932b09)

Lavorando sulle facce ho fatto una extrude sulla parte più esterna del braccio dove poi ho preso le quattro facce esterne (su quella extrude) e fatto un faces along normal fino ad ottenere una specie di palla da cui con una grab ho dato leggermente la forma del guanto, successivamente con una grab sul guanto l'ho reso un po più lungo e mediante la knife ho tagliato alcune parti del guanto in modo che con una extrude formare il pollice.

#ProgettoP3
![immagine2](https://github.com/user-attachments/assets/acedbce8-a256-47a7-8c94-ed50752e4975)


Per le gambe ho seguito lo stesso ragionamento usato nelle braccia quindi ho creato un cube che poi ho trasformato usando ctrl+2, con grab l'ho allungato e usato una piccola extrude e poi una extrude faces along normal per dare un po la forma alo stivale che poi ho suddiviso e lavorando sulle facce una delle parti suddivise l'ho leggermente allungata con extrude per creare la punta dello stivale. 

#Progetto P6

![immagine5](https://github.com/user-attachments/assets/e4271b1a-87f1-4e54-aa78-34aa4611c63d)


Procedendo con gli stivali li ho separati dalle gambe, lavorando sulle facce poi li ho grabbati verso l'alto dando quella forma di gamba dentro lo stivale, successivamente lavorando sui lati con grab ho allungato leggermente la punta dei piedi così da poter allungare un altro lato verso l'alto con grab e dargli quella forma particolare da stivale da pagliaccio.

#ProgettoP7

![immagine4](https://github.com/user-attachments/assets/a42ae0e3-0b1c-4f73-94f7-d5052b575548)


Per creare la bocca ho usato una uvsphere che ho tagliato secondo diversi versi per avere come risultato un 1/8 di sfera cioè una specie di sagoma di una bocca(però a metà visto che il modificatore mirror ci da una mano per fare l'altra metà), questa sagoma l'ho attaccata nella testa e mediante il modficatore boolean con difference applicato alla testa e selezionando la sagoma ho creato la bocca, infine questa sagoma l'ho nascosta momentaneamente con H ma che poi verrà eliminata più avanti.

#ProgettoP9
![immagine6](https://github.com/user-attachments/assets/4fff2441-d024-46c5-8950-67dd0fa31223)

Per creare il naso, lavorando sui vertici ho scelto 2 punti specifici su cui ho usato la bevel applicata ai vertici (comando crtl+shift+B) e creato quei 2 esagoni che si possono osservare, dove poi lavorando sulle facce con una extrude ho creato il naso e per farlo stare un po in diagonale ho usato un grab sulla faccia più esterna e l'ho spostato, per la lingua invece sempicemente ho usato un cube trasformato col comando crtl+2 su cui ho effettuato diversi resize e grab per dare la forma e attaccarlo alla testa.

#ProgettoP10
![immagine7](https://github.com/user-attachments/assets/cbb3d322-abcd-4300-b5e4-d55d30e5436b)

Per gli occhi ho usato un circle che ho ruotato a 90°, con F ho creato la facciata, poi l'ho ridimensionato con qualche resize per dare la forma,successivamente ho applicato una leggera extrude sulla faccia(per dare quella forma 3d)ed infine usando il proportional editing objects e usando la grab li ho "attaccati" il più possibile alla testa.

#ProgettoP11
![immagine8](https://github.com/user-attachments/assets/b09f4da3-8ac6-4f99-b4f8-4ad4482b2c4a)
 Per le sopracciglia invece ho preso due lati specifici sopra l'occhio che ho dissolto e lavorando sui vertici ho usato la knife su cui ho creato un triangolo ed infine con la grab prendendo il vertice più in alto di questo triangolo l'ho mosso un po su vari assi per dare la forma finale.

#ProgettoP12

![immagine9](https://github.com/user-attachments/assets/505057e1-e7df-4a61-a2f4-bcc04e89166c)
In questo file semplicemente ho applicato tutti i modificatori usati fin ora su ciascuna parte del corpo ed infine mediante il comando ctrl+j ho unito tutti i pezzi del corpo per farsi di ottenere un unico oggetto.

#ProgettoP12animazione2
![immagine10](https://github.com/user-attachments/assets/b1723fcc-4390-4ec5-9368-394c0a4aa43c)

Su questo file ho cominciato a creare le ossa che poi serviranno per far muovere il personaggio durante l'animazione, ne ho create per il corpo/testa, per le braccia,i pollici , le gambe e la cintura, anche se quest'ultima poi l'ho cancellata perchè rendeva complicato la rotazione/movimento delle gambe (Al momento il peso delle ossa non è ancora distribuito bene e quando si vuole ruotare un articolazione, influenza anche altre parti del corpo).

#ProgettoP12animazioneunito3
![immagine11](https://github.com/user-attachments/assets/42131c4d-7202-457d-8440-157c9a60dd57)

Su questo file ho aggiunto ancora qualche osso per gli stivali e ho "unito" gambe e braccia al corpo (così durante l'animazione si muovono meglio) e per farlo ho cancellato le parti più interne al corpo, ho cancellato le facce del corpo più adiacenti a ciascuna articolazione ed ho applicato una bridge edge loops che poi con l'aiuto del grab ho aggiustato meglio.

#ProgettoP12animazioneunito4
![immagine12](https://github.com/user-attachments/assets/ee2b7538-ae74-49ce-9449-070af8408317)

Su questo file ho semplicemente aggiunto un plane; diciamo per creare un piccolo spazio di sceneggiatura per l'animazione finale.

#ProgettoP15
![immagine13](https://github.com/user-attachments/assets/38ff08a8-5e1f-4cb8-85a3-1e2ddfdfd0d4)

Su questo file, come accennato in precedenza ho semplicemenete cancellato le ossa della cintura che rendeva diffcile la rotazione/movimento delle gambe, ed ho anche già per lo più distribuito meglio il peso di ciascun osso per mezzo della weight paint.

#ProgettoP19
![immagine14](https://github.com/user-attachments/assets/4e16decc-8f98-4a7c-b0e4-7c44d01730d9)

Questo file semplicemente è il completamento finale della giusta distribuzione del peso per ciascun osso, ed è pronto per la creazione dei frame d'animazione.

#ProgettoP20
![immagine15](https://github.com/user-attachments/assets/28079792-3a0c-4b2b-9a3f-8a0f491cc1ed)

Questo file contiene l'animazione del Pacman,ho iniziato dal frame 60 e concluso al frame 220, e l'animazione consisite di un semplice salto e di un atterraggio facendo una specie di opplà.In più ho anche aggiunto una luce ad area.

#ProgettoP21
![immagine16](https://github.com/user-attachments/assets/c84424ec-23e3-42c1-a8ae-b228cd60f394)

Su questo file ho aggiunto un piccolo Pacman versione "2d" per abbellire un po l'animazione, per farlo ho seguito un piccolo tutorial che ho trovato, e la sua animazione viene effettuata applicando rotation key e location key. L'ho animato in modo che si fermi poco prima del pacman 3d così che quest'ultimo inizi la sua di animazione.

#ProgettoP22s
![immagine17](https://github.com/user-attachments/assets/7f3b42fe-d2a1-4ac3-b4d4-59e9141b0b58)


Questo è il risultato quasi finale dell'intera animazione, in cui ho aggiunto un'altra luce ad area, ho aggiunto il fantasmino(cui successivamente spiego la creazione) e le tipiche palline bianche dei giochi di Pacman che ho creato usando solo delle icosphere. Inoltre ho aggiunto un effetto di invisibilità quando il fantasmino e le palline venivano "mangiate", per farlo ho solo usato il disable in render e durante i frame in cui venivano mangiati l'ho disabilitato e aggiunto il keyframe. Ho anche modificato un po' la posizione della camera e fatto quel tipo di zoom per mezzo dei frame.

#ProgettoP23

![immagine18](https://github.com/user-attachments/assets/f9a853e3-410e-452c-9de5-90dfa2aa182c)

Su questo ultimo file ho semplicemente voltato il fantasmino per dargli miglior visibilità e gli ho aggiunto una piccola animazione di movimento, come se scappasse dall'essere mangiato.
Il video del rendering dell'animazione è allegato. Ho anche aggiunto un piccolo audio trovato su internet.

#Fantasma
![immagine19](https://github.com/user-attachments/assets/da8f9763-2828-4a21-91bf-3f03b4efb84a)

Per la creazione del fantasmino ho usato una uvsphere che poi ho tagliato a metà e lavorando sui lati e per mezzo di una extrude ho fatto l'estrusione verso il basso, e per dare quella forma di spigoli, lavorando sui vertici ho solo grabbato verso l'alto ciascun vertice.Per gli occhi invece ho usato una uvshpere che ho ridimensionato ed applicato vari resize per dargli la giusta dimensione e per dargli quella forma a goccia ho usato il grab con aiuto del proportional editing objects.Per le braccia ho seguito lo stesso procedimento del Pacman spiegato in precedenza.

#Fanatasma1
![immagine20](https://github.com/user-attachments/assets/45f31e06-c4d1-4ca0-bb14-6a956eae4b27)

Per la bocca invece ho usato una cube su cui ho applicato il comando ctrl+2, ci ho applicato alcune resize per la giusta dimensione e usando il grab ed il proportional editing objects ho dato quella forma curva, la lingua invece è solo lavoro di shading.

#Fantasma2
![immagine21](https://github.com/user-attachments/assets/a83fa873-7dc3-4a80-a0a4-334f1a358140)

Su questo file ho solo dato una forma migliore ai guanti,lavorando sulle facce ho solo usato la grab e così ho dato un po' quella forma infossata.

#Fantasma3
![immagine22](https://github.com/user-attachments/assets/55787b3d-991b-49fb-add0-55a300a8877e)

Su questo ultimo file invece ho solo dato una migliore posa con le braccia al personaggio, per farlo ho solo effettutato rotazioni e grab sulle braccia fino a raggiungere la forma desiderata.

