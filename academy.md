---
title: Academy
---

<style>
  @media (min-width: 800px) {
    .phone-frame-container--tilted {
      margin-top: -100px;
      position: relative;
      perspective: 1000px;

      .phone-frame {
        transform-style: preserve-3d;
        transform: rotateX(15deg) rotateY(-15deg);
      }
    }
  }

  .phone-frame-container--span {
    max-width: 260px;
    margin: 24px auto;
  }

  @media (min-width: 800px) {
    .phone-frame-container--span {
      order: 1;
      margin: -80px 0 0;
      flex: 0 0 260px;
    }
  }
</style>

<div class="grid center grid--laptop--50 gap-5 p-5">
  <div class="span--desktop--2">
    <img src="/assets/img/team/todas.jpg" alt="Time EmpreendaPretas">

    <h2>Transforme Desafios em Conquistas</h2>

    <p>
      O EmpreendaPretas Academy é uma plataforma de educação e mentoria criada para apoiar mulheres negras em suas
      jornadas empreendedoras. Aprenda no seu ritmo, com aulas gravadas, mentoria de especialistas e uma comunidade de
      apoio.
    </p>

    <p>
      <a href="https://pay.kiwify.com.br/JLy8qir" target="_blank" class="button">
        Acesse o EmpreendaPretas Academy
      </a>
    </p>
  </div>

  <div class="phone-frame-container--tilted">
    <div class="phone-frame">
      <video src="/assets/video/empreendapretas-academy-demo.mp4" muted loop autoplay preload="auto"></video>
    </div>
  </div>
</div>

## O Que Você Vai Encontrar no EmpreendaPretas Academy?

<div class="vertical gap-3 my-5">
  {% for member in site.data.team %}{% capture img_classname %}{% cycle "pull-right", "" %}{% endcapture %}
  <div class="wrapper horizontal--laptop center gap-3">
    <img src="{{ member.img.src }}" alt="{{ member.img.alt }}" width="140" class="{{ img_classname }}" />
    <p>{{ member.description }}</p>
  </div>
  {% endfor %}
</div>

## Por Que Assinar o EmpreendaPretas Academy?

**Aulas gravadas de fácil acesso:** Estude no seu ritmo, de onde estiver, com conteúdos práticos e
aplicáveis.

**Mentoria de Especialistas:** Tenha acesso a uma comunidade de suporte e a dicas exclusivas de
quem entende suas dificuldades.

**Empoderamento Real:** Mais do que cursos, nós oferecemos ferramentas para transformar a
sua vida e o seu negócio.

<div class="horizontal--desktop center bg-black p-6 my-6 text-balance home-hero">
  <div class="phone-frame-container--span">
    <div class="phone-frame">
      <video src="/assets/video/empreendapretas-academy-demo.mp4" muted loop autoplay preload="auto"></video>
    </div>
  </div>

  <div class="wrapper">
    <p class="font--6">
      Se você está pronta para levar seu empreendimento ao próximo nível, não perca essa
      oportunidade de aprender com as melhores!
    </p>

    <p>Assine agora e comece a construir a sua liberdade financeira e autonomia!</p>
  
    <p>
      <a href="https://pay.kiwify.com.br/JLy8qir" target="_blank" class="button">
        Quero assinar
      </a>
    </p>
  </div>
</div>

## Para Quem é o EmpreendaPretas Academy?

O EmpreendaPretas Academy foi criado especialmente para mulheres negras que desejam
crescer e prosperar em suas áreas de atuação, sejam elas mentoras, empresárias ou
empreendedoras de diversos segmentos. É para você que:

- É mentora ou deseja ser mentora e busca profissionalizar sua entrega, garantindo resultados
transformadores para suas alunas através de um acompanhamento personalizado.

- Quer otimizar seu tempo, focando no que realmente importa e criando um impacto duradouro
em sua comunidade.

- Deseja oferecer uma experiência de excelência para suas mentoradas, elevando o padrão da
sua entrega.

- É uma empresária, infoprodutora ou especialista que deseja criar e vender mentorias de forma
profissional, maximizando o seu potencial de faturamento.

- Está pronta para faturar R$10mil ou mais por mês com mentorias bem estruturadas e
direcionadas.

- Busca crescer junto com outras empreendedoras negras, valorizando sua identidade racial e
construindo uma rede de apoio e oportunidades.

Além disso, no EmpreendaPretas Academy, você terá a oportunidade de promover e vender
seus próprios produtos e serviços, expandindo ainda mais seu alcance e impacto no mercado.

## Checklist EmpreendaPretas Academy

### Tudo o que Você Precisa para Aumentar Suas Vendas Diárias e Empoderar Seu Negócio!

Você está pronta para elevar suas vendas, otimizar seu tempo e aplicar estratégias que
realmente funcionam no seu dia a dia? Com este checklist exclusivo, você terá em mãos:

<div class="page-content bg-grey-100">
  <div class="wrapper">
    <ul class="seamless horizontal--laptop gap-4 text-balance">
      <li>
        <strong class="font--3">As Melhores Estratégias Diárias:</strong>
        <br />
        Saiba exatamente o que fazer todos os dias para garantir que suas vendas aumentem e seu negócio se mantenha em
        crescimento constante.
      </li>
      <li>
        <strong class="font--3">Dicas de Empoderamento:</strong>
        <br />
        Descubra como incorporar o empoderamento em cada etapa da sua jornada empreendedora, fortalecendo sua confiança
        e ampliando seu impacto.
      </li>
      <li>
        <strong class="font--3">Otimização de Tempo:</strong>
        <br />
        Aprenda como focar no que realmente importa e deixar de perder tempo com atividades que não trazem resultados.
      </li>
    </ul>
  </div>
</div>

<div class="wrapper horizontal--desktop p-3">
  <div class="phone-frame-container--span pull-right">
    <div class="phone-frame">
      <video src="/assets/video/empreendapretas-academy-demo.mp4" muted loop autoplay preload="auto"></video>
    </div>
  </div>

  <div class="flex">
    <p>
      Este checklist é a ferramenta perfeita para mulheres negras empreendedoras que querem ver
      resultados reais e imediatos, aplicando métodos práticos e eficientes. Não deixe suas vendas
      nas mãos do acaso – esteja sempre um passo à frente!
    </p>
  
    <p>
      <strong>Empreendapretas Academy:</strong>
      Transforme desafios em conquistas.
    </p>
    <p>
      <a href="https://pay.kiwify.com.br/JLy8qir" target="_blank" class="button">
        Acesse o EmpreendaPretas Academy
      </a>
    </p>
  </div>
</div>