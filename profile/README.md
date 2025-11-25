<div align="center">
  <a href="https://aeroduel.github.io/">
    <img src="/profile/two-jets-logo.svg" alt="Aeroduel Logo" width="800" />
  </a>
  <br />
  <hr/>
  <br />
  <h1>Aeroduel: The future of RC aerial combat.</h1>
  <hr/>

<h2>What is Aeroduel?</h2>
  <p>Aeroduel merges cutting-edge software engineering with RC model aircraft to
     create the an advanced aerial combat system for RC aircraft.</p>
  <p>We're equipping high-performance RC fighter jets with camera systems that 
     automatically detect targets equipped with Aeroduel detection lights. This
     allows aircraft to use advanced computer vision to lock onto targets and 
     simulate aerial combat, keeping score via a Wi-Fi connection to the host 
     server back on the ground. Add FPV cameras and pilots can get a true
     cockpit experience and aim like a pro.</p>

  <p>Our mobile app will allow users to register their planes equipped with
     Aeroduel equipment and enter dogfights by scanning a QR code or entering a 
     game pin displayed on the host computer. This requires at least one player 
     to have our desktop app installed and all players to have our mobile app 
     installed, as well as the proper Aeroduel equipment installed on their 
     plane of choice.</p>

  <h2>How it Works</h2>

  <h3>Hosting the Match Server</h3>
  <p>One person installs the Aeroduel Server desktop app, available for Windows,
     MacOS, and Linux. This user connects to a WFi network (may be a mobile
     hotspot) and creates a new match.</p>

  <h3>Joining the Match</h3>
  <p>Participating players register for the match with the Aeroduel mobile app
     by either scanning a QR code or inputting a game PIN. When all players have
     joined, the host may start the match with a single click.</p>

  <h3>Behind the Scenes</h3>
  <p>Onboard each plane is a computer vision camera, several LED lights, a LoRa
     WiFI receiver, and an ESP32 arduino. When the camera detects the color
     pattern of a participating plane, it locks on for several seconds. If
     it can maintain that lock for several seconds, it registers a hit, sending
     a signal to the server, which then sends an updated score to the mobile app.
  </p>
  <p>The planes, server, and mobile apps communicate with each other via a 
     WebSocket connection, allowing for low-latency communication between the
     entire system during the match.</p>

  <h3>Game Rules</h3>
  <p>The match timer begins when all planes have taken off. Pilots then attempt
     to lock on to other planes by keeping them within view of the cockpit. When
     a solid lock is initiated, the game simulates a shot and logs a hit, giving
     the pilot 1 point. Though no physical shots are fired, accidents happen,
     even in normal every day flights. If a participating plane crashes, they
     are disqualified from the match, though this currently cannot be detected
     automatically, and that is up to the players to handle.</p>
  <p>When the timer ends, all pilots must take turns landing. The pilot with
     the most points wins the match.</p>

  <h2>Our Team</h2>
  <p>We are a team of 5 students from Atlas School, Tulsa. We are currently 
     working on our promotional website, desktop server app, and mobile app, 
     in addition to building and testing our RC fighter jets.</p>
  <ul>
    <li><a href="https://github.com/SpaceDandy15">Malik Vance</a></li>
    <li><a href="https://github.com/Zytronium">"Zytronium"</a></li>
    <li><a href="https://github.com/TebariousBag">Tristan Davis</a></li>
    <li><a href="https://github.com/zack6yuan">Zack Yuan</a></li>
    <li><a href="https://github.com/Frandy4ever">Frandy Slueue</a></li>
  </ul>

  <h2>Project Timeline</h2>
  <p>An exact date of completion is not yet known, however, a demo will be 
     available by Thursday, December 11th, 2025.</p>
</div>

---
<div align="center">
  <h2>Our Apps</h2>

  <a href="https://github.com/Aeroduel/server">
    <img src="/profile/logo_text.svg" alt="Aeroduel" width="300" />
  </a>
  <br />
  <img src="/profile/server-text.svg" alt="Server" width="115" />
  <br />
  <h1>Aeroduel Local Server</h1>
  <p>
    <strong>The dedicated game server for the Aeroduel experience.</strong>
  </p>

  <hr/>

  <a href="https://github.com/Aeroduel/mobile">
    <img src="/profile/aero-duel-jet-left-logo.svg" alt="Aeroduel" width="300" />
  </a>
  <br />
  <h1>Aeroduel Mobile App</h1>
  <p>
    <strong>The mobile app for joining matches</strong>
  </p>

  <hr/>

  <p>For more information, visit our website at <a href="https://aeroduel.github.io/">aeroduel.github.io</a></p>
</div>
