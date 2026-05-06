---
layout: default
title: "Home"
description: "Community-led co-investment. Experienced leads. Same terms for everyone."
---

<div class="container">

  <div class="home-hero">
    <span class="kicker">Community v0.1 prototype</span>
    <h1>Three deals open. The lead investors<br>are putting in their own money.<br><em>So are we.</em></h1>
    <p class="home-deck">This is a working prototype of what investor community infrastructure should look like. Every deal you see has a real lead with skin in the game. Every fee is published. Every investor is on the same terms.</p>
  </div>

  <div class="home-section" id="deals">
    <div class="home-section-header">
      <h2>Open deals this week</h2>
      <a href="/#deals" class="home-section-link">View all open deals &rarr;</a>
    </div>

    <div class="deal-grid">
      {% for deal in site.data.deals %}
        {% include deal-card.html deal=deal %}
      {% endfor %}
    </div>
  </div>

  <div class="home-section">
    <div class="home-section-header">
      <h2>What members are talking about</h2>
    </div>

    <div class="threads-list">

      <div class="thread-with-commentary">
        <div class="thread-preview">
          <div class="member-avatar">AM</div>
          <div class="thread-body">
            <span class="thread-deal-tag">Meridian Defense Systems</span>
            <p class="thread-text">"The $40M cap feels high for pre-revenue. Can Sarah walk through the comp set that justified this? I've seen SBIR-backed defense companies priced at $15–25M at the same stage and can't reconcile the difference." — <strong>4 replies</strong>, including a detailed response from the lead investor</p>
            <div class="thread-meta">
              <span>Alex M.</span>
              <span>2 days ago</span>
              <span>4 replies</span>
            </div>
          </div>
        </div>
        {% include commentary.html
          label="Why we're showing this"
          text="Member-led valuation skepticism is the system working. The platform doesn't screen deals for quality. It gives members the information and the lead investor's contact to run their own analysis. This thread already produced a detailed comp set from the lead." %}
      </div>

      <div class="thread-with-commentary">
        <div class="thread-preview">
          <div class="member-avatar">PK</div>
          <div class="thread-body">
            <span class="thread-deal-tag">Common Ground Coffee Co.</span>
            <p class="thread-text">"I found Marcus Webb's previous exit — Equator Coffees sold to private equity in 2021. Pulled the ADA data: they were running 7 locations with $4.2M in revenue at exit. Common Ground's $12M cap implies a 3x premium to that comp. Is the worker-equity model the justification, or is something else going on?" — <strong>6 replies</strong></p>
            <div class="thread-meta">
              <span>Priya K.</span>
              <span>1 day ago</span>
              <span>6 replies</span>
            </div>
          </div>
        </div>
        {% include commentary.html
          label="Why we're showing this"
          text="One member spending two hours on public records produced a valuation anchor that changes the conversation for everyone in the community. This is what community diligence looks like when you give people real information to work with." %}
      </div>

      <div class="thread-with-commentary">
        <div class="thread-preview">
          <div class="member-avatar">DL</div>
          <div class="thread-body">
            <span class="thread-deal-tag">LastMile Broadband</span>
            <p class="thread-text">"I want to push back on whether revenue-share debt is appropriate for retail investors at all. Revenue share means your return is entirely correlated to a single company's operating performance, with no collateral and no fixed interest rate. A rural telecom startup is not a bond. Can Jim explain the downside scenario?" — <strong>9 replies</strong></p>
            <div class="thread-meta">
              <span>David L.</span>
              <span>3 days ago</span>
              <span>9 replies</span>
            </div>
          </div>
        </div>
        {% include commentary.html
          label="Why we're showing this"
          text="Some deals should be questioned at the structural level, not just the valuation level. A member raising a legitimate concern about whether a security type is appropriate for retail investors is the community functioning as a check. We don't moderate this out." %}
      </div>

    </div>
  </div>

  <div class="home-section">
    <div class="home-section-header">
      <h2>From the research desk</h2>
      <a href="/research/" class="home-section-link">All research &rarr;</a>
    </div>

    <div class="research-list">
      <div class="research-item">
        <a href="/research/">The 36-platform map: who's winning, who's quietly dying</a>
        <span class="research-item-meta">Research Desk &middot; May 2026</span>
      </div>
      <div class="research-item">
        <a href="/deal/#why-retail-gets-screwed">Why retail investors get screwed: ten structural mechanics</a>
        <span class="research-item-meta">Research Desk &middot; May 2026</span>
      </div>
      <div class="research-item">
        <a href="/research/#equity-crowdfunding">What Wefunder Investor Clubs already does (and where it falls short)</a>
        <span class="research-item-meta">Research Desk &middot; May 2026</span>
      </div>
    </div>
  </div>

</div>

<div class="home-principles-strip">
  <div class="container">
    <div class="home-principles-inner">
      <div class="home-principles-left">
        <span class="kicker">How we operate</span>
        <h2 class="home-principles-heading">Six structural commitments.<br>In writing. Before we have one investor.</h2>
      </div>
      <div class="home-principles-right">
        <ul class="home-principles-list">
          <li>We co-invest on every deal, on the same terms.</li>
          <li>Every fee is published at the deal level.</li>
          <li>Members get the same terms as the lead investor.</li>
          <li>Diligence is real, published, and disputable.</li>
          <li>Bad deals don't get listed, regardless of the fee.</li>
          <li>The community is the product. Not the deal flow.</li>
        </ul>
        <a href="/principles/" class="home-principles-cta">Read our principles &rarr;</a>
      </div>
    </div>
  </div>
</div>

<div class="home-footer-note">
  <div class="container">
    <p>This home page leads with deals and member discussion rather than marketing copy. That's not an aesthetic choice — it's a structural commitment. The community's value comes from the quality of its analysis, not from the platform's promotion of itself. A home page that leads with "democratizing investment" copy is one whose incentives run toward marketing. This one runs toward information.</p>
  </div>
</div>
