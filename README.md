<a id="readme-top"></a>

<h3 align="center">Smart vekkerklokke</h3>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#om-prosjektet">Om prosjektet</a>
    </li>
    <li>
      <a href="#getting-started">Installasjon</a>
    </li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## Om prosjektet

I dette prosjektet skal vi utvikle en form for smart klokke som hovedsakelig skal vekke brukeren med hjelp av lys i stedet for lyd. 
Her skal vi se nærmere på hvordan vi setter opp MQTT og Node-Red



<!-- GETTING STARTED -->
## Getting Started

Man trenger å laste ned Node-Red [Installasjonsveiledning](https://nodered.org/docs/getting-started/local)
Også trenger man å laste ned mosquitto [Installasjonsveiledning](https://mosquitto.org/download/)



### Installasjon

1. Installere mosquitto config filen
   [a Mosquitto Config](https://github.com/Phoenix-mk3/MQTT-NodeRED/blob/main/mosquitto/mosquitto.conf)

2. Overskriv den lokale mosquitto config fila.
     Som regel ligger denne her: C:\Program Files\mosquitto\mosquitto.conf
   
3. Kjøre Node-Red i et terminal vindu
   ```sh
   Node-Red
   ```
   
4. Kjøre mosquitto i et annet terminal vindu. Pass på at fil plassering er skrevet riktig for ditt tilfelle.
   ```sh
   "C:\Program Files\mosquitto\mosquitto.exe" -c "C:\Program Files\mosquitto\mosquitto.conf" -v
   ```
5. Om alt går etter planen så skal man få opp hvilken IP Node-Red kjøres på. Man kan da åpne den ip-adressa i en nettleser for å så se node-red

<img width="725" alt="image" src="https://github.com/user-attachments/assets/6fdbdd71-c5ee-4fce-9932-cee32768deb3">

6. Last ned og importer vår Node-Red flow
   [a Flow](https://github.com/Phoenix-mk3/MQTT-NodeRED/blob/main/flows.json)
   I Node-Red, trykk på i høyret hjørnet
   <img width="373" alt="image" src="https://github.com/user-attachments/assets/20dedf05-b414-4bce-bf94-e47370f35062">
   Import
   Så kan man enten lime inn hele json fila eller opplaste den om man har lasted den ned lokalt på maskina.

   
<p align="right">(<a href="#readme-top">back to top</a>)</p>




