<main>
    <h1>coffee</h1>
   <section class="gallery">
    <article>
        <img src="/images/coffee/Matcha-Latte-001s.webp" alt="Matcha">
    <p>Match is about green tea powder</p>
    </article>
   </section>
</main>
     <style>
        .gallery{
    margin: auto;
}
.gallery article {
    width: 100%;
    margin: 1rem;
    background-color: gray;
    border-radius: 1rem;
    border: 1px soild black;
    box-shadow: 0 1px 1px #eee;
}
gallery article h3 {
    margin: 0.5rem;
    text-align: center;
  }
  .gallery article img {
    display: block;
    width: 100%;
    aspect-ratio: 1/1;
    object-fit: cover;
    border-top-left-radius: 1rem;
    border-top-right-radius: 1rem;
  }
  @media screen and (min-width: 800px) {
    .gallery {
      display: grid;
      grid-template-columns: 250px 250px 250px;
      justify-content: center;
      gap: 1rem;
    }
    .gallery article {
      margin: 0;
    }
  }
     </style>