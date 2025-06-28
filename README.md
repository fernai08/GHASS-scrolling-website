<section
          id="grid-container"
          class="transitions-enabled fluid masonry js-masonry grid"
        >
          <article class="beach people sea">
            <a
              href="https://www.imdb.com/title/tt15680618/?ref_=tt_rvi_tt_i_1"
              target="_blank"
            >
              <img
                src="./MEDIA/portfolio/bride-token-poster.png"
                class="img-responsive"
              />
            </a>
          </article>

          <article class="beach bird">
            <a href="" target="_blank">
              <img
                src="./MEDIA/portfolio/adm-poster.png"
                class="img-responsive"
            /></a>
          </article>

          <article class="sea">
            <a
              href="https://open.spotify.com/artist/04uUTwnXnmClA1mZnFAsOZ?si=uaU9e9Z8R4um8xpCe59HOg"
              target="_blank"
            >
              <img
                src="./MEDIA/portfolio/mamih-vinyl-cover.png"
                class="img-responsive"
            /></a>
          </article>

          <article class="beach people rock sea">
            <img
              src="https://cdn2.hubspot.net/hub/322787/hubfs/MYCHEFCOM/hackathon/photos-gallery/beach2.jpg"
              class="img-responsive"
            />
          </article>
        </section>





        .img-responsive {

display: block;
max-width: 100%;
height: auto;
}

.grid article {
background-color: #FFFFFF;
display: block;
float: left;
margin: 1%;
width: 23%;
}

@media (max-width: 1024px) {
.grid article {
width: 31.3%;
}
}

@media (max-width: 767px) {
.grid article {
width: 48%;
}
}

@media (max-width: 479px) {
.grid article {
margin: 2% 0;
width: 100%;
}
}
