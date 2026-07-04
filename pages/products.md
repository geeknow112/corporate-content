<div class="biz-hero-box">
  <h1>製品・サービス</h1>
  <p>Products & Services</p>
</div>

<h2 class="biz-section-title">製品</h2>

<div class="biz-product-grid">
  <div class="biz-product-card">
    <div class="biz-product-icon">🤖</div>
    <div class="biz-product-name">RPA WEBツール</div>
  </div>
  <div class="biz-product-card">
    <div class="biz-product-icon">📊</div>
    <div class="biz-product-name">アクセスログ解析ツール</div>
  </div>
  <div class="biz-product-card">
    <div class="biz-product-icon">👥</div>
    <div class="biz-product-name">カスタマーDB分析ツール</div>
  </div>
  <div class="biz-product-card">
    <div class="biz-product-icon">📦</div>
    <div class="biz-product-name">商品在庫管理WEBツール</div>
  </div>
  <div class="biz-product-card">
    <div class="biz-product-icon">💰</div>
    <div class="biz-product-name">財務管理WEBツール</div>
  </div>
</div>

<h2 class="biz-section-title">サービス</h2>

<ul class="biz-check-list">
  <li>DX推進支援</li>
  <li>IaaS導入・環境構築支援</li>
  <li>社内システム・クラウドツール保守支援</li>
  <li>情報システム業務代行</li>
  <li>HP作成支援</li>
  <li>助成金・補助金等の獲得支援</li>
</ul>

<div class="biz-cta-box">
  <h2>お問い合わせ</h2>
  <p>製品・サービスの詳細やデモのご依頼など、お気軽にご相談ください。</p>
  <p><a href="/contact/" class="biz-cta-btn">お問い合わせフォーム</a></p>
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
.article h2.biz-section-title {
  display: inline-block;
  background: linear-gradient(135deg, #19448e 0%, #2a5caa 100%);
  color: #fff;
  padding: 0.3em 1em;
  border-radius: 4px;
  font-size: 1.1em;
  margin: 1.5em 0 0.8em 0;
}
.biz-product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 1em;
  margin: 1em 0;
}
.biz-product-card {
  text-align: center;
  padding: 1.5em 1em;
  background: linear-gradient(135deg, #f8f9fa 0%, #fff 100%);
  border-radius: 8px;
  border-bottom: 3px solid #19448e;
  transition: transform 0.2s ease;
}
.biz-product-card:hover {
  transform: translateY(-3px);
}
.biz-product-icon {
  font-size: 2em;
  margin-bottom: 0.3em;
}
.biz-product-name {
  font-size: 0.9em;
  font-weight: bold;
  color: #333;
}
.biz-check-list {
  list-style: none;
  margin: 1em 0;
  padding: 0;
}
.biz-check-list li {
  padding: 0.6em 0 0.6em 1.8em;
  position: relative;
  border-bottom: 1px dashed #ddd;
}
.biz-check-list li::before {
  content: "✓";
  position: absolute;
  left: 0;
  font-weight: bold;
  color: #19448e;
}
.biz-cta-box {
  text-align: center;
  padding: 2em;
  background: linear-gradient(135deg, #f0f4f8 0%, #e8eef5 100%);
  border-radius: 8px;
  margin-top: 2em;
  border: 1px solid #d0dae8;
}
.biz-cta-box h2 {
  margin: 0 0 0.5em 0;
  color: #19448e;
}
.biz-cta-btn {
  display: inline-block;
  padding: 0.8em 2em;
  background: linear-gradient(135deg, #19448e 0%, #2a5caa 100%);
  color: #fff;
  text-decoration: none;
  border-radius: 4px;
  font-weight: bold;
}
</style>
