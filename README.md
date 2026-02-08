<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VIP PAGE | BANKER</title>

<style>
*{
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
    margin:0;
    padding:0;
}

body{
    background:#111;
    display:flex;
    justify-content:center;
    padding:10px;
}

.container{
    width:100%;
    max-width:390px;
    background:#1b1b1b;
    border-radius:10px;
    overflow:hidden;
}

/* HEADER */
.header{
    background:#6cc070;
    padding:12px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.header-left{
    color:#000;
    font-weight:bold;
    font-size:14px;
}

.header-left span{
    margin-right:8px;
}

.header-right{
    color:#000;
    font-size:18px;
}

/* TABLE */
table{
    width:100%;
    border-collapse:collapse;
    color:#fff;
    font-size:12px;
}

/* VERY VISIBLE GRID LINES */
td{
    padding:10px 6px;
    text-align:center;
    border:2px solid #6a6a6a;
}

/* COLUMN STYLES */
td.match{
    text-align:left;
    width:38%;
}

td.date{
    width:18%;
    color:#f0f0f0;
    font-weight:700;
}

td.market{
    width:18%;
}

/* STACK OVER / 3.5 */
.market-top,
.market-bottom{
    display:block;
    line-height:1.1;
}

td.odds{ width:10%; }
td.score{ width:10%; }

td.status{
    width:10%;
    font-weight:bold;
}

/* STATUS COLORS */
.win{ color:#38ff6b; }
.lost{ color:#ff3b3b; }
</style>
</head>

<body>

<div class="container">

    <div class="header">
        <div class="header-left">
            <span>VIP PAGE</span> | <span>BANKER</span>
        </div>
        <div class="header-right">🔔</div>
    </div>

    <table>
        <tr>
            <td class="date">25.01.2026</td>
            <td class="match">Feyenoord - Heracles</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">4.5</span>
            </td>
            <td class="odds">3.15</td>
            <td class="score">4:2</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">26.01.2026</td>
            <td class="match">Crystal Palace U21 - Derby U21</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">4.5</span>
            </td>
            <td class="odds">3.20</td>
            <td class="score">6:0</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">27.01.2026</td>
            <td class="match">Portimonense U23 - Gil Vicente U23</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.23</td>
            <td class="score">1:3</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">28.01.2026</td>
            <td class="match">Napoli - Chelsea</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.10</td>
            <td class="score">2:3</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">29.01.2026</td>
            <td class="match">Umm Salal - Al Arabi</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.45</td>
            <td class="score">2:4</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">30.01.2026</td>
            <td class="match">ADO Den - Jong AZ</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.80</td>
            <td class="score">1:4</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">31.01.2026</td>
            <td class="match">Larnaca - Enosis Neon</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.55</td>
            <td class="score">4:0</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">01.02.2026</td>
            <td class="match">Excelsior - Ajax</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.45</td>
            <td class="score">2:2</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">02.02.2026</td>
            <td class="match">Jong PSV - SC Cambuur</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.60</td>
            <td class="score">3:1</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">03.02.2026</td>
            <td class="match">AFC Fylde - Peterborough</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.20</td>
            <td class="score">5:2</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">04.02.2026</td>
            <td class="match">NEC Nijmegen - Volendam</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.00</td>
            <td class="score">1:0</td>
            <td class="status lost">LOST</td>
        </tr>

        <tr>
            <td class="date">05.02.2026</td>
            <td class="match">Al Wahda - Al Bataeh</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.30</td>
            <td class="score">2:2</td>
            <td class="status win">WIN</td>
        </tr>

        <tr>
            <td class="date">06.02.2026</td>
            <td class="match">De Graafschap - Jong Ajax</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.00</td>
            <td class="score">4:0</td>
            <td class="status win">WIN</td>
        </tr>
 





             <tr>
            <td class="date">07.02.2026</td>
            <td class="match">Real Sociedad - Elche</td>
            <td class="market">
                <span class="market-top">Over</span>
                <span class="market-bottom">3.5</span>
            </td>
            <td class="odds">3.50</td>
            <td class="score"> </td>
            <td class="status "> </td>
        </tr>
 









   </table>

</div>

</body>
</html>
