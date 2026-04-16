<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Random Soccer Player Generator</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: white;
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .container {
      background: rgba(255, 255, 255, 0.08);
      padding: 30px;
      border-radius: 20px;
      width: 90%;
      max-width: 700px;
      text-align: center;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
    }

    h1 {
      margin-bottom: 10px;
      font-size: 2rem;
    }

    p {
      color: #cbd5e1;
      margin-bottom: 20px;
    }

    button {
      background: #22c55e;
      color: white;
      border: none;
      padding: 12px 24px;
      font-size: 1rem;
      border-radius: 10px;
      cursor: pointer;
      margin-top: 10px;
    }

    button:hover {
      background: #16a34a;
    }

    .player-card {
      margin-top: 25px;
      padding: 20px;
      background: rgba(255, 255, 255, 0.08);
      border-radius: 15px;
      text-align: left;
    }

    .player-card h2 {
      margin: 0 0 15px 0;
      font-size: 1.8rem;
      text-align: center;
    }

    .player-card div {
      margin: 10px 0;
      font-size: 1.05rem;
    }

    .label {
      font-weight: bold;
      color: #86efac;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Random Soccer Player Generator</h1>
    <p>Click the button to get a random soccer player from any era.</p>
    <button onclick="generatePlayer()">Generate Player</button>

    <div class="player-card" id="playerCard" style="display: none;">
      <h2 id="playerName"></h2>
      <div><span class="label">Country:</span> <span id="playerCountry"></span></div>
      <div><span class="label">Position:</span> <span id="playerPosition"></span></div>
      <div><span class="label">Era:</span> <span id="playerEra"></span></div>
      <div><span class="label">Notable Club:</span> <span id="playerClub"></span></div>
    </div>
  </div>

  <script>
    const players = [
      { name: "Pelé", country: "Brazil", position: "Forward", era: "1950s-1970s", club: "Santos" },
      { name: "Diego Maradona", country: "Argentina", position: "Attacking Midfielder", era: "1970s-1990s", club: "Napoli" },
      { name: "Johan Cruyff", country: "Netherlands", position: "Forward", era: "1960s-1980s", club: "Ajax" },
      { name: "Franz Beckenbauer", country: "Germany", position: "Sweeper", era: "1960s-1980s", club: "Bayern Munich" },
      { name: "George Best", country: "Northern Ireland", position: "Winger", era: "1960s-1980s", club: "Manchester United" },
      { name: "Bobby Charlton", country: "England", position: "Midfielder", era: "1950s-1970s", club: "Manchester United" },
      { name: "Eusébio", country: "Portugal", position: "Forward", era: "1960s-1970s", club: "Benfica" },
      { name: "Lev Yashin", country: "Soviet Union", position: "Goalkeeper", era: "1950s-1970s", club: "Dynamo Moscow" },
      { name: "Garrincha", country: "Brazil", position: "Winger", era: "1950s-1960s", club: "Botafogo" },
      { name: "Ferenc Puskás", country: "Hungary", position: "Forward", era: "1940s-1960s", club: "Real Madrid" },
      { name: "Alfredo Di Stéfano", country: "Argentina", position: "Forward", era: "1940s-1960s", club: "Real Madrid" },
      { name: "Gerd Müller", country: "Germany", position: "Striker", era: "1960s-1980s", club: "Bayern Munich" },
      { name: "Paolo Rossi", country: "Italy", position: "Striker", era: "1970s-1980s", club: "Juventus" },
      { name: "Zico", country: "Brazil", position: "Attacking Midfielder", era: "1970s-1990s", club: "Flamengo" },
      { name: "Socrates", country: "Brazil", position: "Midfielder", era: "1970s-1980s", club: "Corinthians" },
      { name: "Michel Platini", country: "France", position: "Midfielder", era: "1970s-1980s", club: "Juventus" },
      { name: "Marco van Basten", country: "Netherlands", position: "Striker", era: "1980s-1990s", club: "AC Milan" },
      { name: "Ruud Gullit", country: "Netherlands", position: "Midfielder", era: "1980s-1990s", club: "AC Milan" },
      { name: "Frank Rijkaard", country: "Netherlands", position: "Defensive Midfielder", era: "1980s-1990s", club: "AC Milan" },
      { name: "Lothar Matthäus", country: "Germany", position: "Midfielder", era: "1980s-2000s", club: "Bayern Munich" },
      { name: "Roberto Baggio", country: "Italy", position: "Attacking Midfielder", era: "1980s-2000s", club: "Juventus" },
      { name: "Franco Baresi", country: "Italy", position: "Defender", era: "1970s-1990s", club: "AC Milan" },
      { name: "Paolo Maldini", country: "Italy", position: "Defender", era: "1980s-2000s", club: "AC Milan" },
      { name: "Romário", country: "Brazil", position: "Striker", era: "1980s-2000s", club: "Vasco da Gama" },
      { name: "Hristo Stoichkov", country: "Bulgaria", position: "Forward", era: "1980s-2000s", club: "Barcelona" },
      { name: "Rivaldo", country: "Brazil", position: "Attacking Midfielder", era: "1990s-2010s", club: "Barcelona" },
      { name: "Roberto Carlos", country: "Brazil", position: "Left Back", era: "1990s-2010s", club: "Real Madrid" },
      { name: "Cafu", country: "Brazil", position: "Right Back", era: "1990s-2010s", club: "AC Milan" },
      { name: "Ronaldo Nazário", country: "Brazil", position: "Striker", era: "1990s-2010s", club: "Real Madrid" },
      { name: "Zinedine Zidane", country: "France", position: "Midfielder", era: "1990s-2000s", club: "Real Madrid" },
      { name: "Thierry Henry", country: "France", position: "Forward", era: "1990s-2010s", club: "Arsenal" },
      { name: "Patrick Vieira", country: "France", position: "Midfielder", era: "1990s-2010s", club: "Arsenal" },
      { name: "Claude Makélélé", country: "France", position: "Defensive Midfielder", era: "1990s-2010s", club: "Chelsea" },
      { name: "Dennis Bergkamp", country: "Netherlands", position: "Forward", era: "1980s-2000s", club: "Arsenal" },
      { name: "Edgar Davids", country: "Netherlands", position: "Midfielder", era: "1990s-2000s", club: "Juventus" },
      { name: "Clarence Seedorf", country: "Netherlands", position: "Midfielder", era: "1990s-2010s", club: "AC Milan" },
      { name: "Ruud van Nistelrooy", country: "Netherlands", position: "Striker", era: "1990s-2010s", club: "Manchester United" },
      { name: "Andriy Shevchenko", country: "Ukraine", position: "Striker", era: "1990s-2010s", club: "AC Milan" },
      { name: "Andrea Pirlo", country: "Italy", position: "Midfielder", era: "1990s-2010s", club: "AC Milan" },
      { name: "Alessandro Del Piero", country: "Italy", position: "Forward", era: "1990s-2010s", club: "Juventus" },
      { name: "Francesco Totti", country: "Italy", position: "Forward", era: "1990s-2010s", club: "Roma" },
      { name: "Gianluigi Buffon", country: "Italy", position: "Goalkeeper", era: "1990s-2020s", club: "Juventus" },
      { name: "Fabio Cannavaro", country: "Italy", position: "Defender", era: "1990s-2010s", club: "Real Madrid" },
      { name: "Iker Casillas", country: "Spain", position: "Goalkeeper", era: "1990s-2020s", club: "Real Madrid" },
      { name: "Carles Puyol", country: "Spain", position: "Defender", era: "1990s-2010s", club: "Barcelona" },
      { name: "Xavi", country: "Spain", position: "Midfielder", era: "1990s-2010s", club: "Barcelona" },
      { name: "Andrés Iniesta", country: "Spain", position: "Midfielder", era: "2000s-2020s", club: "Barcelona" },
      { name: "David Villa", country: "Spain", position: "Striker", era: "2000s-2020s", club: "Valencia" },
      { name: "Fernando Torres", country: "Spain", position: "Striker", era: "2000s-2020s", club: "Liverpool" },
      { name: "Sergio Ramos", country: "Spain", position: "Defender", era: "2000s-2020s", club: "Real Madrid" },
      { name: "Sergio Busquets", country: "Spain", position: "Defensive Midfielder", era: "2000s-2020s", club: "Barcelona" },
      { name: "Cesc Fàbregas", country: "Spain", position: "Midfielder", era: "2000s-2020s", club: "Arsenal" },
      { name: "Lionel Messi", country: "Argentina", position: "Forward", era: "2000s-present", club: "Barcelona" },
      { name: "Cristiano Ronaldo", country: "Portugal", position: "Forward", era: "2000s-present", club: "Real Madrid" },
      { name: "Ronaldinho", country: "Brazil", position: "Attacking Midfielder", era: "1990s-2010s", club: "Barcelona" },
      { name: "Kaká", country: "Brazil", position: "Attacking Midfielder", era: "2000s-2010s", club: "AC Milan" },
      { name: "Neymar", country: "Brazil", position: "Forward", era: "2010s-present", club: "Barcelona" },
      { name: "Dani Alves", country: "Brazil", position: "Right Back", era: "2000s-2020s", club: "Barcelona" },
      { name: "Marcelo", country: "Brazil", position: "Left Back", era: "2000s-2020s", club: "Real Madrid" },
      { name: "Casemiro", country: "Brazil", position: "Defensive Midfielder", era: "2010s-present", club: "Real Madrid" },
      { name: "Rivaldo", country: "Brazil", position: "Attacking Midfielder", era: "1990s-2010s", club: "Barcelona" },
      { name: "Javier Zanetti", country: "Argentina", position: "Defender", era: "1990s-2010s", club: "Inter Milan" },
      { name: "Gabriel Batistuta", country: "Argentina", position: "Striker", era: "1990s-2000s", club: "Fiorentina" },
      { name: "Juan Román Riquelme", country: "Argentina", position: "Attacking Midfielder", era: "1990s-2010s", club: "Boca Juniors" },
      { name: "Carlos Tevez", country: "Argentina", position: "Forward", era: "2000s-2020s", club: "Boca Juniors" },
      { name: "Javier Mascherano", country: "Argentina", position: "Defensive Midfielder", era: "2000s-2020s", club: "Barcelona" },
      { name: "Ángel Di María", country: "Argentina", position: "Winger", era: "2000s-present", club: "Real Madrid" },
      { name: "Sergio Agüero", country: "Argentina", position: "Striker", era: "2000s-2020s", club: "Manchester City" },
      { name: "Lautaro Martínez", country: "Argentina", position: "Striker", era: "2010s-present", club: "Inter Milan" },
      { name: "Luka Modrić", country: "Croatia", position: "Midfielder", era: "2000s-present", club: "Real Madrid" },
      { name: "Ivan Rakitić", country: "Croatia", position: "Midfielder", era: "2000s-present", club: "Barcelona" },
      { name: "Davor Šuker", country: "Croatia", position: "Striker", era: "1980s-2000s", club: "Real Madrid" },
      { name: "Zvonimir Boban", country: "Croatia", position: "Midfielder", era: "1980s-2000s", club: "AC Milan" },
      { name: "Robert Lewandowski", country: "Poland", position: "Striker", era: "2000s-present", club: "Bayern Munich" },
      { name: "Grzegorz Lato", country: "Poland", position: "Winger", era: "1970s-1980s", club: "Stal Mielec" },
      { name: "George Weah", country: "Liberia", position: "Striker", era: "1980s-2000s", club: "AC Milan" },
      { name: "Didier Drogba", country: "Ivory Coast", position: "Striker", era: "2000s-2010s", club: "Chelsea" },
      { name: "Yaya Touré", country: "Ivory Coast", position: "Midfielder", era: "2000s-2020s", club: "Manchester City" },
      { name: "Samuel Eto'o", country: "Cameroon", position: "Striker", era: "1990s-2010s", club: "Barcelona" },
      { name: "Roger Milla", country: "Cameroon", position: "Forward", era: "1970s-1990s", club: "Montpellier" },
      { name: "Jay-Jay Okocha", country: "Nigeria", position: "Attacking Midfielder", era: "1990s-2000s", club: "Bolton Wanderers" },
      { name: "Nwankwo Kanu", country: "Nigeria", position: "Forward", era: "1990s-2010s", club: "Arsenal" },
      { name: "Mohamed Salah", country: "Egypt", position: "Forward", era: "2010s-present", club: "Liverpool" },
      { name: "Sadio Mané", country: "Senegal", position: "Forward", era: "2010s-present", club: "Liverpool" },
      { name: "Riyad Mahrez", country: "Algeria", position: "Winger", era: "2010s-present", club: "Manchester City" },
      { name: "Abedi Pelé", country: "Ghana", position: "Attacking Midfielder", era: "1980s-2000s", club: "Marseille" },
      { name: "Asamoah Gyan", country: "Ghana", position: "Striker", era: "2000s-2020s", club: "Al Ain" },
      { name: "Michael Essien", country: "Ghana", position: "Midfielder", era: "2000s-2010s", club: "Chelsea" },
      { name: "Park Ji-sung", country: "South Korea", position: "Midfielder", era: "2000s-2010s", club: "Manchester United" },
      { name: "Son Heung-min", country: "South Korea", position: "Forward", era: "2010s-present", club: "Tottenham Hotspur" },
      { name: "Shinji Kagawa", country: "Japan", position: "Attacking Midfielder", era: "2010s-2020s", club: "Borussia Dortmund" },
      { name: "Hidetoshi Nakata", country: "Japan", position: "Midfielder", era: "1990s-2000s", club: "Roma" },
      { name: "Cha Bum-kun", country: "South Korea", position: "Forward", era: "1970s-1980s", club: "Bayer Leverkusen" },
      { name: "Tim Cahill", country: "Australia", position: "Attacking Midfielder", era: "2000s-2010s", club: "Everton" },
      { name: "Harry Kewell", country: "Australia", position: "Winger", era: "1990s-2010s", club: "Leeds United" },
      { name: "Mark Viduka", country: "Australia", position: "Striker", era: "1990s-2010s", club: "Leeds United" },
      { name: "Ryan Giggs", country: "Wales", position: "Winger", era: "1990s-2010s", club: "Manchester United" },
      { name: "Gareth Bale", country: "Wales", position: "Winger", era: "2000s-2020s", club: "Real Madrid" },
      { name: "Ian Rush", country: "Wales", position: "Striker", era: "1980s-1990s", club: "Liverpool" },
      { name: "George Best", country: "Northern Ireland", position: "Winger", era: "1960s-1980s", club: "Manchester United" },
      { name: "Kenny Dalglish", country: "Scotland", position: "Forward", era: "1970s-1990s", club: "Liverpool" },
      { name: "Denis Law", country: "Scotland", position: "Striker", era: "1950s-1970s", club: "Manchester United" },
      { name: "Graeme Souness", country: "Scotland", position: "Midfielder", era: "1970s-1990s", club: "Liverpool" },
      { name: "John Charles", country: "Wales", position: "Forward", era: "1950s-1970s", club: "Juventus" },
      { name: "Alan Shearer", country: "England", position: "Striker", era: "1980s-2000s", club: "Newcastle United" },
      { name: "Wayne Rooney", country: "England", position: "Forward", era: "2000s-2020s", club: "Manchester United" },
      { name: "Steven Gerrard", country: "England", position: "Midfielder", era: "2000s-2020s", club: "Liverpool" },
      { name: "Frank Lampard", country: "England", position: "Midfielder", era: "1990s-2020s", club: "Chelsea" },
      { name: "Paul Scholes", country: "England", position: "Midfielder", era: "1990s-2010s", club: "Manchester United" },
      { name: "David Beckham", country: "England", position: "Midfielder", era: "1990s-2010s", club: "Manchester United" },
      { name: "Rio Ferdinand", country: "England", position: "Defender", era: "1990s-2010s", club: "Manchester United" },
      { name: "John Terry", country: "England", position: "Defender", era: "1990s-2010s", club: "Chelsea" },
      { name: "Ashley Cole", country: "England", position: "Left Back", era: "1990s-2010s", club: "Chelsea" },
      { name: "Harry Kane", country: "England", position: "Striker", era: "2010s-present", club: "Tottenham Hotspur" },
      { name: "Jude Bellingham", country: "England", position: "Midfielder", era: "2020s-present", club: "Real Madrid" },
      { name: "Kevin De Bruyne", country: "Belgium", position: "Midfielder", era: "2010s-present", club: "Manchester City" },
      { name: "Eden Hazard", country: "Belgium", position: "Winger", era: "2000s-2020s", club: "Chelsea" },
      { name: "Vincent Kompany", country: "Belgium", position: "Defender", era: "2000s-2020s", club: "Manchester City" },
      { name: "Jean-Marie Pfaff", country: "Belgium", position: "Goalkeeper", era: "1970s-1990s", club: "Bayern Munich" },
      { name: "Jan Ceulemans", country: "Belgium", position: "Midfielder", era: "1970s-1990s", club: "Club Brugge" },
      { name: "Thomas Müller", country: "Germany", position: "Forward", era: "2000s-present", club: "Bayern Munich" },
      { name: "Miroslav Klose", country: "Germany", position: "Striker", era: "2000s-2010s", club: "Lazio" },
      { name: "Philipp Lahm", country: "Germany", position: "Full Back", era: "2000s-2010s", club: "Bayern Munich" },
      { name: "Manuel Neuer", country: "Germany", position: "Goalkeeper", era: "2000s-present", club: "Bayern Munich" },
      { name: "Toni Kroos", country: "Germany", position: "Midfielder", era: "2000s-2020s", club: "Real Madrid" },
      { name: "Bastian Schweinsteiger", country: "Germany", position: "Midfielder", era: "2000s-2010s", club: "Bayern Munich" },
      { name: "Oliver Kahn", country: "Germany", position: "Goalkeeper", era: "1990s-2000s", club: "Bayern Munich" },
      { name: "Mesut Özil", country: "Germany", position: "Attacking Midfielder", era: "2010s-2020s", club: "Real Madrid" },
      { name: "Luis Figo", country: "Portugal", position: "Winger", era: "1990s-2010s", club: "Real Madrid" },
      { name: "Eusébio", country: "Portugal", position: "Forward", era: "1960s-1970s", club: "Benfica" },
      { name: "Deco", country: "Portugal", position: "Midfielder", era: "1990s-2010s", club: "Porto" },
      { name: "Bernardo Silva", country: "Portugal", position: "Midfielder", era: "2010s-present", club: "Manchester City" },
      { name: "Bruno Fernandes", country: "Portugal", position: "Midfielder", era: "2010s-present", club: "Manchester United" },
      { name: "Rui Costa", country: "Portugal", position: "Attacking Midfielder", era: "1990s-2000s", club: "AC Milan" },
      { name: "Pavel Nedvěd", country: "Czech Republic", position: "Midfielder", era: "1990s-2000s", club: "Juventus" },
      { name: "Petr Čech", country: "Czech Republic", position: "Goalkeeper", era: "2000s-2010s", club: "Chelsea" },
      { name: "Tomáš Rosický", country: "Czech Republic", position: "Midfielder", era: "2000s-2010s", club: "Arsenal" },
      { name: "Zlatan Ibrahimović", country: "Sweden", position: "Striker", era: "2000s-2020s", club: "AC Milan" },
      { name: "Henrik Larsson", country: "Sweden", position: "Striker", era: "1990s-2010s", club: "Celtic" },
      { name: "Freddie Ljungberg", country: "Sweden", position: "Midfielder", era: "1990s-2010s", club: "Arsenal" },
      { name: "Emil Forsberg", country: "Sweden", position: "Midfielder", era: "2010s-present", club: "RB Leipzig" },
      { name: "Erling Haaland", country: "Norway", position: "Striker", era: "2010s-present", club: "Manchester City" },
      { name: "Martin Ødegaard", country: "Norway", position: "Midfielder", era: "2010s-present", club: "Arsenal" },
      { name: "Ole Gunnar Solskjær", country: "Norway", position: "Striker", era: "1990s-2000s", club: "Manchester United" },
      { name: "Ruud Krol", country: "Netherlands", position: "Defender", era: "1970s-1980s", club: "Ajax" },
      { name: "Arjen Robben", country: "Netherlands", position: "Winger", era: "2000s-2020s", club: "Bayern Munich" },
      { name: "Wesley Sneijder", country: "Netherlands", position: "Attacking Midfielder", era: "2000s-2010s", club: "Inter Milan" },
      { name: "Robin van Persie", country: "Netherlands", position: "Striker", era: "2000s-2020s", club: "Arsenal" },
      { name: "Virgil van Dijk", country: "Netherlands", position: "Defender", era: "2010s-present", club: "Liverpool" },
      { name: "Jaap Stam", country: "Netherlands", position: "Defender", era: "1990s-2000s", club: "Manchester United" },
      { name: "Edwin van der Sar", country: "Netherlands", position: "Goalkeeper", era: "1990s-2010s", club: "Manchester United" },
      { name: "Ronald Koeman", country: "Netherlands", position: "Defender", era: "1980s-1990s", club: "Barcelona" },
      { name: "Kylian Mbappé", country: "France", position: "Forward", era: "2010s-present", club: "Paris Saint-Germain" },
      { name: "Antoine Griezmann", country: "France", position: "Forward", era: "2010s-present", club: "Atlético Madrid" },
      { name: "N'Golo Kanté", country: "France", position: "Midfielder", era: "2010s-present", club: "Chelsea" },
      { name: "Karim Benzema", country: "France", position: "Striker", era: "2000s-2020s", club: "Real Madrid" },
      { name: "Lilian Thuram", country: "France", position: "Defender", era: "1990s-2000s", club: "Juventus" },
      { name: "Marcel Desailly", country: "France", position: "Defender", era: "1980s-2000s", club: "Chelsea" },
      { name: "Jean-Pierre Papin", country: "France", position: "Striker", era: "1980s-2000s", club: "Marseille" },
      { name: "David Ginola", country: "France", position: "Winger", era: "1980s-2000s", club: "Newcastle United" },
      { name: "Raúl", country: "Spain", position: "Forward", era: "1990s-2010s", club: "Real Madrid" },
      { name: "Luis Enrique", country: "Spain", position: "Midfielder", era: "1990s-2000s", club: "Barcelona" },
      { name: "Fernando Hierro", country: "Spain", position: "Defender", era: "1980s-2000s", club: "Real Madrid" },
      { name: "Emilio Butragueño", country: "Spain", position: "Forward", era: "1980s-1990s", club: "Real Madrid" },
      { name: "Lamine Yamal", country: "Spain", position: "Winger", era: "2020s-present", club: "Barcelona" }
    ];

    function generatePlayer() {
      const randomIndex = Math.floor(Math.random() * players.length);
      const player = players[randomIndex];

      document.getElementById("playerName").textContent = player.name;
      document.getElementById("playerCountry").textContent = player.country;
      document.getElementById("playerPosition").textContent = player.position;
      document.getElementById("playerEra").textContent = player.era;
      document.getElementById("playerClub").textContent = player.club;
      document.getElementById("playerCard").style.display = "block";
    }
  </script>
</body>
</html>
