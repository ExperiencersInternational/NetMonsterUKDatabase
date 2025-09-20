# NetMonsterUKDatabase

A NetMonster database of cellular transmitters across a limited area in the UK. I did initially have split files here (which were split through AI code), but I have ultimately decided not to have them now just since it makes things easier for me until this gets contributors. I'll likely only publish a new big release every month or so?

Please note that some entries on the list are for networks abroad, but I am trying to clean this up.

Import onto your device by opening the NetMonster app > Menu > Database > Import > Pick File with the combined NTM downloaded from the releases page. I intend to eventually add downloads for other applications, but it's not in the scope of the project at the moment.

## Supported areas

These areas should have at least 10% coverage on at least one operator on 4G. This will probably get added to in the future. Some of these areas may be limited to something as simple as sites along a major road or railway, so this does not guarantee that you will have any data in your specific area.

Abergavenny, Barry, Barton-upon-Humber, Bath, Brecon, Bristol, Brough, Caldicot, Cardiff, Cardigan, Cheltenham, Chippenham, Cinderford, Cirencester, Derby, Doncaster, Dursley, Gloucester, Goole, Hessle, Hull, Keynsham, Lampeter, Mitcheldean, Monmouth, Newport, New Quay (Ceredigion), Reading, Ross-on-Wye, Rotherham, Sheffield, Slough, Stonehouse, Stroud, Swindon, Tamworth, Tewkesbury, Windsor, Worcester, Weston-super-mare, Yate

<img width="1440" height="2632" alt="A list of cell phone towers on a map of England and Wales. There's a general pattern of areas in the South West connecting to South Wales, West Wales, North East and Outer London." src="https://github.com/user-attachments/assets/4690cfe2-b142-40ed-850e-6873c3f8a1ab" />

> **Note:** Please note that the map will display blank when importing the database. NetMonster only shows sites and cells on the map after you have picked them up. If you're in a supported area, you should start filling out the map quickly but it may take longer. You can always check what cells are on the map by importing the NTM file into QGIS.

## Supported networks

* O2 - UK (23410): most coverage on 3G and 4G with limited coverage on 2G and marginal coverage on 5G (also most covered network on the database)
* vodafone UK (23415): most coverage on 4G only with limited 2G coverage and marginal 5G coverage
* 3 UK (23420): most coverage on 4G only with limited coverage on 3G
* EE (23430): most coverage on 4G only with limited coverage on 2G

Support for networks in the Channel Islands is currently outside of the scope of the project, but I may look into this in the future.
