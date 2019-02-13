                                  ### --- MVC, PHP --- ###
 ###Lektion 1:
 
-Jag kom på en idee.

-Min idee är strukturera en PHP kod som jag skrev med Rickhard.

-Vi skrev PHP,CSS,JAVASCRIPT och HTML kod i samma fil, min ide är strukturera koden och dela koden i olika filer.

-Jag ska skriva allt CSS kod i ett CSS fil, allt HTML kod i ett TPL fil, allt PHP kod i ett PHP fil och allt JAVASCRIPT kod i ett JS fil.

-På min gamla PHP kod databas koplingen log i i index filen. Jag ska skappa ny fil som heter db.php och skriva databas kopplingen i db.php.

###Lektion 2:

-Jag började med min projekt genom att skappa nya filer.

      Filernas namn:
       * register.php
       * login.php
       * db.php
       * error.php
       * style.css
       
-Sedan gjorde jag resource på internet, hur man kan skriva ett ren php kod och hur man delar koden i olika filer/PHP/HTML/CSS.

-Jag skrev allt PHP kod i den filen som jag skapade och den filen heter db.php.

-Jag skrev register formulären i register.php filen. 

-Loga in formulären skrev jag i login.php filen.

-En validering ligger i error filen, det validerar formuläret.  Till exempel; när man lämnar en e-post,namn osv då kommer en varning
att man har lämnat inputen tom eller skrev fel.

###Lektion 3:

-På tredije lektionen kunde jag inte jobba med min MVC, PHP projekt för att jag fick ett arbetsprov från min praktikplats och jag var
tvungen och klara den inom en vecka för att få en praktikplats.

###Lektion 4:

-Jag kunde inte komma till skolan på fjärde lektionen på grund av jag var sjuk, och jag kunde inte jobba mycket med min uppgift.
Men jag jobbade lite med min uppgift annandag när jag började bli lite frisk. 

-Min kod hade några error, det fungerade men när man körde koden då dykte upp lite error. Jag försökte fixa de errorna hemma.

-Det var så lätt fixa errorna som jag fick på min kod, Det tog flera timmar och fixa några av errorna genom googla. Jag kunde inte 
fixa alla errorna. Jag hade fortfarande några error kvar i min kod.

-Jag lärde mig en viktig sak på Tillämpadprogrammering(Magnus) kursen; om man har ett fel och kan inte lösa det felet då ska man inte 
flura tid på det. Man ska be om hjälp istället, och det gjorde jag genom fråga min lärare (Magnus). Det tog bara 1 minut fixa hela
errorna. 

-Den metoden som jag lärde mig med (Magnus) hjälpte mig väldigt mycket, om man inte kan lösa en error på flera timmar så är det ingen
mening att slösa din tid på det om du inte kan hitta lösning så ska man begära om hjälp.

###Lektion 5:

-Jag hade en problem som jag inte kunde lösa. Problemet: När jag registrerade mig det sparades i databasen och loggade in men jag ville
användnamnet ska dyka upp. Men användarnamnet dykte inte upp. Jag bad hjälp om hjälp av min lärare(Magnus) och vi löste problemet
tillsammans.

                              ###--- Fel sätt ---### [ Jag hade skrivit så ]
                             
                             $_SESSION['$_GET(firstname')] = $firstname;
                             $_SESSION['success'] = 'Nu är du inloggad';

                             ###--- Rätt sätt ---### [ Jag har rättat koden hjälp av min lärare. ]
                             
                             $_SESSION['firstname'] = $firstname;
                             $_SESSION['success'] = 'Nu är du inloggad';
                             
-Jag har staylat mina formulärt med CSS och allt CSS kod ligger i CSS filen. Jag har inte lagt så mycket tid på styleningen, jag tyckte
att funktionalitet är viktigare och fokuserat mest på funktionen.

                          ### Skillnaden mellan min strukturerad kod och min gamla ostrukturerad kod ###
                          
![1](https://user-images.githubusercontent.com/39722976/52724601-f48a5700-2faf-11e9-8c26-74c9340d92a7.png)
