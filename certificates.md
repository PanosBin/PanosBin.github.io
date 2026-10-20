---
layout: default
title: Certificates
permalink: /certificates/
description: "Professional certificates and certifications of Panagiotis Binikos."
---

<div class="section-header">
  <h1>Certificates</h1>
</div>

<div class="certificates-grid">

  <div class="cert-card">
    <div class="cert-year">2026</div>
    <div class="cert-content">
      <h3>Cybersecurity Lab</h3>
      <div class="cert-issuer"><i class="fas fa-building" aria-hidden="true"></i> Code.Hub</div>
      <p class="cert-desc">Enterprise Azure Security &amp; Zero Trust Deployment. Designed a Zero Trust cloud infrastructure using Azure with comprehensive identity and access management controls.</p>
      <div class="cert-meta">
        <span class="cert-id"><i class="fas fa-hashtag" aria-hidden="true"></i> 26C0110258</span>
      </div>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-year">2025</div>
    <div class="cert-content">
      <h3>CompTIA Security+ (SY0-701) Bootcamp</h3>
      <div class="cert-issuer"><i class="fas fa-building" aria-hidden="true"></i> Udemy</div>
      <p class="cert-desc">Security fundamentals training covering threats and vulnerabilities, security architecture, operations, incident response, and governance, risk and compliance.</p>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-year">2022</div>
    <div class="cert-content">
      <h3>ReGeneration Initiative: Upskilling Greek Youth for the Digital Era</h3>
      <div class="cert-issuer"><i class="fas fa-building" aria-hidden="true"></i> Code.Hub</div>
      <p class="cert-desc">Intensive upskilling program in Microsoft technologies and digital skills, preparing participants for roles in the tech sector.</p>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-year">2021</div>
    <div class="cert-content">
      <h3>The Data Science Course 2021: Complete Data Science Bootcamp</h3>
      <div class="cert-issuer"><i class="fas fa-building" aria-hidden="true"></i> Udemy</div>
      <p class="cert-desc">Comprehensive data science training covering statistics, Python, data preprocessing, and machine learning fundamentals.</p>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-year">2020</div>
    <div class="cert-content">
      <h3>4th ECB Simulation Conference</h3>
      <div class="cert-issuer"><i class="fas fa-building" aria-hidden="true"></i> Get_Involved</div>
      <p class="cert-desc">Simulated the European Central Bank&rsquo;s Governing Council, analyzing economic data and debating monetary policy decisions.</p>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-year">2020</div>
    <div class="cert-content">
      <h3>Blockchain and Cryptocurrencies Workshop</h3>
      <div class="cert-issuer"><i class="fas fa-building" aria-hidden="true"></i> Get_Involved</div>
      <p class="cert-desc">Workshop on blockchain technology fundamentals, cryptocurrencies, and their applications in finance and business.</p>
    </div>
  </div>

</div>

<style>
.certificates-grid {
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
  margin-top: 2rem;
}

.cert-card {
  display: grid;
  grid-template-columns: 80px 1fr;
  gap: 1.5rem;
  padding: 1.5rem 1.75rem;
  border: 1px solid #e4e4e7;
  border-radius: 14px;
  background: #fff;
  transition: all .3s cubic-bezier(.22,1,.36,1);
}

.cert-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 32px rgba(0,0,0,.08);
  border-color: rgba(37,99,235,.25);
}

.cert-year {
  font-size: 0.82rem;
  font-weight: 700;
  color: #2563eb;
  padding-top: 0.15rem;
  font-variant-numeric: tabular-nums;
}

.cert-content h3 {
  margin: 0 0 0.4rem;
  font-size: 1.05rem;
  font-weight: 700;
}

.cert-issuer {
  font-size: 0.85rem;
  color: #71717a;
  margin-bottom: 0.6rem;
  display: flex;
  align-items: center;
  gap: 0.4rem;
}

.cert-issuer i {
  color: #2563eb;
  font-size: 0.75rem;
}

.cert-desc {
  font-size: 0.88rem;
  color: #71717a;
  line-height: 1.6;
  margin: 0 0 0.5rem;
}

.cert-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 0.5rem;
}

.cert-id {
  font-size: 0.75rem;
  color: #a1a1aa;
  display: flex;
  align-items: center;
  gap: 0.3rem;
}

.cert-id i {
  font-size: 0.65rem;
}

@media (max-width: 480px) {
  .cert-card {
    grid-template-columns: 1fr;
    gap: 0.3rem;
  }
}

/* Dark mode */
[data-theme="dark"] .cert-card {
  background: #18181b;
  border-color: #27272a;
}
[data-theme="dark"] .cert-card:hover {
  box-shadow: 0 8px 32px rgba(0,0,0,.5);
  border-color: rgba(96,165,250,.35);
}
[data-theme="dark"] .cert-year { color: #60a5fa; }
[data-theme="dark"] .cert-content h3 { color: #f4f4f5; }
[data-theme="dark"] .cert-issuer { color: #a1a1aa; }
[data-theme="dark"] .cert-issuer i { color: #60a5fa; }
[data-theme="dark"] .cert-desc { color: #a1a1aa; }
[data-theme="dark"] .cert-id { color: #71717a; }
</style>
