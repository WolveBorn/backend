                          # Backend College 1.1 (titus)

### Het vak
Het vak heeft 2 toetsing momenten.
 - Digitale toets (March 26 or 27)
 - Mondeling (April 9, 10, 12)

 je kunt 3 studiepunten krijgen.

### Communicatie
GitHub: Overview, examples, assignments, classes
Slack: Questions, answers, chat, updates
Moodle: Test, schedulers

### Tips
 - Werk hard
 - Weinig contact uren, dus veel zelf.
 - Lees de handleiding
 - Vraag en help andere op Slack
 - Maak kleine stapjes
 - Zet door!



                          # Project Tech korte intro College 1.0

Mijn coach: Albert de Klein.

### De opdracht
Ontwerp en bouw een prototype (Front- en Backend) dating site voor serieuze relaties
(HTML/CSS/JavaScript/Node.js/MySQL/MongoDB)

Technische eisen:
-
-
-

Tips:
 - Doe onderzoek naar andere dating sites.
 - Hou wekelijks je procesboek bij.
 - Besteed 2 dagen per week aan dit project.

### Verplichtingen
 - Drie maal je iteratie laten zien.
 - Twee maal verplicht voortgangs gesprek. (Testplan van te voren inleveren.)
 - Consciou Geek (Moodle)

### Opleveren
 - Werkend prototype
 - Procesboek
 - Licht je ontwerpkeuzes en iteraties toe en onderbouw deze.



                          # Backend College 1.2 (titus)

### Commandline

  Een Commandline is een interface gebasseert op text

  Servers hebben vaak geen visuele maar een text interface

  Een programma dat deze interface verwerkt heet een shell
  (Shell is hetgene waar je tegen praat.)

[~]$ rm -f foo.txt
 - [~]$           = Prompt                        (??)
 - rm             = Command                       (De opdracht, in dit geval verwijder/remove.)
 - -f             = Option                        (??)
 - foo.txt        = Arguments                     (Het bestaand waar je het op uitvoerd.)

### Navigeren/elementen

 - pwd            = Print working directory       (Print uit waar in het bestand je zit.)
 - ls             = list                          (Geeft een lijst met wat er in de map zit.)
 - ls -a          = list alles                    (Geeft een lijst met echt ALLES wat er in de map zit.)
 - .              = huidige map
 - ..             = mapje terug
 - ls -l          = uitgebreide lijst             (Geeft dezelde lijst maar dan met meer informatie)
 - cd _           = Change directory              (Gaat naar de map of locatie die je na de 'cd' zet.)
 - cd ../../_     = Mapjes terug                  (Zo ga je naar een locatie in een eerder mapje (2 mapjes terug))
 - cd ~           = ??                            (??)
 - touch          = maak document                 (??)
 - mkdir _        = maak map                      (Dit maakt een map aan.)
 - rm _           = remove                        (Verwijderd het erna genoemde document.)
 - rm -r _        = remove map                    (Verwijderd het genoemde mapje.)
 - mv _ _         = move                          (renaming)
 - cp _           = copy                          (??)
 - cat _          = print/lees                    (leest het erna genoemde bestand.)
 - clear          = cleart scherm                 (cmd+k of ctrl + k)
 - echo "text"    = print "text"
 - X = "Hi"       = variabele                     (Creeërd variabele X)
 - $X             = aanroep variabele             (bv: echo "$X Wouter" --> "Hi Wouter")
 - _ > _          = verplaatsen/toevoegen         (bv: echo "Sup Hombre" > message.txt --> zorgt dat de text "Sup Hombre" in het bestand message.txt komt te staan.)
 - _ >> _         = later toevoegen               (Voegt het later in het bestand toe, dus onder "Sup Hombre".)
 - curl *site*    = gaat naar site                (Haalt data van het gegeven webadres op.)
 - less /././     = interactief lezen             (Lees het opgegeven bestand.)
 - :q!            = exit
 - :qa!           = exit and dont save
 - vim /././      = editor                        (Nu kun je in het bestand schrijven.)
 - man _          = Manual                        (Geeft uitleg over het gevraagde element.)
 - sudo           = Hackerman                     (Wanneer iets niet mag, overwriten met admin mode.) (just dont)


### Tips:

 Maak een back up van je pc
 Werk in dropbox
 Gebruik alleen lage letters en _ in je benamingen.
 GEEN SPATIES IN NAMEN!


### Git

  Git slaat veranderingen op.
  Zorgt er ook voor dat je samen in 1 bestand kunt werken.


#### Git Commandline
  - git init                  = Create repository
  - git status                = Current state
  - git add (new)             = Track file
  - git add (existing)        = Stage file
  - git commit -m "string"    = commit with a message with what you changed
  - git log                   = Show progress (logboek)
  - git remote add origin     = Legt de link met de offline en online branch (zelfde branch alleen off en on)
  - git push -u origin master = Pushed offline branch naar online branch (later git push)
  - git push                  = Pushed naar GitHub na 1 keer ^ gebruikt te hebben.
  - git pull origin master    = Pulled online branch naar je offline branches.
  - git pull                  = Pull van GitHub na 1 keer ^ gebruikt te hebben.
  - git diff HEAD             = Shows what is different since our last commit. use HEAD for most recent commit.
  - git diff --staged         = See the changes you just staged
  - git reset                 = Unstage files
  - git checkout -- _         = Changes the file back since to the state of the last commit.

  -    '*.txt'                = Verwijder alle .txt bestanden ( * = alles)


#### Git Branch

  - git branch _              = Create a branch

  - git checkout -b _         = Create a branch
  - git checkout _            = Switch to a branch
  - git branch                = Show branches
  - git merge _               = Apply changes
  - git branch -d _           = Remove a branch

  - -m    --message           = Comment
  - -d    --delete            = Remove
  - -b    --b                 =



### GitHub

  GitHub is een sociaal platform geformd rondom Git.
  Een sociaal platform voor nerds, hoe ironisch.

  ==Tabs==
  Issues          : voor bugs, vragen en problemen.
  Pull requests   : voor features en fixes.



  #Markdown


  De taal waarin readme.md geschreven word.

  #### Heading&list

  # level 1 heading
  ## level 2 heading
  ### level 3 heading
  #### level 4 heading
  ##### level 5 heading
  ###### level 4 heading

  A normal paragraph

  * An
  * Unordered
  * List

  1. An
  2. Ordered
  3. List


  #### Blockquote&code

  A paragraph

  > A block quote

  Another paragraph

  ```js
  and.aBit({of: 'JavaScript'});
  ```


  #### Inline

  A paragraph with *italics*, **bold face**, **_bold italic_** and `inlineCode()`.


  A [link](http://example.com).


  And an ![image](http://example.com/image.png).



  Do you want to [see something fun][a fun place]?

  Well, do I have [the website for you][another fun place]!

  [a fun place]: www.zombo.com
  [another fun place]: www.stumbleupon.com


  ![The first father][First Father]
  ![The second first father][Second Father]

  [First Father]: http://octodex.github.com/images/founding-father.jpg
  [Second Father]: http://octodex.github.com/images/foundingfather_v2.png


  Twee spaties zorgen dat je een nieuwe regel begint zonder wit ruimte.
