# REACT-ucenje
1 - uvod, state, props, komponente
2 - prenos svojstava, spread operator, lifecycle, dogadjaji
3 - slozeniji rad sa komponentama, portal
4 - React aplikacija (CV) od pocetka
5 - zadatak (rad sa props i state)
6 - zadatak (forme, provera input polja...)
7 - TO-DO React (dodate animacije, prosledjivanje metoda kao props)
8 - FETCH u Reactu (fetch ip adrese)
9 - prvi domaci (1. danasnji datum u posebnoj komponenti; 2. vreme koje je ostalo do sledecih olimpijskih igara; 3. neki fetch u trecoj komponenti(fetch bilo cega, moze i vreme))
!!!!!!!!!!!!!!!!!!!!VRLO VAZNO!!!!!!!!!!!!!!!!!!!!!!!!
--- najvaznija stvar koju sam naucio je da se arrow fje razlikuju i po tome sto nasledjuju this od roditelja, ako ih koristis u ucaurenim fjama une ce nasledjivati this od svojih parrenta. Ako ne koristis arrow fje, mooras da nasledjujes this sve do ucaurene fje da bi i ona koja je ucaurena znala sta je this. (npr:that=this a posle that.setState({.....})). Tu ni bajndovanje ne pomaze. Sve ovo ima veze kada se radi sa klasama i konstruktorima a ne sa fjama u React-u