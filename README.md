# rtc-javascript-standalone
Une page html avec d'un Javascript local qui charge les données du réseaux de transport RTC depuis leur [Open data](https://www.rtcquebec.ca/Default.aspx?tabid=192&language=en-CA) puis utilise une carte locale pour afficher les arrêts et itinéraires.

L'idée initial était de créer une application avec les technologies les plus simpes (Html et JS) pour afficher les horraires et les tracées depuis un simple navigateur ou une app webview.

Malheureusement, même si ce projet fonctionne très bien sous un samsung galaxy et plusieurs autres téléphones, l'application est trop lourde pour mon téléphone personnel. Le problème est le "pré-chargement" des données qui dépassent le maximum permis pour le processus Web sous Sailfish OS porté vers le moto g first Gen. Je tiens à ce que l'application ne dépendent pas d'un service externe ou une connexion internet.

La prochaine étape est une application native à SailfishOS avec une base de donnée locale afin d'éviter un "pré-chargement". La carte sera probablement fournie via le serveur [osmscout](https://github.com/rinigus/osmscout-server).

Je laisse ce projet ici si d'autres aimeraient le consulter.
