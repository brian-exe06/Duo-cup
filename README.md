<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Duo Cup</title>
    <link rel="icon" href="logo.ico">
    <style>

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }


        /* Tabla eliminatoria */
        .eliminatoria {
            display: flex;
            justify-content: center;
            margin-left: 30px;
            gap: 10px;
            width: 100%;
        }

        .round {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 6px;
        }

        .h2-cuartos {
            font-size: 16px;
            margin-bottom: 68px;
            background-color: #b7daff;
        }

        .h2-semifianles {
            font-size: 16px;
            margin-bottom: 150px;
            background-color: #b7daff;
        }

        .h2-final {
            font-size: 16px;
            margin-bottom: 310px;
            background-color: #b7daff;
        }

        .titulo-grande {
            font-size: 20px;
        }

        .match {
            font-size: 10px;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 3px;
            width: 100px;
            background-color: #e0e0e0;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
            
        }

        .match span {
            margin: 2px 0;
            font-size: 14px;
        }

        .final {
            font-size: 12px;
            font-weight: bold;
            background-color: #ecf0f1;
            padding: 12px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 180px;
        }

        header {
            background-color: #007bff;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        nav {
            background-color: #0056b3;
            padding: 0.5rem 0;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            padding: 2rem;
            text-align: center;
            margin: 10px;
        }

        .sangria {
            text-indent: 0em;
        }

        img {
            max-width: 25%;
            border-radius: 25px;
            height: auto;
            display: block;
            margin: 1rem auto;
        }

        .imagen-ajustada {
            width: 300px; /* Cambia a tu tamaño deseado */
            height: auto; /* Mantiene la proporción de la imagen */
        }

        table {
            margin: 2rem auto;
            border-collapse: collapse;
            width: 80%;
            text-align: center;
            background-color: #fff;
            border: 1px solid #ccc;
        }

        table th, table td {
            border: 1px solid #ccc;
            padding: 0.5rem;
        }

        table th {
            background-color: #007bff;
            color: white;
        }
        
        @media (max-width: 768px) {
            .eliminatoria {
                flex-direction: column;
                align-items: center;
                margin: left;
            }
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .highlight {
            background-color: #d4edda;
        }
    </style>
</head>
<body>
    <header>
        <h1>Duo Cup</h1>
    </header>
    <nav>
        <a href="#Inicio">Inicio</a>
        <a href="#Fase de grupos">tabla fase de grupos</a>
        <a href="#Tabla-de-eliminatoria">tabla eliminatoria</a>
        <a href="#Contactos">Contactos</a>
        <a href="#calendario">Calendario</a>
        
    </nav>
    <main>
        <h2 id="Inicio">Sobre el torneo</h2>
        <p class="main">
            ¡Prepárate para la batalla! Presentamos la Duo cup un  Torneo de 2v2 en Clash Royale, donde <br>
            el trabajo en equipo será clave para alcanzar la victoria.
            
              <li>El torneo será en modalidad 2v2.</li>
              <li>Cada equipo estará compuesto por 2 jugadores.</li>
              <li>La fecha del torneo se dara a conocer cuando los jugadores confirmen su asistencia.</li>
              <li>Ya confirmado los jugadores comenzara la fase de grupos donde se va a realizar <br>
                el sorteo para dividirlos en 8 grupos, cada grupo va a estar divido en 4 equipos.</li>
              <li>Luego de pasar la fase de grupos siguira la fase eliminatoria, octavos, cuartos de final,<br>
                semifinal y la final.</li>
                <li>En la fase de grupo como en un mundial los 4 equipos jugarán entre si ,ejemplo con un equipo A:Equipo A vs Equipo B, Luego Equipo A vs Equipo C y por último partidio del equipo A Equipo A vs Equpo D.<br>
                cada partido se jugarán 3 partidas, ejemplo: Equipo A jugara el primer partido vs el Equipo B; éstos dos equipos jugarán 3 partidas, cada partida con un mazo Diferente, máximo de cartas repetidas "3" y si un equipo repite mas de "3" cartas, en la segunda partida se repitiera (solo una vez),si dos equipos consiguen los mismos puntos se decidirá por diferencia de coronas.
                
                </li>
                
                <li>sistema de puntuación: cada victoria suma 1 punto y por cada derrota no se suman puntos.
                </li>
                <li>
                    los partidos inicialmente iniciarán a las 5 hora colombiana.
                </li>

        </p>
        <p><strong>20 / ENERO / 2025</strong></p>
        <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg-Krk2No69TabId17NDE1JHSFm_Si7Nue_DQAzqvsUlODQ16SMnu6Hw0SXxy-YPu0FiwUPVgH1mAii3nHH6a2kWfvQyAuqXjV2v1Ndff18ciqHJpIblABLWIMm4E4azaAYrEb-15nNFbA/s2048/Clipart+clash+of+clans+royale+png+descarga+gratis+%2528151%2529.png" class="imagen-ajustada" alt="">
        
        <h2 id="Fase de grupos">Fase de grupos</h2>
        
        <p>estas son las tablas de puntos de cada grupo.</p>


        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>D.Coronas</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>A</td>
                    <td>Drakaina ♡ 🧸</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>A</td>
                    <td>Andres_rma09🐐</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>A</td>
                    <td>zkekox</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>A</td>
                    <td>luisdavid</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>D.Coronas</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>B</td>
                    <td>------</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>B</td>
                    <td>------</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>B</td>
                    <td>💀⚡Dark Tok⚡💀</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>B</td>
                    <td>Paco_royal18</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
        </table>

        <!-- Grupos B-H -->
        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>D.Coronas</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>C</td>
                    <td>🥇 Alfonzo glez 🥇</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>C</td>
                    <td>Xnthony 🐷</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>C</td>
                    <td>AngelJuegaYT</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>C</td>
                    <td>B e c e B o y 🖤</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>

            </tbody>
        </table>
        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>Empatados</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>D</td>
                    <td>Buchee23</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>D</td>
                    <td>BNETO🥷</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>D</td>
                    <td>ItsJav🦇</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>D</td>
                    <td>GatoPan🖤Giomora</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>D.Coronas</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>E</td>
                    <td>JPN/GM🇯🇵🇩🇪❤️Mrdavid</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>E</td>
                    <td>Martin 2.0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>E</td>
                    <td>Quetito👻</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>E</td>
                    <td>StarkClash</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
        </table>
        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>D.Coronas</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>F</td>
                    <td>Hugo_random</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>F</td>
                    <td>Alonso</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>F</td>
                    <td>alex</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>F</td>
                    <td>clash Royal</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>

            </tbody>
        </table>
        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>D.Coronas</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>G</td>
                    <td>Mauricio.Cardona</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>G</td>
                    <td>Rafagod😎🦄</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>G</td>
                    <td>Brian 🙀</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>G</td>
                    <td>jan Moreno🧸🎭444</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
        </table>
        <table>
            <thead>
                <tr>
                    <th>Grupo</th>
                    <th>Equipo</th>
                    <th>Jugados</th>
                    <th>Ganados</th>
                    <th>D.Coronas</th>
                    <th>Perdidos</th>
                    <th>Puntos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="highlight">
                    <td>H</td>
                    <td>Andres</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr class="highlight">
                    <td>H</td>
                    <td>Dianne g</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>H</td>
                    <td>Yulay</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>H</td>
                    <td>RENATO GAMER 👑</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                    <td>0</td>
                </tr>

            </tbody>
        </table>
        
        <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiFZdhIQ-kbTZFf6mX0lWjsjEemAo9ei8wSKsx3NbD_1nXrPfRIfEWFW1gsSHcr6VYVKFrPIt4tYn6v9jhnTBkcfUnWwrofc_ZXKSLmL_OZcnwSwG8Ix79yZ_Qr2kQzHDDQUBQmdbHzVVM/s600-rw/Clipart+clash+of+clans+royale+png+descarga+gratis+%2528140%2529.png" class="imagen-ajustada">
        
        <h2 id="Tabla-de-eliminatoria">Tabla eliminatoria</h2>
        <p>pasan los 2 equipos de cada grupo con mas puntos.</p>

        <div class="eliminatoria">

            <!-- Cuartos de final -->
            <div class="round">
                <h2 class="h2-cuartos">Cuartos de Final</h2>
                <div class="match" style="margin-bottom: 68px;">
                    <span>Equipo A1</span>
                    <span>vs</span>
                    <span>Equipo B2</span>
                </div>
                <div class="match" style="margin-bottom: 75px;">
                    <span>Equipo C1</span>
                    <span>vs</span>
                    <span>Equipo D2</span>
                </div>
                <div class="match" style="margin-bottom: 75px;">
                    <span>Equipo E1</span>
                    <span>vs</span>
                    <span>Equipo F2</span>
                </div>
                <div class="match">
                    <span>Equipo G1</span>
                    <span>vs</span>
                    <span>Equipo H2</span>
                </div>
            </div>
    
            <!-- Semifinales -->
            <div class="round">
                <h2 class="h2-semifianles">Semifinales</h2>
                <div class="match" style="margin-bottom: 205px;">
                    <span>Ganador 1</span>
                    <span>vs</span>
                    <span>Ganador 2</span>
                </div>
                <div class="match">
                    <span>Ganador 3</span>
                    <span>vs</span>
                    <span>Ganador 4</span>
                </div>
            </div>
    
            <!-- Final -->
            <div class="round">
                <h2 class="h2-final">Final</h2>
                <div class="final">
                    <span>Ganador 1</span>  
                    <span>vs</span>
                    <span>Ganador 2</span>
                </div>
                <img src="copa1.webp" alt="Trofeo" class="imagen-final">
            </div>
    
            <!-- Semifinales -->
            <div class="round">
                <h2 class="h2-semifianles">Semifinales</h2>
                <div class="match" style="margin-bottom: 205px;">
                    <span>Ganador 1</span>
                    <span>vs</span>
                    <span>Ganador 2</span>
                </div>
                <div class="match">
                    <span>Ganador 3</span>
                    <span>vs</span>
                    <span>Ganador 4</span>
                </div>
            </div>
    
            <!-- cuartos -->
            <div class="round">
                <h2 class="h2-cuartos">Cuartos de Final</h2>
                <div class="match" style="margin-bottom: 68px;">
                    <span>Equipo B1</span>
                    <span>vs</span>
                    <span>Equipo A2</span>
                </div>
                <div class="match" style="margin-bottom: 75px;">
                    <span>Equipo D1</span>
                    <span>vs</span>
                    <span>Equipo C2</span>
                </div>
                <div class="match" style="margin-bottom: 75px;">
                    <span>Equipo F1</span>
                    <span>vs</span>
                    <span>Equipo E2</span>
                </div>
                <div class="match">
                    <span>Equipo H1</span>
                    <span>vs</span>
                    <span>Equipo G2</span>
                </div>
            </div>
        </div>
        <h2 id="calendario">Calendario </h2>
        <p><strong>jueves 20 de enero 2025</strong></p>
        
        <p>----------------------------------------------------</p>
        
        <p>partido 1 - Grupo A : Drakaina ♡ 🧸 <span style="color: red;">VS</span> Andres_rma09🐐</p>
        <p>5:00 - 5:20</p>
       
       
        <p>partido 2 - Grupo A :  zkekox <span style="color: red;">VS</span> luisdavid</p>
        <p>5:20 - 5:40</p>
        
        <p>----------------------------------------------------</p>
        
        <p>partido 3 - Grupo B : ------ <span style="color: red;">VS</span> ------</p>
        <p>5:40 - 6:00</p>

        
    <p>partido 3 - Grupo B : 💀⚡Dark Top ⚡💀<span style="color: red;">VS</span>  familydom</p>
        <p>5:40 - 6:00</p>
        
        <p>----------------------------------------------------</p>
        
        <p>partido 5 - Grupo C : 🥇 Alfonzo glez 🥇<span style="color: red;">VS</span> Xnthony🐷</p>
        <p>6:20 - 6:40</p>


        <p>partido 6 - Grupo C : AngelJuegaYT <span style="color: red;">VS</span> B e l c e B o y 🖤</p>
        <p>6:40 - 7:00</p>
    
        <p>----------------------------------------------------</p>
        
        <p>partido 7 - Grupo D : Buchee23 <span style="color: red;">VS</span> BNETO🥷</p>
        <p>7:00 - 7:20</p>
        
        
        <p>partido 8 - Grupo D : itsJav🦇 <span style="color: red;">VS</span>  GatoPan🖤Giomora</p>
        <p>7:20 - 7:40</p>
        
        <p>----------------------------------------------------</p>
        
        <p>partido 9 - Grupo E : JPN/GM🇯🇵🇩🇪❤️Mrdavid <span style="color: red;">VS</span>  Martin 2.0</p>
        <p>7:40 - 8:00</p>
        
        
        <p>partido 10 - Grupo E : Quetito👻 <span style="color: red;">VS</span>  StarKclash</p>
        <p>8:00 - 8:20</p>
        
        <p>----------------------------------------------------</p>
        
        <p>partido 11 - Grupo F : Hugo_random <span style="color: red;">VS</span> Alonso</p>
        <p>8:20 - 8:40</p>
        
        
        <p>partido 12 - Grupo F : alex <span style="color: red;">VS</span> clash Royal</p>
        <p>8:40 - 9:00</p>
        
        <p>----------------------------------------------------</p>
        
        <p>partido 13 - Grupo G : Mauricio.Cardona<span style="color: red;">VS</span>Rafagod😎🦄</p>
        <p>9:00 - 9:20</p>
        
        
        <p>partido 14 - Grupo G : Brian 🙀<span style="color: red;">VS</span> jan Moreno🧸🎭444</p>
        <p>9:20 - 9:40</p>
        
        <p>----------------------------------------------------</p>
        
        <p>partido 15 - Grupo H : Andres<span style="color: red;">VS</span> Dianne g</p>
        <p>9:40 - 10:00</p>
        
        
        <p>partido 16 - Grupo H : Yulay<span style="color: red;">VS</span> RENATO GAMER 👑</p>
        <p>10:00 - 10:20</p>
        
    <footer id="Contactos">
        <p>&copy; 2024 Duo cup. Todos los derechos reservados. instagram: @liga_random</p>
    </footer>
</body>
</html>
