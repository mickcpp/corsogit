# corsogit

#### Inizializzare una repository Git:</h4>
git init

#### Clonare una repository esistente:
git clone <URL_del_repository>

#### Aggiungere file alla staging area:
git add <nome_file>

#### Aggiungere tutti i file modificati alla staging area:
git add .

#### Eseguire un commit:
git commit -m "Messaggio del commit" (opzionale -m "dettagli")

#### Visualizzare lo stato dei file nella repository:
git status

#### Visualizzare la cronologia dei commit:
git log

#### Creare un nuovo branch:
git branch <nome_branch>

#### Passare a un branch specifico:
git checkout <nome_branch>

#### Creare e passare a un nuovo branch in un solo comando:
git checkout -b <nome_branch>

#### Unire i cambiamenti da un branch a un altro:
git merge <nome_branch>

#### Scaricare i cambiamenti dalla repository remota:
git pull origin <nome_branch>

#### Caricare i cambiamenti alla repository remota:
git push origin <nome_branch>

#### Clonare un branch remoto in un nuovo branch locale:
git checkout -b <nome_branch_locale> origin/<nome_branch_remoto>

#### Configurare credenziali:
- git config --global user.email "email"
- git config --global user.name "name"
- (si puo eseguire anche come local togliendo l'opzione global)*

#### Fare l'unstage degli ultimi file aggiunti:
git reset

#### Tornare indietro di un commit:
git reset HEAD~1

#### Tornare a uno specifico commit:
git reset <hash_commit>

#### Eseguire il restore di un file per visualizzare il codice corretto in locale (essenzialmente un restore allo stato dell'ultimo commit):
git restore <file_name>

#### Eseguire il restore di tutti i file:
git restore .

#### Collegare il repository remoto: Specificare il repository remoto con il quale desideri sincronizzare.
git remote add origin <URL_del_repo>

#### Sincronizzare con il repository remoto: Caricare i commit locali sul repository remoto.
git push origin <nome_branch>

#### Visualizzare le modifiche apportate a un file:
git diff <nome_file>
