html:<!DOCTYPE html>
<html lang="sv">
  <head>
    <meta charset="utf-8"/>
    <title>spel - Hemsida</title>
    <link rel="stylesheet" href="css/spel.css"/>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
  </head>

    <body class="startpage">
      <form action="/action_page.php">
        <div class="password">
          Email: <input type="text" name="email"><br>
          Password: <input type="password" name="pwd" maxlength="8"><br>
          <input type="submit">
        </div>
      </form>
      <header>

    <nav class="navbar">
  <ul class="navbar-nav" style="list-style-type:none">

    <li class="nav-item">
      <a class="nav-link" href="#">Musik</a>
    </li>

    <li class="nav-item">
      <a class="nav-link" href="file:///C:/Users/hugo.braatz/Documents/Webbutveckling/Slutprojekt/html/spel.html">spel &nbsp</a>
    </li>

    <li class="nav-item">
      <a class="nav-link" href="#">Film &nbsp</a>
    </li>

    <li class="nav-item">
      <a class="nav-link" href="file:///C:/Users/hugo.braatz/Documents/Webbutveckling/Slutprojekt/html/3col.html">Övrigt</a>
    </li>
  </ul>

</nav>
      </header>
      <div class="P5">

      </div>
      <div class="temp">
        <div class="hwrap">
          <p>&nbsp Persona 5 är ett JRPG (Japanese role playing game) spel som utspelas i Tokyo japan. Detta spelet handlar om &nbspen kille som har blivit ditsatt av en känd politiker och han tvingas att flytta från där han bodde då båda föräldrarna valde att han skulle bli bortskickad från familjen. “Jokern” som huvudkaraktären kallas skickas till yongen jaya där en person vid sojiro sakura ska ta hand om dig. sojiro sakura är en gammal man med ett litet cafe som serverar kaffe och curry och det är där du bor uppe på vinden av cafet.<br><br>
Jokern är runt 17-18 år och går andra året på gymnasiet och det är nu storyn blir svår att förklara men anledningen varför spelet är så bra. I spelet persona så lever du två liv en som en vanlig student och det andra livet är du en mästertjuv som kan ändra på folks hjärtan så dem berättar vad som har hänt.
Utan att spoila för mycket så är den första bossen idrottsläraren kamoshida som har vunnit massa matcher och turneringar i &nbsp volleyboll. kamoshida får vi reda på skadar killarna som ska spela och våldtar tjejerna eller iallafall några. Det går så långt att en tjej försökte ta livet av sig genom att hoppa av från ett tak det är då Jokern väljer att ändra hans hjärta.<br>

Budskapet bakom spelet är att vänner är det bästa man kan ha och att fler är bättre än en och hur viktigt vänskap är.<br>

&nbsp Persona 5 tar upp hur samhället fungerar då allting du gör har med samhället att göra då du lever som en vanlig person under halva spelet och upplever den japanska kulturen och samhället fungerar. vi får se hur en korrupt politiker använder sin makt för att förstöra för dem som inte håller med han. en idrottsstjärna som använder sin makt för att förstöra liv för unga elever för att han känner sig oslagbar. vi har en konstnär som tar målningar av hans studenter och även gör falska kopior av ett verk som han tog som sedan gjorde han känd. detta till slut avslutas med att du går emot “GUD”

          </p>
        </div>
      </div>
      <div class="Fallout">

      </div>
      <div class="temp">
        <div class="hwrap">
          <img class="Fallout" src="https://images.g2a.com/newlayout/600x351/1x1x0/7f04df747d8e/59e5fb145bafe3233e6ee122"
          <p>&nbsp 
Fallout 4

Fallout 4 tar plats i Boston, Massachusetts och i andra delar av New England - numera känt som The Commonwealth  i efterdyningen av ett kärnvapenkrig. Till skillnad från tidigare titlar börjar berättelsen i Fallout 4 innan kärnvapenkriget brutit ut. 23 oktober 2077 tar huvudpersonen skydd i ett skyddsvall med sin familj, då de får veta att kärnvapenkriget är på väg. 
200 år senare vaknar huvudpersonen upp och visar sig vara den enda överlevande personen i skyddsvalvet
Hans son har blivit kidnappad av Raders
och du ska ge dig ut för att försöka hitta honom
han går flera mil för att hitta han
enligt mig är budskapet att familjen är det bästa du kan ha och att familjer kommer gå så långt dom bara kan för att bli tillsammans igen
du tror att det bara har gått ett par år men det har gått så mycket mer än så
(Spoiler) när du hitta din son så är han en gammal man han är äldre än dig om du inte ändrar din gubbe i början av spelet så kommer din son att var väldigt lik dig (enligt mig)

Spelet blir mycket roligare med mods
man kan gå vart man vill i hela spelet.
man kan göra sin gubbe så han/hon ser ut hur dom vill.
Storien är 1/10 enligt mig är alla andra Fallout bättre när det gäller story
Solo gameplay,<br><br>


Genre: Äventyr, Action
          </p>
        </div>
      </div>
    </body>
</html>


CSS:@charset "UTF-8";

html
{
    /* margin: 2%; */
    background: url(https://scontent-arn2-1.xx.fbcdn.net/v/t1.0-9/54417778_845289462477402_6753731365952290816_n.jpg?_nc_cat=106&_nc_ht=scontent-arn2-1.xx&oh=50887a540451f0d47b49ae337fb8e407&oe=5D07201A);
    background-size: auto;
}

body
{
  font-family: "Helvetica Neue", "Liberation Sans", Calibri, Arial, sans-serif;
  margin: auto;
  font-family: sans-serif;
  font-size: 100%;
  /* background-color: white; */
}
.hwrap
{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  /* justify-content: center; */
}


  header
  {
    text-align: center;
    color: white;
  }
  .temp
  {
    text-align: center;
    color: white;
    outline-style: outset;
    outline-color: white;
    outline-width: 5px;
    background-color: black;
    width: 800px;
    margin: 30px auto;
  }

  .startpage .logo
  {
    width: auto;
    height: auto;
  }

.navbar
{
  display: flex;
  width: auto;
}
ul
{
  display: flex;
   margin: auto;
}
li
{
  margin: 30px;
}

form
{
  float: right;
  align-items: center;
  justify-content: center;
  margin-right: 0px;
}
.password
{
  width: auto;
  height: auto;
}

.nav-item
{
  outline-style: outset;
  outline-color: white;
  outline-width: 5px;
  font-size: 36px;
}
.nav-link
{
  color: white;
  background-color: black;
}
a:hover {
  color: #FF0066;
}

.P5
{
  display: flex;
  margin-left: 600px;
  margin-right: 600px;
  width: 220px;
  height: 312px;
  background: url(https://upload.wikimedia.org/wikipedia/en/thumb/b/b0/Persona_5_cover_art.jpg/220px-Persona_5_cover_art.jpg)
}

.Fallout
{
  display: flex;
  margin-left: 0px;
  margin-right: 0px;
  width: 600px;
  height: 351px;
}


