 <style>
   :root{
      --bg:#f5f7fb;
      --page:#ffffff;
      --card:#ffffff;
      --text:#111827;
      --muted:#6b7280;
      --line:#eceff3;
      --link:#4338ca;
      --shadow:0 20px 60px rgba(15,23,42,0.06);
      --button-top:#37456a;
      --button-bottom:#26334f;
    }

    *{
      box-sizing:border-box;
    }

    body{
      margin:0;
      font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
      background:var(--bg);
      color:var(--text);
      padding:56px 20px 80px;
      line-height:1.82;
    }

    .page-wrap{
      max-width:700px;
      margin:0 auto;
      padding:56px 40px 40px;
      background:var(--page);
      border-radius:28px;
      box-shadow:var(--shadow);
    }

    .container{
      max-width:680px;
      margin:0 auto;
    }

    .hero{
      max-width:560px;
      margin:0 auto 42px;
    }

    h1{
      font-size:36px;
      line-height:1.08;
      letter-spacing:-0.03em;
      margin:0 0 16px;
      color:var(--text);
    }

    h2{
      font-size:22px;
      line-height:1.3;
      letter-spacing:-0.02em;
      margin:0 0 14px;
      color:var(--text);
    }

    h3{
      font-size:16px;
      line-height:1.45;
      letter-spacing:-0.01em;
      margin:0 0 10px;
      color:var(--text);
    }

    .subtitle{
      max-width:480px;
      font-size:18px;
      line-height:1.95;
      color:var(--muted);
      margin:0;
    }

    .card{
      width:100%;
      max-width:620px;
      margin:28px auto 0;
      background:rgba(255,255,255,0.96);
      border:1px solid var(--line);
      border-radius:24px;
      padding:26px 28px;
      box-shadow:0 10px 28px rgba(15,23,42,0.04);
    }

    .overview-card{
      margin-top:0;
      text-align:center;
    }

    .overview-card h2{
      margin-bottom:18px;
    }

    .overview-table-wrap{
      max-width:100%;
      margin:0 auto;
    }

    .overview-card table{
      width:100%;
      border-collapse:collapse;
      table-layout:fixed;
      margin-top:0;
      font-size:15px;
    }

    .overview-card td{
      padding:12px 6px;
      border-bottom:1px solid #eef1f4;
      vertical-align:middle;
      color:#374151;
      text-align:left;
    }

    .overview-card tr:last-child td{
      border-bottom:none;
    }

    .overview-card td:first-child{
      width:25%;
      color:var(--muted);
    }

    .overview-card td:nth-child(2){
      width:37.5%;
    }

    .overview-card td:nth-child(3){
      width:37.5%;
    }

    .reading-section{
      max-width:560px;
      margin:64px auto 0;
    }

    .reading-section h2{
      margin-bottom:16px;
    }

    .reading-section p{
      max-width:500px;
      font-size:17px;
      line-height:1.95;
      color:#4b5563;
      margin:0 0 18px;
    }

    .cta-card{
  text-align:center;
  padding:30px 32px;
  background:#f3f4f6;
  border:1px solid #eceff3;
}

    .cta-card p{
      max-width:46ch;
      margin:0 auto 16px;
      font-size:16px;
      line-height:1.9;
      color:#4b5563;
    }

    .cta-button{
      display:inline-block;
      background:linear-gradient(180deg,var(--button-top) 0%, var(--button-bottom) 100%);
      color:#ffffff !important;
      text-decoration:none;
      font-weight:600;
      padding:13px 24px;
      border-radius:14px;
      box-shadow:0 10px 22px rgba(38,51,79,0.22);
    }

    .faq-section{
      max-width:560px;
      margin:64px auto 0;
    }

    .faq-wrap{
      max-width:500px;
    }

    .faq-title{
      margin:0 0 22px;
    }

    .faq-item{
      padding:16px 0;
      border-bottom:1px solid #e7ebf0;
    }

    .faq-item:last-child{
      border-bottom:none;
      padding-bottom:0;
    }

    .faq-item h3{
      max-width:500px;
      margin:0 0 10px;
    }

    .faq-item p{
      max-width:500px;
      font-size:16px;
      line-height:1.9;
      color:#4b5563;
      margin:0;
    }

    .nav-card{
      text-align:center;
      padding:30px 32px;
    }

    .nav-card h2{
      margin-bottom:18px;
    }

    .nav-links{
      display:flex;
      flex-direction:column;
      gap:14px;
      align-items:center;
    }

    .nav-links a{
      color:var(--link);
      text-decoration:none;
      font-weight:500;
    }

    .community-card{
      text-align:center;
      padding:32px 32px;
    }

    .community-card p{
      max-width:48ch;
      margin:0 auto 14px;
      font-size:16px;
      line-height:1.9;
      color:#4b5563;
    }

    .community-list{
      list-style:none;
      padding:0;
      margin:18px 0 22px;
      color:var(--muted);
      font-size:15px;
    }

    .community-list li{
      margin:8px 0;
    }

    .community-actions{
      display:flex;
      gap:12px;
      justify-content:center;
      flex-wrap:wrap;
      margin-top:4px;
    }

    .community-button{
      display:inline-block;
      background:linear-gradient(180deg,var(--button-top) 0%,var(--button-bottom) 100%);
      color:#fff !important;
      text-decoration:none;
      font-weight:600;
      padding:12px 22px;
      border-radius:12px;
      box-shadow:0 10px 22px rgba(38,51,79,0.22);
    }

    .community-link{
      display:inline-block;
      color:var(--link);
      text-decoration:none;
      font-weight:500;
      padding:12px 4px;
    }

    .community-note{
      margin-top:12px;
      font-size:14px;
      color:#9ca3af;
    }

    .back-wrap{
      text-align:left;
      max-width:560px;
      margin:30px auto 0;
    }

    .back{
      display:inline-block;
      color:#6366f1;
      text-decoration:none;
      font-weight:500;
    }

    @media (max-width:640px){
      body{
        padding:20px 12px 48px;
      }

      .page-wrap{
        padding:28px 18px 28px;
        border-radius:20px;
      }

      .container,
      .hero,
      .reading-section,
      .faq-section{
        max-width:100%;
      }

      h1{
        font-size:31px;
      }

      h2{
        font-size:20px;
      }

      .subtitle{
        max-width:100%;
        font-size:16px;
        line-height:1.88;
      }

      .card{
        max-width:100%;
        border-radius:18px;
        padding:22px 18px;
      }

      .overview-card td{
        padding:12px 4px;
        font-size:14px;
      }

      .reading-section p,
      .faq-item h3,
      .faq-item p{
        max-width:100%;
      }

      .faq-wrap{
        max-width:100%;
      }

      .community-actions{
        flex-direction:column;
        align-items:center;
      }

      .back-wrap{
        max-width:100%;
      }
    }
  
  </style>
