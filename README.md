Aide de claude ai pour 
"if($choix === "1")
    {
        require "templates/partials/choix1.phtml";
    }
    elseif($choix === "2")
    {
        require "templates/partials/choix2.phtml";
    }
    elseif($choix === "3")
    {
        require "templates/partials/choix3.phtml";
    }
    else{
   ?>" Prompt: Aide a faire en sorte que le contenu de ma page choix ne s'affiche plus en dessous de ma page d'accueil


   "Warning: Undefined array key "choix" in C:\xampp\htdocs\PHP\coda-php-projet-heros\templates\partials\_main.phtml" Ligne de code donnée par claude pour corriger le warning: 
   "$choix = $_GET['choix'] ?? null;"
    