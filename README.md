<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Liminal Interactive | Indie Game Studio</title>
  
  <!-- Carbon-style font -->
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
  
  <!-- Styles and scripts -->
  <link rel="stylesheet" href="styles.css" />
  <script defer src="script.js"></script>

  <!-- Apply font to entire site -->
  <style>
    body {
      font-family: 'Share Tech Mono', monospace;
    }
  </style>
</head>
<body>
  <script>
  document.addEventListener("DOMContentLoaded", function () {
    const collapsibles = document.querySelectorAll(".collapsible");

    collapsibles.forEach((button) => {
      button.addEventListener("click", function () {
        this.classList.toggle("active");
        const content = this.nextElementSibling;

        if (content.style.maxHeight) {
          content.style.maxHeight = null;
          content.style.paddingTop = "0";
          content.style.paddingBottom = "0";
        } else {
          content.style.maxHeight = content.scrollHeight + "px";
          content.style.paddingTop = "0.5rem";
          content.style.paddingBottom = "0.5rem";
        }

        this.textContent = this.textContent.startsWith("▾")
          ? this.textContent.replace("▾", "▸")
          : this.textContent.replace("▸", "▾");
      });
    });
  });
</script>

  <header>
    <h1>Liminal Interactive</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="projects.html">Projects</a>
      <a href="devblog.html">Dev Blog</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main class="section">
    <h2>Welcome to Liminal Interactive</h2>
    <p>
      Liminal Interactive was created to make games which people might enjoy, as most games these days feel like empty. Overpriced, unfinished, and sometimes a buggy mess. We were tired of paying full price for something that felt like a chore to play.
    </p>
    <p>
      So we decided to do our own thing. We want to make games that stick with you — not because they’re flashy, but because they mean something. Stories that hit hard. Characters you might actually care about. The themes is in these games aren’t afraid to get uncomfortable.
    </p>
    <p>
      It's not about being fancy. It’s about being real. We’re not some big studio with a million-dollar budget — we’re a couple of people who care about what games *could* be. That’s what drives us. If that resonates with you, you’re in the right place.
    </p>
  </main>

  <section class="section">
    <h2>Featured Projects</h2>

    <div class="project">
  <h3><a href="projects.html#vanguard">Vanguard: Hammerfall</a></h3>
  <p>
    Vanguard: Hammerfall is a gritty, hyper-realistic first-person shooter set during a fictional 2019 conflict in the Philippines. But it’s not your typical military shooter. You don’t play the hero. You play a ghost — known only as The Rookie — a black-ops operative, someone trained to follow orders without question, to survive by any means, and to erase his presence as easily as he erases threats.
  </p>
  <p>
    The game opens mid-chaos: a botched helicopter drop, friendly fire, and an entire region spiraling into madness. As the player, you’re forced to navigate political lies, command betrayal, and an unraveling mental state, all while completing missions that blur the line between duty and atrocity. The gunfights are brutal, close-quarters, and anxiety-inducing. Every bullet counts. Every kill leaves a mark.
  </p>
  <p>
    But beneath the combat lies the real game — the psychological unravelling of The Rookie. Dialogue is minimal, choices are subconscious, and the narrative is shaped not by what you say, but how you behave under pressure. There are no morality bars, no good endings. There’s just consequence.
  </p>
      <button class="collapsible">▸ DLC – Containment Protocol</button>
<div class="content">
  <p>
    After the events of the main campaign, an abandoned facility near the quarantine zone begins broadcasting encrypted signals. Vanguard is sent in — not to rescue, but to erase. What they find inside changes the scope of the war: infected test subjects, corporate-backed bio-weapons, and the harrowing question of whether the outbreak was an accident... or a live trial. The Rookie is reactivated, and what follows is a claustrophobic, morally bankrupt descent into pandemic containment at gunpoint. It’s not about saving lives — it’s about burying secrets.
  </p>
</div>

    <div class="project">
  <h3><a href="projects.html#oakridge">Oakridge: Static</a></h3>
  <p>
    Oakridge: Static is not a horror game in the traditional sense — it’s a slow, suffocating descent into memory loss, trauma, and madness. You play as Andrew “Hammer” Miller, a once-stoic special forces operative now spiraling into post-traumatic stress after leaving Vanguard. Haunted by things he did — and things he doesn’t even remember doing — Andrew wakes up in Oakridge, a town that shifts around him like a fever dream.
  </p>
  <p>
    The gameplay is quiet, methodical, and discomforting. Doors lead to places they shouldn’t. Recordings glitch with voices that sound like his. Street signs change. Mirrors lie. You are never quite sure if what you’re experiencing is real, or a projection of Andrew’s fractured mind.
  </p>
  <p>
    The story is nonlinear, told through scattered journals, and choices that seem meaningless — until they aren’t. It’s a story about guilt, repressed memory, and the fear that maybe the monster isn’t hiding under the bed… maybe it’s you.
  </p>
      <button class="collapsible">▸ DLC – Before the Silence</button>
<div class="content">
  <p>
    Set during Hammer’s final mission with Vanguard, this DLC peels back the layers of the mission that broke him. What began as a covert hostage extraction in the Central Asian highlands devolved into a massacre — civilians caught in the crossfire, orders rewritten mid-op, and an objective that was never what it seemed. You experience the mission firsthand, through the fractured lens of a soldier obeying commands he no longer understands. This isn’t just backstory — it’s the trigger that shattered Andrew's sense of self, and the reason he walked away from it all.
  </p>
</div>

    <div class="project">
  <h3><a href="projects.html#nexus">Project Nexus Universe</a></h3>
  <p>
    Project Nexus isn’t just a timeline or a shared setting — it’s the spine holding everything together. Every mission in Vanguard, every hallucination in Oakridge, every shadowy name in a dossier — it all connects back to a broader universe where truth is fragmented and nothing is coincidence.
  </p>
  <p>
    The universe is grounded in realism, but never comfortable. It’s a world where black-ops teams are just tools for power struggles, and every character is a pawn, or worse — a willing piece. From redacted CIA files to psychological profiles built from real-world trauma cases, Project Nexus builds a world where war isn't just about politics or territory, but about the lies we tell ourselves to justify pulling the trigger.
  </p>
  <p>
    This isn’t a cinematic universe where everything lines up cleanly. It’s messy. Fractured. Human. You’ll uncover connections across games through hidden clues, thematic overlap, and slowly unraveling truths. Nothing is ever said directly. You earn every piece of lore you find. Because in Nexus, the biggest question is never what happened. It’s why.
  </p>
</div>
  </section>

  <footer>
    <p>&copy; 2025 Liminal Interactive. All rights reserved.</p>
  </footer>
</body>
</html>
