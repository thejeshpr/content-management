<!-- 🏍️ Gixxer Rules (Bootstrap 5 Dark Theme - Mobile Friendly) -->
<meta name="viewport" content="width=device-width, initial-scale=1">

<div class="container-fluid p-2" style="max-width:800px;">
  <div class="card bg-dark text-light shadow-sm mb-2">
    <div class="card-body py-3">
      <h3 class="card-title mb-1">🏍️ <strong>Gixxer Rules</strong></h3>
      <p class="card-text small text-muted mb-0">
        You <strong>must follow all the rules below</strong>. These instructions are for <strong>our own safety</strong> and to keep the bike in top condition — not restrictions, but good habits to make sure it runs smooth and lasts long. 🚦
      </p>
    </div>
  </div>

  <div class="card bg-dark text-light mb-3" style="border-radius:12px;">
    <ul class="list-group list-group-flush">
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">1.</span> No rash riding — Ride responsibly and safely.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">2.</span> Speed limit: <strong>60 km/h max</strong> — Don’t exceed this limit.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">3.</span> Don’t give the bike to anyone else — Strictly for your use only.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">4.</span> Avoid unnecessary rides — Use it only when needed.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">5.</span> Monthly fuel limit: <strong>₹500</strong> — Stay within this budget.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">6.</span> Handle the bike with care — Treat it like your own.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">7.</span> No triple riding — Only two people allowed.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">8.</span> Keep the chain clean — Regular maintenance keeps performance smooth.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">9.</span> Don’t remove the SIM from the GPS tracker — It’s for safety and tracking.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">10.</span> No long drives — Keep it for short or essential city rides only.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">11.</span> No long-distance temple runs — Avoid long religious trips or outstation rides.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">12.</span> Check engine oil regularly — Maintain good engine health.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">13.</span> Keep the bike clean — Wash and wipe regularly.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">14.</span> No helmet, no bike — Always wear a helmet, no exceptions.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">15.</span> Always park in a safe, designated place — Avoid no-parking zones or direct sunlight for long hours.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">16.</span> Report any damage immediately — Even small scratches or dents.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">17.</span> Avoid riding in heavy rain or water-logged areas — Protects electricals and chain.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">18.</span> Switch off headlight when parked — Prevents battery drain.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">19.</span> Don’t rev or race unnecessarily — Wastes fuel and stresses the engine.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">20.</span> Don’t sit on the bike when it’s on the stand — Can damage the stand or cause it to fall.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">21.</span> Always park the bike inside the gate before sleeping — If used during the day, bring it inside before bed.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">22.</span> If the bike was parked in rain, check for water around the fuel tank cap before riding again — Prevents water entering the tank.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">23.</span> Regularly inspect the bike’s overall condition — Check brakes, tyres, lights, and other parts to avoid bigger issues later.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">24.</span> Keep track of service intervals and inform me for service — Monitor kilometres/date and notify when service is due.</li>
      <li class="list-group-item bg-dark text-light border-0 py-2"><span class="fw-bold">25.</span> Always return home by <strong>8:30 PM</strong> — If you’re getting late, call and inform in advance.</li>

      <!-- Message section -->
      <li class="list-group-item bg-dark text-light border-0 py-3">
        <div class="fw-semibold">26. A message for you</div>
        <div class="small text-muted mt-1">
          I’ve taken good care of this Gixxer all along — I even thought about selling it a few times, but didn’t because it means something.  
          Now it’s your turn to keep it running strong and in good condition.  
          Take care of it, and it’ll take care of you on every ride. <span class="text-warning">❤️🏍️</span>
        </div>
      </li>
    </ul>
  </div>

  <div class="card bg-dark text-center text-muted py-2" style="border-radius:10px;">
    <div class="small px-2">
      👉 <strong>If you take care of the bike, it’ll serve you well for years — ignore it, and it’ll break down sooner than you think.</strong>
    </div>
  </div>

  <div class="text-center mt-3">
    <small class="text-muted">Last updated: <span id="gx-last-updated"></span></small>
  </div>
</div>

<script>
  // Auto-insert today's date for "Last updated"
  (function(){
    var el = document.getElementById('gx-last-updated');
    if(!el) return;
    var d = new Date();
    var opts = { year:'numeric', month:'short', day:'numeric' };
    el.textContent = d.toLocaleDateString(undefined, opts);
  })();
</script>