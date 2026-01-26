# NetMonsterUKDatabase

A NetMonster database of cellular transmitters across a limited area in the UK. I'll likely only publish a new big release every month or so?

Import onto your device by opening the NetMonster app > Menu > Database > Import > Pick File with the combined NTM downloaded from the releases page. I intend to eventually add downloads for other applications, but it's not in the scope of the project at the moment.

## Supported areas

These areas should have at least 10% coverage on at least one operator on 4G. This will probably get added to in the future. Some of these areas may be limited to something as simple as sites along a major road or railway, so this does not guarantee that you will have any data in your specific area.

Aberaeron, Abergavenny, Barry, Barton-upon-Humber, Bath, Beaconsfield, Boston, Brecon, Bristol, Brough, Burford, Caldicot, Cardiff, Cardigan, Carterton, Cheltenham, Chepstow, Chippenham, Cinderford, Cirencester, Coleford, Derby, Doncaster, Dursley, Frome, Gloucester, Goole, Hessle, High Wycombe, Hull, Keynsham, Lampeter, Ledbury, Llandovery, Lydney, Mitcheldean, Monmouth, Newport, New Quay (Ceredigion), Oxford, Portishead, Reading, Ross-on-Wye, Rotherham, Sheffield, Slough, Spalding, Staines-upon-Thames, Stonehouse, Stroud, Swindon, Tamworth, Tewkesbury, Trowbridge, Wells, Windsor, Witney, Worcester, Weston-super-mare, Yate

<img width="1050" height="867" alt="A OpenStreetMap map with various coloured points for each network, with a lot of blue primarily for O2. You can see from around Brighton to Corrour." title="A OpenStreetMap map with various coloured points for each network, with a lot of blue primarily for O2. You can see from around Brighton to Corrour." src="https://github.com/user-attachments/assets/d55fcf48-dfee-4342-843a-22e469715ff2" />

> **Note:** Please note that the map will display blank when importing the database. NetMonster only shows sites and cells on the map after you have picked them up. If you're in a supported area, you should start filling out the map quickly but it may take longer. You can always check what cells are on the map by importing the NTM file into QGIS. External websites also exist for viewing data but data may not be up to date on those sites. Map of mapped sites last updated 2026-01-26.

## Supported networks

* Wavemobile (23404): limited 4G coverage, no 2G coverage
* O2 - UK (23410): most coverage on 3G and 4G with limited coverage on 2G and marginal coverage on 5G
* vodafone UK (23415): most coverage on 4G only with limited 2G coverage and marginal 5G coverage
* 3 UK (23420): most coverage on 4G only
* EE (23430): most coverage on 4G only with limited coverage on 2G and marginal coverage on 5G

Support for networks in the Channel Islands is currently outside of the scope of the project, but I may look into this in the future.
