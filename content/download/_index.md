---
title: Download
toc: false
---

<style>
.dl-hero {
  text-align: center;
  padding: 0 0 2rem;
}
.dl-hero h2 {
  font-size: 2rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
}
.dl-hero p {
  color: #9ca3af;
  font-size: 1.1rem;
  max-width: 600px;
  margin: 0 auto;
}
.dl-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
  margin: 2rem 0 3rem;
}
@media (min-width: 768px) {
  .dl-grid {
    grid-template-columns: 1fr 1fr;
  }
}
.dl-card {
  border: 1px solid #2d3748;
  border-radius: 12px;
  padding: 2rem;
  background: #1a1f2e;
  transition: border-color 0.2s;
}
.dl-card:hover {
  border-color: #4a90d9;
}
.dl-card-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}
.dl-card-icon {
  width: 48px;
  height: 48px;
  border-radius: 10px;
  background: #2d3748;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.5rem;
  flex-shrink: 0;
}
.dl-card-title {
  font-size: 1.25rem;
  font-weight: 600;
}
.dl-card-meta {
  font-size: 0.85rem;
  color: #6b7280;
}
.dl-card-desc {
  color: #9ca3af;
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 1.5rem;
}
.dl-card-footer {
  display: flex;
  gap: 0.75rem;
  flex-wrap: wrap;
  align-items: center;
}
.dl-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.6rem 1.5rem;
  border-radius: 8px;
  font-weight: 600;
  font-size: 0.95rem;
  text-decoration: none;
  transition: opacity 0.2s;
}
.dl-btn:hover {
  opacity: 0.85;
}
.dl-btn-primary {
  background: #4a90d9;
  color: #fff;
}
.dl-btn-secondary {
  background: #2d3748;
  color: #d1d5db;
}
.dl-section {
  margin: 3rem 0;
}
.dl-section h3 {
  font-size: 1.4rem;
  font-weight: 600;
  margin-bottom: 1.25rem;
}
.dl-verify-steps {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.5rem;
  margin-top: 1.5rem;
}
@media (min-width: 768px) {
  .dl-verify-steps {
    grid-template-columns: 1fr 1fr 1fr;
  }
}
.dl-step {
  border: 1px solid #2d3748;
  border-radius: 10px;
  padding: 1.25rem;
  background: #1a1f2e;
}
.dl-step-num {
  display: inline-block;
  width: 28px;
  height: 28px;
  line-height: 28px;
  text-align: center;
  border-radius: 50%;
  background: #4a90d9;
  color: #fff;
  font-size: 0.85rem;
  font-weight: 700;
  margin-bottom: 0.75rem;
}
.dl-step-title {
  font-weight: 600;
  margin-bottom: 0.5rem;
}
.dl-step code {
  display: block;
  background: #111827;
  padding: 0.5rem 0.75rem;
  border-radius: 6px;
  font-size: 0.8rem;
  overflow-x: auto;
  margin-top: 0.5rem;
  color: #d1d5db;
}
.dl-req-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 1rem;
}
.dl-req-table th,
.dl-req-table td {
  text-align: left;
  padding: 0.75rem 1rem;
  border-bottom: 1px solid #2d3748;
}
.dl-req-table th {
  color: #9ca3af;
  font-weight: 600;
  font-size: 0.85rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}
.dl-req-table td {
  color: #d1d5db;
}
.dl-prev {
  text-align: center;
  padding: 2rem 0;
  color: #9ca3af;
}
.dl-prev a {
  color: #4a90d9;
  text-decoration: none;
}
.dl-prev a:hover {
  text-decoration: underline;
}
</style>

<div class="dl-hero">
  <h2>Get Ion Linux</h2>
  <p>A Hyprland-first Linux distribution built for performance. Download the latest release and get started.</p>
</div>

