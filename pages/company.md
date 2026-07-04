<div class="biz-hero-box">
  <h1>会社情報</h1>
  <p>About us - Trident Capital Symbiosis</p>
</div>

<div class="biz-menu-grid">
  <a class="biz-menu-card" href="/overview/">
    <span class="biz-menu-icon">🏢</span>
    <span class="biz-menu-text">会社概要</span>
  </a>
  <a class="biz-menu-card" href="/business/">
    <span class="biz-menu-icon">💼</span>
    <span class="biz-menu-text">事業内容</span>
  </a>
  <a class="biz-menu-card" href="/history/">
    <span class="biz-menu-icon">📜</span>
    <span class="biz-menu-text">沿革</span>
  </a>
  <a class="biz-menu-card" href="/access/">
    <span class="biz-menu-icon">📍</span>
    <span class="biz-menu-text">アクセス</span>
  </a>
</div>

<style>
.biz-hero-box {
  text-align: center;
  padding: 3em 1.5em;
  color: #fff;
  border-radius: 0;
  margin: -20px -20px 2em -20px;
  background: linear-gradient(135deg, #0a1628 0%, #19448e 50%, #2a5caa 100%);
  position: relative;
  overflow: hidden;
}
.biz-hero-box::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-image: 
    radial-gradient(circle at 20% 80%, rgba(255,255,255,0.1) 0%, transparent 50%),
    radial-gradient(circle at 80% 20%, rgba(255,255,255,0.08) 0%, transparent 40%),
    radial-gradient(circle at 40% 40%, rgba(255,255,255,0.05) 0%, transparent 30%);
  pointer-events: none;
}
.biz-hero-box h1 {
  font-size: 2em;
  margin: 0 0 0.5em 0;
  color: #fff;
  position: relative;
  letter-spacing: 0.05em;
}
.biz-hero-box p {
  margin: 0;
  opacity: 0.95;
  position: relative;
}
.biz-menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 1.2em;
  margin: 1.5em 0;
}
.biz-menu-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 2em 1em;
  border: 2px solid #19448e;
  border-radius: 8px;
  color: #19448e;
  font-weight: bold;
  text-decoration: none;
  transition: all 0.3s ease;
  background: #fff;
}
.biz-menu-card:hover {
  background: linear-gradient(135deg, #19448e 0%, #2a5caa 100%);
  color: #fff;
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(25, 68, 142, 0.3);
}
.biz-menu-icon {
  font-size: 2em;
  margin-bottom: 0.3em;
}
.biz-menu-text {
  font-size: 1.1em;
}
</style>
