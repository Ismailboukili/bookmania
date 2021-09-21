---
layout: default
title: Contact
---
<main id="contact">
  <section class="container mt-4 mt-sm-5 pt-5 pb-4 pb-sm-5">
    <div class="row mt-5">
      <div class="col-lg-5 mb-lg-0 mb-4 d-flex justify-content-center" data-aos="fade-up">
        <div class="card">
          <div class="card-body">
            <p class="dark-grey-text">
              Laissez votre numéro, nous vous rappelons dans les plus brefs délais.
            </p>
            <form action="https://formspree.io/ismail.boukili@gmail.com" method="POST" class="validation">
              <input type="hidden" name="_cc" value="Fatimazahra.birzyne@bookmania.ma">
              <input type="hidden" name="_language" value="fr" />
              <input type="hidden" name="_next" value="{{site.baseurl}}/merci.php"/>
              <div class="md-form">
                <i class="fas fa-user prefix grey-text"></i>
                <input type="text" id="form-name" name="Nom" class="form-control" required>
                <label for="form-name">Nom complet</label>
              </div>
              <div class="md-form">
                <i class="fas fa-envelope prefix grey-text"></i>
                <input type="email" id="form-email" name="Email" class="form-control" required pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$">
                <label for="form-email">Email</label>
              </div>
              <div class="md-form">
                <i class="fas fa-phone prefix grey-text"></i>
                <input type="tel" id="form-Subject" name="Téléphone" class="form-control">
                <label for="form-Subject">N° de téléphone</label>
              </div>
              <div class="md-form">
                <i class="fas fa-pencil-alt prefix grey-text"></i>
                <textarea type="text" id="form-text" name="Message" class="form-control md-textarea"></textarea>
                <label for="form-text">Message (facultatif)</label>
              </div>
              <div class="text-center">
                <button type="submit" class="btn btn-light-blue">
                  ENVOYER
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
      <div class="cta d-lg-none d-flex justify-content-center col-12 mb-5">
        <div class="wrapper">
          <button>
            <a target="_blank" href="https://wa.me/212606060101" class="text-white">
              <i class="fab fa-whatsapp"></i>
              WHATSAPP
            </a>
          </button>
        </div>
      </div>
      <div class="col-lg-7" data-aos="fade-up">
        <div id="map-container-section" class="z-depth-1-half map-container-section mb-4" style="height: 400px">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3323.624520661829!2d-7.635239684719824!3d33.58909698073458!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xda7d2935589d485%3A0x93425f8fafdf71a4!2sBookmania+-+Tutoring+Language+Center+%C3%80+Casablanca!5e0!3m2!1sen!2sth!4v1558617630216!5m2!1sen!2sth" frameborder="0"
            style="border:0" allowfullscreen></iframe>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <i class="fas fa-map-marker-alt text-muted"></i>
            <p>
              <a target="_blank" href="https://goo.gl/maps/qExbRXBoUtz">
                64, avenue Hassan Souktani, Quartier Gautier, 20060, Casablanca Maroc
              </a>
            </p>
          </div>
          <div class="col-md-4">
            <i class="fas fa-envelope text-muted"></i>
            <p>
              <a href="mailto:{{site.email}}">
                {{site.email}}
              </a>
            </p>
          </div>
          <div class="col-md-4">
            <i class="fas fa-phone text-muted"></i>
            <p>
              <a href="tel:+212522225062">
                (+212) 5 22 22 50 62
              </a>
            </p>
            <p>
              WhatsApp:<br>
              <a target="_blank" href="https://wa.me/212606060101">
                (+212) 6 06 06 01 01
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>
