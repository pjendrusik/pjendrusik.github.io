---
layout: default
title: Pawel Jendrusik - Backend Engineer & Systems Architect
description: Backend engineering for payments, crypto, and data platforms. Scala, TypeScript, event-driven systems, and hands-on architecture.
---
<div class="header-shell" id="top">
  <header class="site-header container">
    <a class="wordmark" href="#top" aria-label="Pawel Jendrusik, back to top">
      <span class="monogram" aria-hidden="true">pj<span>.</span></span>
      <span>Paweł Jendrusik</span>
    </a>
    <nav class="site-nav" aria-label="Main navigation">
      <a href="#expertise">What I do</a>
      <a href="#work">Selected work</a>
      <a href="#experience">Experience</a>
      <a class="nav-contact" href="#contact">Let's talk <span aria-hidden="true">↗</span></a>
    </nav>
  </header>

</div>

<main id="main-content" tabindex="-1">
  <div class="hero-shell">
    <section class="hero container" aria-labelledby="hero-title">
      <div class="hero-copy">
        <p class="eyebrow hero-eyebrow"><span class="status-dot" aria-hidden="true"></span>Senior backend engineer / systems architect</p>
        <h1 id="hero-title">I build the systems money moves <span>through.</span></h1>
        <p class="hero-description">Payments, platforms, and the data behind them. I turn complex financial workflows into software that's reliable, understandable, and built to run.</p>
        <div class="hero-actions">
          <a class="button button-accent" href="mailto:pawel@jendrusik.pl">Let's talk <span aria-hidden="true">↗</span></a>
          <a class="text-link" href="{{ '/assets/cv.pdf' | relative_url }}" download="Pawel-Jendrusik-CV.pdf">Download my CV <span aria-hidden="true">↓</span></a>
        </div>
        <p class="hero-footnote">Fintech <span>·</span> Crypto <span>·</span> Data <span>·</span> Architecture</p>
      </div>

      <figure class="system-map" aria-label="An illustration of my focus: payment APIs connected to domain events, transactional storage, and analytics.">
        <div class="map-heading"><span class="eyebrow">Behind the product</span><span class="map-symbol" aria-hidden="true">[ + ]</span></div>
        <div class="map-canvas" aria-hidden="true">
          <svg class="map-routes" viewBox="0 0 440 340" fill="none">
            <path class="route" d="M220 82V144 M220 204V234H100V270 M220 234H340V270" />
            <path class="route route-secondary" d="M100 304H46V56H154 M340 304H394V56H286" />
            <circle class="route-point" cx="220" cy="234" r="4" />
            <circle class="route-point" cx="220" cy="115" r="3" />
          </svg>
          <div class="flow-node node-api"><span class="node-icon">↗</span><div><span class="node-label">Money movement</span><strong>Payments & APIs</strong></div></div>
          <div class="flow-node node-events"><span class="node-icon">⌘</span><div><span class="node-label">Event-driven systems</span><strong>Domain events</strong></div><span class="node-indicator"></span></div>
          <div class="flow-node node-storage"><span class="node-label">Transactional</span><strong>PostgreSQL</strong></div>
          <div class="flow-node node-analytics"><span class="node-label">Analytical</span><strong>ClickHouse</strong></div>
          <span class="map-note note-left">consistency</span>
          <span class="map-note note-right">observability</span>
        </div>
        <figcaption><span class="map-caption-dot" aria-hidden="true"></span>Correctness. Traceability. A clear path through.</figcaption>
      </figure>
    </section>
  </div>

<div class="facts-strip container" aria-label="Profile at a glance">
  <div><strong>13<span>+</span></strong><span class="eyebrow">Years of engineering</span></div>
  <div><strong>Finance & crypto</strong><span class="eyebrow">Deep domain experience</span></div>
  <div><strong>Code to architecture</strong><span class="eyebrow">Hands-on technical leadership</span></div>
  <div><strong>Product first</strong><span class="eyebrow">Engineering with purpose</span></div>
</div>

