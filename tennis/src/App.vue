<script></script>

<template>
  <header>
    <div class="col-3">
      <img
        id="logo"
        src="https://i.pinimg.com/originals/4a/17/df/4a17df51b352d1430c5c6ad2476da93a.jpg"
        alt=""
      />
    </div>

    <div class="col-9" id="titulo-principal">
      <h1>Sneakers</h1>
    </div>

    <nav class="col-12">
      <ul>
        <li>Home</li>
        <li>Promoções</li>
        <li>Feminino</li>
        <li>Masculino</li>
      </ul>
    </nav>
  </header>

  <main class="col-9">
    <section class="col-12" id="produtos">
      <h4>DESTAQUES</h4>
      <article class="col-6 destaque">
        <h4>Jordan</h4>
        <div class="col-12">
          <img
            src="https://www.aj1classic.ru/66124-large_default/air-jordan-1-mid-se-satin-smoke-grey-852542-011-grey.jpg"
            alt=""
          />
        </div>
        <br />
        <br />
        <h6>
          Jordan Air Max 12 <br />
          Masculino Adulto <br />
          R$499,90
        </h6>
      </article>

      <article class="col-6 destaque2">
        <h4>Nike</h4>
        <div class="col-12">
          <img
            src="https://th.bing.com/th/id/R.eae66a2736668b5208f3d1a9e9fd2b64?rik=DpJGowQIZAzdtw&pid=ImgRaw&r=0"
            alt=""
          />
        </div>
        <h6>
          Nike Yzzi <br />
          Feminino <br />
          R$549,90
        </h6>
      </article>
    </section>

    <section class="col-12" id="descontos">
      <h5>PROMOÇÕES</h5>
      <article class="col-4 adidas">
        <h4>Adidas</h4>
        <div class="col-12">
          <img
            src="https://th.bing.com/th/id/R.f3a91298da0d6a23a1b19250c3b8ab7d?rik=hbv6Ee3ewVhglQ&pid=ImgRaw&r=0"
            alt=""
          />
        </div>
        <div>
          <p>
            Adidas SuperStar Masculino <br />
            R$799,90
          </p>
        </div>
      </article>
      <article class="col-4 pulma">
        <h4>Pulma</h4>
        <div class="col-12">
          <img
            src="https://th.bing.com/th/id/R.331e4b6c3de92f642406a43291f02edf?rik=CawEhJ8xVq1%2bJQ&pid=ImgRaw&r=0"
            alt=""
          />
        </div>
        <div>
          <p>
            Pulma Shoes Masculino <br />
            R$ 399,90
          </p>
        </div>
      </article>

      <article class="col-4 olympikus">
        <h4>Olympikus</h4>
        <div class="col-12">
          <img
            src="data:image/jpeg;base64,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"
            alt=""
          />
        </div>
        <div>
          <p>
            Olympikus Vênus 2 Masculino <br />
            R$ 178,00
          </p>
        </div>
      </article>
    </section>
  </main>

  <aside class="col-3 propaganda">
    <img
      src="https://th.bing.com/th/id/R.eb58ba7d756591a00e8ebafd73170c31?rik=KA8OYBwSpwHD%2fQ&pid=ImgRaw&r=0"
      alt=""
    />
  </aside>

  <footer class="col-12 footer">
    <p>
      BrasilPolítica de PrivacidadeTermos de Uso © 2021 . Todos os direitos
      reservados. Fisia Comércio de Produtos Esportivos Ltda - CNPJ:
      59.546.515/0045-55 Rodovia Fernão Dias, S/N Km 947.5 - Galpão Modulo 3640
      - CEP 37640-903 - Extrema - MG.
    </p>
  </footer>
</template>

<style>
@import "./assets/base.css";

body {
  background-image: url(https://image.freepik.com/vetores-gratis/fundo-de-desenho-abstrato-com-gradiente-de-azul-e-roxo_1048-13167.jpg);
  background-repeat: no-repeat;
  background-size: 200%;
}
</style>
