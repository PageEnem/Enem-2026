<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Minha Loja - Produtos</title>
  <style>
    body{font-family:Inter,system-ui,Segoe UI,Helvetica,Arial;margin:0;padding:0;background:#f5f6f8;color:#111}
    header{background:white;padding:20px 16px;box-shadow:0 1px 6px rgba(0,0,0,.06)}
    .container{max-width:980px;margin:24px auto;padding:0 16px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px}
    .card{background:white;border-radius:12px;padding:16px;box-shadow:0 6px 18px rgba(12,20,30,.06)}
    .card img{width:100%;border-radius:8px;height:170px;object-fit:cover}
    h1{margin:0;font-size:20px}
    .price{font-weight:700;margin-top:8px}
    .btn{display:inline-block;margin-top:12px;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:700;border:0;cursor:pointer}
    .btn-buy{background:#0b7df0;color:white}
    footer{padding:20px;text-align:center;color:#666;font-size:14px}
    @media (max-width:500px){ .card img{height:140px} }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Minha Loja — Produtos</h1>
    </div>
  </header>

  <main class="container">
    <div class="grid">
      <!-- Produto 1 -->
      <article class="card">
        <img src="https://via.placeholder.com/600x400?text=Produto+1" alt="Produto 1">
        <h2>Produto 1 — Camiseta legal</h2>
        <p>Descrição curta do produto. Tamanhos: P/M/G. Envio 2-4 dias.</p>
        <div class="price">R$ 79,90</div>
        <!-- Troque o href pelo link real do seu checkout -->
        <a class="btn btn-buy" href="LINK_DE_PAGAMENTO_AQUI" rel="noopener" target="_blank">Comprar agora</a>
      </article>

      <!-- Produto 2 -->
      <article class="card">
        <img src="https://via.placeholder.com/600x400?text=Produto+2" alt="Produto 2">
        <h2>Produto 2 — Boné estiloso</h2>
        <p>Descrição curta do boné. Ajustável, envio rápido.</p>
        <div class="price">R$ 49,90</div>
        <a class="btn btn-buy" href="LINK_DE_PAGAMENTO_AQUI" rel="noopener" target="_blank">Comprar agora</a>
      </article>
    </div>

    <section style="margin-top:22px">
      <h3>Link único para toda a loja</h3>
      <p>Se quiser um link único (ex: colocar na bio), crie uma página simples com links para cada produto ou use um encurtador / Linktree.</p>
      <a class="btn" href="https://linktr.ee" target="_blank" rel="noopener">Criar Link Único</a>
    </section>
  </main>

  <footer>
    © Minha Loja • Troque pelas suas informações • Formas de pagamento: Pix, Cartão, Boleto
  </footer>
</body>
</html>