<div class="content-sections">
  <section class="section container profile-section" id="profile" aria-labelledby="profile-title">
    <div class="section-label"><span>01 /</span> Profile</div>
    <div class="profile-grid">
      <h2 id="profile-title">Good engineering sees the <span class="muted-heading">whole picture.</span></h2>
      <div class="section-copy">
        <p class="intro-copy">I'm a backend engineer who connects technical decisions with the product and the business behind them.</p>
        <p>My work spans regulated banking, crypto payments, and e-commerce: moving money, connecting partners, and making financial data useful. I work across Scala, TypeScript, and PHP, with a focus on distributed systems and the workflows they support.</p>
        <p>From modeling a transaction lifecycle to making reporting trustworthy, I stay close to the implementation and work with product, compliance, and infrastructure teams to get the details right.</p>
      </div>
    </div>
  </section>

  <section class="section container expertise-section" id="expertise" aria-labelledby="expertise-title">
    <div class="section-label"><span>02 /</span> What I do</div>
    <div class="section-heading"><h2 id="expertise-title">Complex domains.<br>Practical solutions.</h2><p>Three areas where I bring experience, context, and hands-on delivery.</p></div>
    <div class="expertise-grid">
      <article class="expertise-item">
        <span class="item-number" aria-hidden="true">01</span>
        <h3>Money movement.</h3>
        <p>Payment APIs, payouts, FX, wallets, and partner integrations. Explicit transaction states, safe retries, and audit trails that hold up in regulated environments.</p>
        <ul class="tag-list" aria-label="Payment expertise"><li>Payments & FX</li><li>KYC / KYB</li><li>PSP integrations</li></ul>
      </article>
      <article class="expertise-item">
        <span class="item-number" aria-hidden="true">02</span>
        <h3>Data you can trust.</h3>
        <p>CDC pipelines, analytical read models, and reporting that connect transactional systems to useful business metrics. Visibility for the people making decisions.</p>
        <ul class="tag-list" aria-label="Data expertise"><li>Kafka & Debezium</li><li>ClickHouse</li><li>Observability</li></ul>
      </article>
      <article class="expertise-item">
        <span class="item-number" aria-hidden="true">03</span>
        <h3>Architecture that works.</h3>
        <p>Domain models, asynchronous workflows, and backend services built around real product needs. Technical direction, mentoring, and ownership through production.</p>
        <ul class="tag-list" aria-label="Architecture expertise"><li>Distributed systems</li><li>API design</li><li>Technical leadership</li></ul>
      </article>
    </div>
  </section>

  <section class="work-section" id="work" aria-labelledby="work-title">
    <div class="section container">
      <div class="section-label"><span>03 /</span> Selected work</div>
      <div class="section-heading"><h2 id="work-title">What that looks like<br>in practice.</h2><p>Real systems, built with real product and operational constraints.</p></div>
      <div class="work-grid">
        <article class="work-card">
          <div class="work-card-top"><span class="eyebrow">Digital-asset payments</span><span class="work-category">Data & integrations</span></div>
          <div class="pipeline" aria-label="Data pipeline: MySQL to Debezium and Kafka to analytical read models"><span>MySQL</span><span class="pipeline-arrow" aria-hidden="true">→</span><span>Debezium<br><b>Kafka</b></span><span class="pipeline-arrow" aria-hidden="true">→</span><span>Read models</span></div>
          <h3>From transactions<br>to useful data.</h3>
          <p>Built CDC pipelines into ClickHouse and MongoDB, current-state views for reporting, and Grafana dashboards for pipeline health and data freshness. Checked consistency across source systems, read models, and APIs.</p>
          <ul class="tag-list" aria-label="Data platform technologies"><li>ClickHouse</li><li>MongoDB</li><li>Grafana</li></ul>
        </article>
        <article class="work-card">
          <div class="work-card-top"><span class="eyebrow">Regulated finance</span><span class="work-category">Banking & payments</span></div>
          <div class="pipeline" aria-label="Banking workflow: onboarding to accounts to payments"><span>Onboarding</span><span class="pipeline-arrow" aria-hidden="true">→</span><span>Accounts<br><b>& balances</b></span><span class="pipeline-arrow" aria-hidden="true">→</span><span>Payments</span></div>
          <h3>Financial workflows,<br>modeled properly.</h3>
          <p>Delivered payment and account services, KYC/KYB onboarding, and a shared market-data and exchange-rate service. Used Kafka and PostgreSQL to support consistent, traceable transaction lifecycles.</p>
          <ul class="tag-list" aria-label="Banking platform technologies"><li>Scala</li><li>Kafka</li><li>PostgreSQL</li></ul>
        </article>
      </div>
    </div>
  </section>

  <section class="experience-section" id="experience" aria-labelledby="experience-title">
    <div class="section container">
      <div class="section-label"><span>04 /</span> Experience</div>
      <div class="section-heading"><h2 id="experience-title">Built over time.<br><span>Grounded in delivery.</span></h2><p>From product platforms to regulated financial infrastructure. Always close to the code.</p></div>
      <div class="experience-list">
        <article class="experience-row">
          <div class="experience-domain">Data & reporting</div>
          <div class="experience-role"><h3>Backend engineering</h3><p>Crypto payment platforms</p></div>
          <p class="experience-description">CDC pipelines, financial reporting, operational read models, and client integrations for a crypto payment platform.</p>
        </article>
        <article class="experience-row">
          <div class="experience-domain">Banking & payments</div>
          <div class="experience-role"><h3>Senior software engineering</h3><p>Regulated financial products</p></div>
          <p class="experience-description">Banking and payment services, compliant onboarding, event-driven workflows, and market-data infrastructure.</p>
        </article>
        <article class="experience-row">
          <div class="experience-domain">Digital assets</div>
          <div class="experience-role"><h3>Staff & lead engineering</h3><p>Payments, custody & compliance</p></div>
          <p class="experience-description">Architectural leadership and hands-on delivery across crypto payments, wallets, PSP and exchange integrations, AML, and Travel Rule. Managed and mentored engineers.</p>
        </article>
        <article class="experience-row">
          <div class="experience-domain">Product platforms</div>
          <div class="experience-role"><h3>Backend development</h3><p>E-commerce, marketplaces & services</p></div>
          <p class="experience-description">Product services, data pipelines, KPI dashboards, and application lifecycle ownership across commerce, comparison, and sports platforms.</p>
        </article>
      </div>
      <a class="experience-cv text-link" href="{{ '/assets/cv.pdf' | relative_url }}" download="Pawel-Jendrusik-CV.pdf">Full career history in my CV <span aria-hidden="true">↓</span></a>
    </div>
  </section>

  <section class="section container toolkit-section" id="toolkit" aria-labelledby="toolkit-title">
    <div class="section-label"><span>05 /</span> The toolkit</div>
    <div class="toolkit-grid">
      <div><h2 id="toolkit-title">A broad toolkit.<br><span class="muted-heading">A clear focus.</span></h2><p class="toolkit-intro">Scala is my primary language. I also work across Node.js, TypeScript, and PHP, choosing tools that fit the system and the team.</p><a class="inline-link" href="https://github.com/pjendrusik">Find me on GitHub <span aria-hidden="true">↗</span></a></div>
      <dl class="toolkit-list">
        <div><dt>Languages</dt><dd>Scala · TypeScript · JavaScript · PHP</dd></div>
        <div><dt>Backend</dt><dd>ZIO · Cats · Akka · Tapir · sttp<br>NestJS · Express · Symfony · Laravel</dd></div>
        <div><dt>Data & messaging</dt><dd>PostgreSQL · MySQL · Kafka · RabbitMQ<br>Debezium · ClickHouse · MongoDB</dd></div>
        <div><dt>Infrastructure</dt><dd>Docker · Kubernetes · GCP<br>CI/CD · Grafana · Linux</dd></div>
      </dl>
    </div>
  </section>

  <section class="contact-section" id="contact" aria-labelledby="contact-title">
    <div class="container contact-grid">
      <div><div class="section-label"><span>06 /</span> Let's talk</div><h2 id="contact-title">Have a complex<br>problem to build for?</h2><p>Payments, data, integrations, or a backend that needs a clear direction. Tell me what you're working on.</p><a class="contact-email" href="mailto:pawel@jendrusik.pl">pawel@jendrusik.pl <span aria-hidden="true">↗</span></a></div>
      <div class="contact-actions"><a class="button button-dark" href="mailto:pawel@jendrusik.pl">Start a conversation <span aria-hidden="true">↗</span></a><a class="button button-outline" href="{{ '/assets/cv.pdf' | relative_url }}" download="Pawel-Jendrusik-CV.pdf">Download CV <span aria-hidden="true">↓</span></a><div class="social-links"><a href="https://www.linkedin.com/in/pjendrusik">LinkedIn <span aria-hidden="true">↗</span></a><a href="https://github.com/pjendrusik">GitHub <span aria-hidden="true">↗</span></a></div></div>
    </div>
  </section>
</div>

</main>

<footer class="site-footer container"><p>© {{ site.time | date: '%Y' }} Paweł Jendrusik</p><p>Backend engineering. Product thinking.</p><a href="#top">Back to top <span aria-hidden="true">↑</span></a></footer>
