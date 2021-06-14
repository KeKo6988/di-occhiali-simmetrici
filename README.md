
2021-06-14T19:18:03.9652144Z ##[section]Inizio: Richiedi un corridore per eseguire questo lavoro
2021-06-14T19:18:05.2824666Z Impossibile trovare alcun runner self-hosted online e inattivo nel repository corrente che corrisponda alle etichette richieste: 'ubuntu-latest'
2021-06-14T19:18:05.3061407Z Impossibile trovare alcun corridore self-hosted online e inattivo nell'account dell'organizzazione del repository corrente che corrisponda alle etichette richieste: 'ubuntu-latest'
2021-06-14T19:18:05.3678713Z Impossibile trovare alcun corridore ospitato online e inattivo nell'account dell'organizzazione del repository corrente che corrisponda alle etichette richieste: 'ubuntu-latest'
2021-06-14T19:18:05.3678849Z Trovati corridori ospitati online e occupati nell'account dell'organizzazione del repository corrente che corrisponde alle etichette richieste: 'ubuntu-latest'. Raggiungi i limiti di concorrenza su un corridore ospitato. In attesa che uno di loro venga assegnato a questo lavoro.
2021-06-14T19:18:05.5803533Z ##[section]Finitura: Richiedi un corridore per eseguire questo lavoro
2021-06-14T19:19:15.8438524Z Versione corrente del corridore: '2.278.0'
2021-06-14T19:19:15.8463000Z ##[gruppo]Sistema operativo
2021-06-14T19:19:15.8463825Z Ubuntu
2021-06-14T19:19:15.8464281Z 20.04.2
2021-06-14T19:19:15.8464672Z LTS
2021-06-14T19:19:15.8465170Z ##[gruppo finale]
2021-06-14T19:19:15.8465697Z ##[gruppo]Ambiente virtuale
2021-06-14T19:19:15.8466328Z Ambiente: ubuntu-20.04
2021-06-14T19:19:15.8466834Z Versione: 20210606.1
2021-06-14T19:19:15.8467823Z Software incluso: https://github.com/actions/virtual-environments/blob/ubuntu20/20210606.1/images/linux/Ubuntu2004-README.md
2021-06-14T19:19:15.8469176Z Rilascio dell'immagine: https://github.com/actions/virtual-environments/releases/tag/ubuntu20%2F20210606.1
2021-06-14T19:19:15.8469984Z ##[gruppo finale]
2021-06-14T19:19:15.8471797Z ##[group]GITHUB_TOKEN Autorizzazioni
2021-06-14T19:19:15.8472993Z Azioni: scrivere
2021-06-14T19:19:15.8473460Z Controlli: scrivere
2021-06-14T19:19:15.8474003Z Contenuto: scrivere
2021-06-14T19:19:15.8474493Z Distribuzioni: scrivere
2021-06-14T19:19:15.8475113Z Discussioni: scrivere
2021-06-14T19:19:15.8475651Z Problemi: scrivere
2021-06-14T19:19:15.8476181Z Metadati: leggi
2021-06-14T19:19:15.8476651Z Pacchetti: scrivere
2021-06-14T19:19:15.8477200Z PullRequests: scrivere
2021-06-14T19:19:15.8477781Z RepositoryProjects: scrivere
2021-06-14T19:19:15.8478425Z SecurityEvents: scrivi
2021-06-14T19:19:15.8478946Z Stati: scrivere
2021-06-14T19:19:15.8479616Z ##[gruppo finale]
2021-06-14T19:19:15.8482331Z Preparare la directory del flusso di lavoro
2021-06-14T19:19:15.9391630Z Preparare tutte le azioni richieste
2021-06-14T19:19:15.9401736Z Ottenere informazioni sul download dell'azione
2021-06-14T19:19:16.3558626Z Scarica il repository di azioni 'actions/setup-node@v2'
2021-06-14T19:19:18.0675666Z Scarica il repository di azioni 'actions/setup-python@v2'
2021-06-14T19:19:18.1984967Z Scarica il repository di azioni 'actions/checkout@v2'
2021-06-14T19:19:18.4350850Z ##[group]Esegui azioni/setup-node@v2
2021-06-14T19:19:18.4351485Z con:
2021-06-14T19:19:18.4351900Z versione nodo: 14.x
2021-06-14T19:19:18.4352372Z check-ultimo: vero
2021-06-14T19:19:18.4352836Z sempre-auth: falso
2021-06-14T19:19:18.4353715Z token: ***
2021-06-14T19:19:18.4354087Z env:
2021-06-14T19:19:18.4354480Z MYTHX_API_KEY: 
2021-06-14T19:19:18.4354900Z ##[gruppo finale]
2021-06-14T19:19:18.8775663Z Tentativo di risolvere l'ultima versione dal manifest...
2021-06-14T19:19:18.8798039Z Risolto come '14.17.0'
2021-06-14T19:19:18.8799034Z Trovato nella cache @ /opt/hostedtoolcache/node/14.17.0/x64
2021-06-14T19:19:18.8952766Z ##[group]Esegui azioni/setup-python@v2
2021-06-14T19:19:18.8953275Z con:
2021-06-14T19:19:18.8953733Z versione Python: 3.8
2021-06-14T19:19:18.8954603Z token: ***
2021-06-14T19:19:18.8955007Z env:
2021-06-14T19:19:18.8955406Z MYTHX_API_KEY: 
2021-06-14T19:19:18.8955841Z ##[gruppo finale]
2021-06-14T19:19:18.9512165Z Configurazione riuscita di CPython (3.8.10)
2021-06-14T19:19:18.9549975Z ##[group]Esegui python -m pip install mythx-cli
2021-06-14T19:19:18.9550740Z ?[36;1mpython -m pip install mythx-cli?[0m
2021-06-14T19:19:18.9593327Z shell: /usr/bin/bash -e {0}
2021-06-14T19:19:18.9593785Z env:
2021-06-14T19:19:18.9594203Z MYTHX_API_KEY: 
2021-06-14T19:19:18.9594808Z pythonPosizione: /opt/hostedtoolcache/Python/3.8.10/x64
2021-06-14T19:19:18.9595539Z LD_LIBRARY_PATH: /opt/hostedtoolcache/Python/3.8.10/x64/lib
2021-06-14T19:19:18.9596109Z ##[gruppo finale]
2021-06-14T19:19:21.1206478Z Collezionando Mytx-Cli
2021-06-14T19:19:21.2084157Z Download di mythx_cli-0.6.22-py2.py3-none-any.whl (48 kB)
2021-06-14T19:19:21.2459072Z Raccolta di htmlmin==0.1.12
2021-06-14T19:19:21.2560415Z Download di htmlmin-0.1.12.tar.gz (19 kB)
2021-06-14T19:19:22.2445511Z Raccolta di pythx==1.6.1
2021-06-14T19:19:22.2592122Z Download di pythx-1.6.1-py2.py3-none-any.whl (39 kB)
2021-06-14T19:19:22.2968568Z Raccolta Jinja2==2.11.2
2021-06-14T19:19:22.3092252Z Download di Jinja2-2.11.2-py2.py3-none-any.whl (125 kB)
2021-06-14T19:19:22.3537271Z Raccolta tabulato==0.8.7
2021-06-14T19:19:22.3633873Z Download tabulate-0.8.7-py3-none-any.whl (24 kB)
2021-06-14T19:19:22.4075481Z Raccolta di py-solc-x==1.0.0
2021-06-14T19:19:22.4172036Z Download di py_solc_x-1.0.0-py3-none-any.whl (15 kB)
2021-06-14T19:19:22.4680280Z Clic di raccolta==7.1.2
2021-06-14T19:19:22.4790838Z Download click-7.1.2-py2.py3-none-any.whl (82 kB)
2021-06-14T19:19:22.5656861Z Raccolta PyYAML==5.3.1
2021-06-14T19:19:22.5765906Z Download di PyYAML-5.3.1.tar.gz (269 kB)
2021-06-14T19:19:23.0273216Z Raccolta MarkupSafe>=0.23
2021-06-14T19:19:23.0430809Z Download di MarkupSafe-2.0.1-cp38-cp38-manylinux2010_x86_64.whl (30 kB)
2021-06-14T19:19:23.1199211Z Raccolta richieste<3,>=2.19.0
2021-06-14T19:19:23.1296168Z Download delle richieste-2.25.1-py2.py3-none-any.whl (61 kB)
2021-06-14T19:19:23.1633232Z Raccolta della versione semantica<3,>=2.8.1
2021-06-14T19:19:23.1719258Z Download semantic_version-2.8.5-py2.py3-none-any.whl (15 kB)
2021-06-14T19:19:23.2254266Z Raccolta di PyJWT<1.8.0,>=1.7.0
2021-06-14T19:19:23.2348161Z Download di PyJWT-1.7.1-py2.py3-none-any.whl (18 kB)
2021-06-14T19:19:23.2560462Z Raccolta di inflessione==0.5,0
2021-06-14T19:19:23.2661336Z Download inflessione-0.5.0-py2.py3-none-any.whl (5.8 kB)
2021-06-14T19:19:23.3196658Z Collezionare modelli miti==1.9.1
2021-06-14T19:19:23.3299777Z Download di mythx_models-1.9.1-py2.py3-none-any.whl (82 kB)
2021-06-14T19:19:23.3646065Z Raccolta di python-dateutil<2.9.0,>=2.8.0
2021-06-14T19:19:23.3741027Z Download di python_dateutil-2.8.1-py2.py3-none-any.whl (227 kB)
2021-06-14T19:19:23.4479799Z Raccolta jsonschema<4.0.0
2021-06-14T19:19:23.4581817Z Download jsonschema-3.2.0-py2.py3-none-any.whl (56 kB)
2021-06-14T19:19:23.4932663Z Raccolta di sei>=1.5
2021-06-14T19:19:23.5022394Z Download di six-1.16.0-py2.py3-none-any.whl (11 kB)
2021-06-14T19:19:23.5568537Z Raccolta pyrsistent>=0.14.0
2021-06-14T19:19:23.5665578Z Download di pyrsistent-0.17.3.tar.gz (106 kB)
2021-06-14T19:19:23.7891901Z Requisito già soddisfatto: setuptools in /opt/hostedtoolcache/Python/3.8.10/x64/lib/python3.8/site-packages (da jsonschema<4.0.0->mythx-models ==1.9.1->pythx==1.6.1->mythx-cli) (56.0.0)
2021-06-14T19:19:23.8187161Z Raccolta attr>=17.4.0
2021-06-14T19:19:23.8301782Z Download attrs-21.2.0-py2.py3-none-any.whl (53 kB)
2021-06-14T19:19:24.5671388Z Raccolta idna<3,>=2.5
2021-06-14T19:19:24.5696175Z Download di idna-2.10-py2.py3-none-any.whl (58 kB)
2021-06-14T19:19:24.5697231Z Raccolta certifi>=2017.4.17
2021-06-14T19:19:24.5698461Z Download certifi-2021.5.30-py2.py3-none-any.whl (145 kB)
2021-06-14T19:19:24.5699476Z Raccolta di urllib3<1.27,>=1.21.1
2021-06-14T19:19:24.5700625Z Download di urllib3-1.26.5-py2.py3-none-any.whl (138 kB)
2021-06-14T19:19:24.5701584Z Raccolta charet<5,>=3.0.2
2021-06-14T19:19:24.5702724Z Download di charet-4.0.0-py2.py3-none-any.whl (178 kB)
2021-06-14T19:19:24.5704553Z Utilizzo di "setup.py install" legacy per htmlmin, poiché il pacchetto "wheel" non è installato.
2021-06-14T19:19:24.5706095Z Utilizzo di "setup.py install" legacy per PyYAML, poiché il pacchetto "wheel" non è installato.
2021-06-14T19:19:24.5707654Z Utilizzo di "setup.py install" legacy per pyrsistent, poiché il pacchetto "wheel" non è installato.
2021-06-14T19:19:24.5710560Z Installazione dei pacchetti raccolti: six, pyrsistent, attrs, urllib3, python-dateutil, jsonschema, inflection, idna, chardet, certifi, semantic-version, request, PyJWT, mythx-models, MarkupSafe, tabulate, PyYAML, pythx, py-solc-x, Jinja2, htmlmin, Click, mythx-cli
2021-06-14T19:19:24.5712504Z Esecuzione di setup.py install per pyrsistent: avviato
2021-06-14T19:19:25.7445724Z Esecuzione di setup.py install per pyrsistent: terminato con stato 'fatto'
2021-06-14T19:19:26.3637524Z Esecuzione di setup.py install per PyYAML: avviato
2021-06-14T19:19:26.7028283Z Esecuzione di setup.py install per PyYAML: terminato con stato 'fatto'
2021-06-14T19:19:26.8292860Z Esecuzione di setup.py install per htmlmin: avviato
2021-06-14T19:19:27.0662378Z Esecuzione di setup.py install per htmlmin: terminato con stato 'fatto'
2021-06-14T19:19:27.1579487Z Installazione riuscita Click-7.1.2 Jinja2-2.11.2 MarkupSafe-2.0.1 PyJWT-1.7.1 PyYAML-5.3.1 attrs-21.2.0 certifi-2021.5.30 charet-4.0 .0 htmlmin-0.1.12 idna-2.10 inflessione-0.5.0 jsonschema-3.2.0 mito-cli-0.6.22 mito-modelli-1.9.1 py-solc-x-1.0.0 pyrsistent-0.17.3 python- dateutil-2.8.1 pythx-1.6.1 request-2.25.1 semantic-version-2.8.5 six-1.16.0 tabulate-0.8.7 urllib3-1.26.5
2021-06-14T19:19:27.3647549Z ##[gruppo]Esegui python3 -V
2021-06-14T19:19:27.3648202Z ?[36;1mpython3 -V?[0m
2021-06-14T19:19:27.3648571Z ?[36;1mythx version?[0m
2021-06-14T19:19:27.3690126Z shell: /usr/bin/bash -e {0}
2021-06-14T19:19:27.3690497Z env:
2021-06-14T19:19:27.3690841Z MYTHX_API_KEY: 
2021-06-14T19:19:27.3691375Z pythonLocation: /opt/hostedtoolcache/Python/3.8.10/x64
2021-06-14T19:19:27.3692075Z LD_LIBRARY_PATH: /opt/hostedtoolcache/Python/3.8.10/x64/lib
2021-06-14T19:19:27.3692576Z ##[gruppo finale]
2021-06-14T19:19:27.3777908Z Python 3.8.10
2021-06-14T19:19:27.6316288Z Utilizzo: mitex [OPZIONI] COMANDO [ARGS]...
2021-06-14T19:19:27.6317090Z 
2021-06-14T19:19:27.6318738Z Errore: l'utente di prova è stato deprecato. Puoi comunque utilizzare la CLI di MythX gratuitamente registrandoti per un account gratuito su https://mythx.io/ e inserendo le tue credenziali di accesso.
2021-06-14T19:19:27.6591350Z ##[error]Processo completato con codice di uscita 2.
2021-06-14T19:19:27.6628397Z Ripulire i processi orfani


# SushiSwap

https://sushi.com/

## Deployed Contracts

https://dev.sushi.com/sushiswap/contracts

## Docs

[Development](docs/DEVELOPMENT.md)

[Deployment](docs/DEPLOYMENT.md)

[History](docs/HISTORY.md)

## Security

[Security Policy](SECURITY.md)

## License

[MIT](LICENSE.txt)