<div class="dl-grid">

  <div class="dl-card">
    <div class="dl-card-header">
      <div class="dl-card-icon">{{< icon name="desktop-computer" >}}</div>
      <div>
        <div class="dl-card-title">Ion Linux Desktop</div>
        <div class="dl-card-meta">v2026.04.11 &middot; x86_64 &middot; Hyprland</div>
      </div>
    </div>
    <div class="dl-card-desc">
      Hyprland-first desktop experience with a fully configured tiling Wayland compositor. Ships with sensible defaults, curated applications, and development tools out of the box.
    </div>
    <div class="dl-card-footer">
      <a href="http://download.ionlinux.org/ionlinux-2026.04.11-x86_64/ionlinux-2026.04.11-x86_64.iso" class="dl-btn dl-btn-primary">Download ISO</a>
      <a href="http://download.ionlinux.org/ionlinux-2026.04.11-x86_64/ionlinux-2026.04.11-x86_64.iso.sig" class="dl-btn dl-btn-secondary">Signature (.sig)</a>
    </div>
  </div>

  <div class="dl-card">
    <div class="dl-card-header">
      <div class="dl-card-icon">{{< icon name="shield-check" >}}</div>
      <div>
        <div class="dl-card-title">Release Details</div>
        <div class="dl-card-meta">Signed &middot; Verified &middot; Rolling</div>
      </div>
    </div>
    <div class="dl-card-desc">
      All releases are GPG-signed for authenticity. Powered by Hyprland on Wayland for smooth animations, dynamic tiling, and a modern desktop. Rolling release model keeps you on the latest packages.
    </div>
    <div class="dl-card-footer">
      <a href="/docs/getting-started" class="dl-btn dl-btn-secondary">Getting Started Guide</a>
      <a href="/docs/installation" class="dl-btn dl-btn-secondary">Installation Guide</a>
    </div>
  </div>

</div>

<hr style="border-color: #2d3748; margin: 2rem 0;">

<div class="dl-section">
  <h3>Verify Your Download</h3>
  <p style="color: #9ca3af;">Confirm your ISO is authentic and untampered before installing.</p>

  <div class="dl-verify-steps">
    <div class="dl-step">
      <div class="dl-step-num">1</div>
      <div class="dl-step-title">Import the GPG key</div>
      <code>gpg --keyserver keyserver.ubuntu.com --recv-keys 15F05CC470C7F468</code>
    </div>
    <div class="dl-step">
      <div class="dl-step-num">2</div>
      <div class="dl-step-title">Verify the signature</div>
      <code>gpg --verify ionlinux-2026.04.11-x86_64.iso.sig ionlinux-2026.04.11-x86_64.iso</code>
    </div>
    <div class="dl-step">
      <div class="dl-step-num">3</div>
      <div class="dl-step-title">Confirm the fingerprint</div>
      <code>EB13 BC87 D0D0 B08C 4CA9 42F4 15F0 5CC4 70C7 F468</code>
    </div>
  </div>
</div>

<hr style="border-color: #2d3748; margin: 2rem 0;">

<div class="dl-section">
  <h3>System Requirements</h3>

  <table class="dl-req-table">
    <thead>
      <tr>
        <th>Component</th>
        <th>Minimum</th>
        <th>Recommended</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>CPU</td>
        <td>x86_64, 2 cores</td>
        <td>x86_64, 4+ cores</td>
      </tr>
      <tr>
        <td>RAM</td>
        <td>1 GB</td>
        <td>4 GB</td>
      </tr>
      <tr>
        <td>Disk</td>
        <td>8 GB</td>
        <td>20 GB</td>
      </tr>
      <tr>
        <td>Graphics</td>
        <td>VESA compatible</td>
        <td>GPU with Vulkan support</td>
      </tr>
    </tbody>
  </table>
</div>

<hr style="border-color: #2d3748; margin: 2rem 0;">

<div class="dl-prev">
  All previous releases and changelogs are available on the <a href="https://sourceforge.net/projects/ionlinux/files/">SourceForge files page</a>.
</div>
