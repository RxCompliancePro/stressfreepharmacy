<style>
/* =========================
Global Styles
========================= */
* { box-sizing: border-box; margin:0; padding:0; }
body { font-family: 'Helvetica Neue', Arial, sans-serif; line-height:1.6; color:#333; background-color:#fdfdfd; }
.container { max-width:1200px; margin:0 auto; padding:0 20px; }

/* Hero Section */
.hero-section { background:#e8f0f8; text-align:center; padding:80px 20px; }
.hero-section h1 { font-size:2.8rem; margin-bottom:20px; color:#1a3b5d; }
.hero-section p { font-size:1.2rem; margin-bottom:30px; color:#1a3b5d; }
.btn-primary { display:inline-block; background-color:#1a3b5d; color:#fff; padding:12px 28px; text-decoration:none; border-radius:6px; font-weight:bold; transition: background-color 0.3s; }
.btn-primary:hover { background-color:#0f2340; }

/* Services Section */
.services-section { padding:60px 20px; background-color:#fff; }
.services-section h2 { text-align:center; margin-bottom:50px; font-size:2rem; color:#1a3b5d; }
.services-grid { display:grid; grid-template-columns:repeat(auto-fit, minmax(300px,1fr)); gap:30px; }
.service { background-color:#f5f7fa; padding:30px; border-radius:8px; border:1px solid #e1e5eb; }
.service h3 { color:#1a3b5d; margin-bottom:15px; font-size:1.5rem; }
.service p { margin-bottom:15px; }
.service ul { list-style-type: disc; margin-left:20px; margin-bottom:20px; }
.btn-secondary { display:inline-block; background-color:#4a90e2; color:#fff; padding:10px 22px; text-decoration:none; border-radius:6px; font-weight:bold; transition: background-color 0.3s; }
.btn-secondary:hover { background-color:#357abd; }

/* Benefits Section */
.benefits-section { padding:60px 20px; background-color:#e8f0f8; text-align:center; }
.benefits-section h2 { font-size:2rem; margin-bottom:20px; color:#1a3b5d; }
.benefits-section p { font-size:1.1rem; margin-bottom:40px; }
.benefits-grid { display:grid; grid-template-columns:repeat(auto-fit, minmax(250px,1fr)); gap:30px; }
.benefit h3 { font-size:1.3rem; margin-bottom:10px; color:#1a3b5d; }
.benefit p { font-size:1rem; color:#333; }

/* Process Section */
.process-section { padding:60px 20px; background-color:#fff; text-align:center; }
.process-section h2 { font-size:2rem; margin-bottom:40px; color:#1a3b5d; }
.process-steps { display:grid; grid-template-columns:repeat(auto-fit, minmax(250px,1fr)); gap:30px; }
.step h3 { color:#1a3b5d; margin-bottom:10px; }
.step p { color:#333; }

/* CTA Section */
.cta-section { background-color:#1a3b5d; color:#fff; padding:80px 20px; text-align:center; }
.cta-section h2 { font-size:2rem; margin-bottom:20px; }
.cta-section p { font-size:1.1rem; margin-bottom:30px; }
.cta-buttons a { display:inline-block; margin:10px; background-color:#4a90e2; color:#fff; padding:12px 28px; text-decoration:none; border-radius:6px; font-weight:bold; transition:background-color 0.3s; }
.cta-buttons a:hover { background-color:#357abd; }
.footer-note { font-size:0.9rem; margin-top:20px; font-style:italic; color:#cce0f5; }

/* Responsive */
@media(max-width:768px){
.hero-section h1{font-size:2rem;}
.services-grid, .benefits-grid, .process-steps{grid-template-columns:1fr;}
}
</style>
