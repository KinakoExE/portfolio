---
title: "About"
showToc: false
---

<style>
.profile-container {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  flex-wrap: wrap;

  background-color: #262626;
  padding: 1.5rem 2rem;
  border-radius: 1rem;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);

  border: 1px solid rgba(255,255,255,0.05);
  transition: all 0.3s ease;

}

.profile-container:hover {
  box-shadow: 0 6px 20px rgba(0,0,0,0.5);
  transform: translateY(-3px);
  border-color: rgba(255,255,255,0.1);
}

.profile-container img {
  border-radius: 50%;
  max-width: 180px;
  height: auto;
  border: 3px solid #333;
}

.profile-details {
  flex: 1;
  min-width: 240px;
  font-size: 1.1rem;
  color: #ccc;
}

.timeline {
  margin-top: 2rem;
}

.timeline h2 {
  font-size: 1.4rem;
  margin-bottom: 0.8rem;
}

.timeline-item {
  margin-bottom: 1rem;
}

.timeline-year {
  font-weight: bold;
  color: #555;
}

.certifications {
  margin-top: 2rem;
  background-color: #262626; /* 経歴カードと同じ背景色 */
  padding: 1.5rem 2rem;
  border-radius: 1rem;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  border: 1px solid rgba(255,255,255,0.05);
}

.certifications h2 {
  font-size: 1.4rem;
  margin-bottom: 1rem;
}

.certifications ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.certifications li {
  padding: 0.5rem 0;
  border-bottom: 1px solid rgba(255,255,255,0.05);
}

.certifications li:last-child {
  border-bottom: none;
}

.certifications .cert-name {
  font-weight: bold;
  color: #fff;
}

.certifications .cert-org {
  font-size: 0.9rem;
  color: #aaa;
}

.certifications .cert-year {
  font-size: 0.85rem;
  color: #777;
}
</style>

<div class="profile-container">
  <img src="/images/icon.jpg" alt="kinako" />

  <div class="profile-details">
    <p>Hello👋</p>
    <p>I'm just a Red Team Operator in 🇯🇵</p>
  </div>
</div>

<div class="timeline">
  <h2>Job History</h2>

  <div class="timeline-item">
    <div class="timeline-year">2022 - Present</div>
    <div>Red Team Operator at a cybersecurity firm</div>
    <div>Active Directory audit, EDR bypass, Malware development for simulated attack.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2020 - 2022</div>
    <div>Web Developer at a fintech company.</div> <div>JServer-side development using Ruby on Rails, Golang, AWS, Terraform</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2020</div>
    <div>Bachelor of Arts in Economics</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2019</div>
    <div>Began studying cybersecurity from scratch, without even knowing what Linux was at that time...</div>
  </div>
</div>


<div class="certifications">
  <h2>Certifications</h2>
  <ul>
    <li>
      <div class="cert-name">CARTP</div>
      <div class="cert-org">Altered Security</div>
      <div class="cert-year">2024</div>
    </li>
    <li>
      <div class="cert-name">OSCP, OSWE, OSED, OSEP, OSCE3</div>
      <div class="cert-org">Offensive Security</div>
      <div class="cert-year">2023 - 2024</div>
    </li>
  </ul>
</div>