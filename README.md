# trackhubs_public
## Collection of released trackhub records

kPetMar1.pri: https://trackhub.science.ru.nl/hubs/veenstralab/trackhubs_public/petromyzon.marinus/hub.txt
mm10: https://trackhub.science.ru.nl/hubs/veenstralab/trackhubs_public/mus.musculus/hub.txt
xenopus: https://trackhub.science.ru.nl/hubs/veenstralab/trackhubs_public/xenopus/hub.txt
 - xLav91
 - xt7_1
 - xt8_0
 - xt9_0

### Track hub instructions

1. Clone/Download this github repository to a web-accesible folder
2. Visit the UCSC genome browser 
3. Click the button "track hubs"
4. Select the tab "My Hubs"
5. Copy-paste the URL to your species specic hub.txt file into the text box (I.e., https://mbdata.science.ru.nl/{username}/trackhubs_internal/species/mmu/hub.txt
6. Click "Add Hub"
7. The newly added trackhub and its corresponding genome should be the default in the Genome Browser Gateway (home) page of the UCSC browser.
8. If the track hub is not selected, or to select the trackhub again among previously loaded trackhubs: In the genome browser, click the top menu item "Genomes" to go to the Genome Browser Gateway page. To the left, under "Represented speces" the track hub "G.J.Veenstra mm10 trackhub" should be listed. Click it to select the trackhub.
9. Click "Go" to move to a position in the genome.
10. Browse the genome or modify track settings (right click on the track, or use track controls under main graphic) 

### Contributing guidelines
1. Fork this repository
2. Add your modification and commit changes to your fork
3. Submit a pull request

### Resource files ###
Place all your large data files (bed, bigwig, ix etc). in a web-accesible location under the corresponding genome assembly. 


### Adding new trackhub records ###
A new trackhub record should have the file hierachy below.

**{species}**
- genomes.txt
- hub.txt
 - **{assembly_id}**
    - trackDB.txt, 
    - annotation.txt etc.

In case you want to add multiple species from the same genus, add your trackhub within a folder with the genus name.

**{genus}**

**{species 1}**
- genomes.txt
- hub.txt
 - **{assembly_id}**
    - trackDB.txt, 
    - annotation.txt etc.
    - 
**{species 2}**
- genomes.txt
- hub.txt
 - **{assembly_id}**
    - trackDB.txt, 
    - annotation.txt etc.





