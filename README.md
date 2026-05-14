<div align="center">
  <h1> Home Mesh Wi-Fi: TP-Link Deco M4</h1>
  <p><i>Dokumentace návrhu, instalace a testování domácí mesh sítě</i></p>
</div>

<hr>

<section id="introduction">
  <h2> Popis projektu</h2>
  <p>
    Tento repozitář slouží jako dokumentace k řešení domácího internetového pokrytí. 
    Hlavním problémem byly "mrtvé zóny" v odlehlých částech domu a nestabilní přepínání 
    mezi staršími routery. Zvolil jsem technologii Mesh pro zajištění plynulého roamingu.
  </p>
</section>

<section id="hardware">
  <h2>🛒 Výběr Hardwaru</h2>
  <p>Po analýze trhu jsem vybral <b>TP-Link Deco M4 (3-pack)</b>. Zvažoval jsem i následující alternativy:</p>

  <table width="100%">
    <thead>
      <tr>
        <th>Model</th>
        <th>Hlavní přednost</th>
        <th>Proč nevybrán?</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Mercusys Halo H50G</b></td>
        <td>Skvělá cena / Rychlost</td>
        <td>Chybějící podpora některých funkcí a méně stabilní SW.</td>
      </tr>
      <tr>
        <td><b>Asus ZenWiFi AC</b></td>
        <td>Extrémní dosah a nastavení</td>
        <td>Cena byla pro tento projekt příliš vysoká.</td>
      </tr>
      <tr>
        <td><b>Tenda Nova MW6</b></td>
        <td>Jednoduchost a cena</td>
        <td>Slabší propustnost při větším množství připojených zařízení.</td>
      </tr>
    </tbody>
  </table>
</section>

<section id="implementation">
  <h2> Implementace a Plánování</h2>
  
  <h3>1. Náčrt domu a zóny pokrytí</h3>
  <p>
    Na náčrtu níže jsou vyznačeny pozice jednotlivých jednotek (Deco 1, 2, 3) a jejich 
    přibližný dosah signálu v rámci pater.
  </p>
  <img src="path/to/tvuj-nacrt.png" alt="Náčrt domu a pokrytí" width="100%">

  <h3>2. Reálné umístění (Detailní pohledy)</h3>
  <p>
    Jednotky by měli být umístěny tak, aby nebyly v uzavřených prostorech (skříně apod.), 
    což maximalizuje efektivitu antén. Bohužel jsem však musel udělat vyjímku v kuchyni z důvodu špatně přístupných zásuvek.
  </p>
  
  <div align="center">
    <img src="fotky/pokojicek.jpeg" alt="Deco hlavní jednotka Pokojíček" width="30%" style="margin-right: 10px;">
    <img src="fotky/kuchyn.jpeg" alt="Deco jednotka Kuchyň" width="30%" style="margin-right: 10px;">
    <img src="fotky/dilna.jpeg" alt="Deco jednotka Dílna" width="30%">
    <br>
    <small><i>Detailní pohledy na umístění jednotek (viz pozice v náčrtu).</i></small>
  </div>
</section>

<section id="results">
  <h2>  Naměřené výsledky (Speedtest)</h2>
  <ul>
    <li><b>Deco 1 (Pokojíček):</b> 50 Mbps / 10 Mbps</li>
    <li><b>Deco 2 (Kuchyň):</b> 50 Mbps / 10 Mbps</li>
    <li><b>Deco 3 (Dílna):</b> 25 Mbps / 5 Mbps</li>
  </ul>
</section>

<hr>

<footer align="center">
  <p>Vytvořeno jako součást domácího networking projektu.</p>
</footer>
