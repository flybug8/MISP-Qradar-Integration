<h1>MISP-QRADAR-REFERENCE-SET-BUILDER</h1>
Pulls IOCs from MISP and adds them to reference sets in QRadar</br>
I added compose file that builds container for each script.</br>
Credit to @derinsiderx on Twitter for the awesome new script ! </br>

<h2>Dependecies</h2>
python pip3</br>
cron</br>
docker</br>

<h3>Installation</h3>

```
 pip install -r requirements.txt
 docker compose up
```
 Be sure to edit compose file to your needs and replace < > fields with correct credentials
