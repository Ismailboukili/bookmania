---
layout: default
title: Recrutement Bookmania
---

<main id="qui-sommes-nous">
  <section class="container mt-4 mt-sm-5 pt-5 pb-4 pb-sm-5">
    <div class="row mt-5">
      <div class="col-12 col-lg-7 col-xl-8">
        <h4 class="pb-3 pb-sm-4">
          <strong>Rejoignez notre équipe pédagogique</strong>
        </h4>
        <p class="pr-xl-5 pr-lg-2">
          Grâce à la confiance des élèves et de leurs parents, Bookmania ne cesse de lancer de <strong>nouveaux projets</strong> et de <strong>grandir</strong> pour répondre à une demande croissante. Nous recherchons continuellement <strong>des talents</strong> pour venir participer avec nous à l’aventure Bookmania et partager nos valeurs avec nos élèves.
        </p>
        <ul class="list-unstyled">
          <li class="mb-2">
            <i class="fas fa-check mr-2"></i>
            Vous avez de l’expérience dans l’éducation ?
          </li>
          <li class="mb-2">
            <i class="fas fa-check mr-2"></i>
            Vous voulez intégrer une équipe talentueuse, passionnée et totalement dédiée à l’éducation ?
          </li>
          <li class="mb-2">
            <i class="fas fa-check mr-2"></i>
            Vous avez envie de participer à une aventure humaine et <em>challengeante</em> ?
          </li>
        </ul>
        <p>
          Si vous avez répondu<strong> OUI</strong> à toutes ces questions, et que vous avez en plus un peu d’humour, vous faites sans doute partie des talents que nous recherchons!
        </p>
      </div>
      <div class="d-none d-lg-block d-xl-block col-12 col-lg-5 col-xl-4" data-aos="fade-left" data-aos-duration="1000">
        <div class="description-image" style="background-image: url('assets/images/photo-1518600506278-4e8ef466b810.jpg');">
        </div>
      </div>
    </div>
  </section>

  <section class="pt-5 pb-5 blue-grey lighten-5">
    <div class="container" data-aos="fade-up">
      <div class="row justify-content-center">
        <div class="col-11 col-sm-12 col-md-11 col-lg-10 col-xl-9">
          <div class="card mw-100">
            <div class="card-body">
              <!-- <form action="#" class="ajax-form">
                <div class="md-form">
                  <i class="fas fa-user prefix grey-text"></i>
                  <input type="text" id="form-name" name="name" class="form-control">
                  <label for="form-name">Nom & Prénom</label>
                </div>
                <div class="md-form">
                  <i class="fas fa-envelope prefix grey-text"></i>
                  <input type="email" id="form-email" name="email" class="form-control">
                  <label for="form-email">Email</label>
                </div>
                <div class="md-form">
                  <i class="fas fa-phone prefix grey-text"></i>
                  <input type="tel" id="form-Subject" name="phone" class="form-control">
                  <label for="form-Subject">N° de téléphone</label>
                </div>
                <div class="md-form">
                  <i class="fas fa-pencil-alt prefix grey-text"></i>
                  <textarea type="text" id="form-text" name="message" class="form-control md-textarea"></textarea>
                  <label for="form-text">Présentez-vous</label>
                </div>
                <div class="md-form pb-5">
                  <i class="fas fa-file prefix grey-text"></i>
                  <input type="file" id="file" name="file" style="display:none">
                  <label for="file" id="upload" style="cursor: pointer;">Ajoutez votre CV</label>
                </div>
                <div class="text-center">
                  <button type="submit" class="btn btn-light-blue submit">
                    Envoyer votre candidature
                  </button>
                </div>
              </form> -->
              <form action="https://formspree.io/f/xvodldyq" method="POST" class="validation" enctype="multipart/form-data">
                <input type="hidden" name="_language" value="fr" />
                <input type="hidden" name="_next" value="{{site.baseurl}}/merci.php"/>
                <div class="md-form">
                  <i class="fas fa-user prefix grey-text"></i>
                  <input type="text" id="form-name" name="Nom" class="form-control" required>
                  <label for="form-name">Nom & Prénom</label>
                </div>
                <div class="md-form">
                  <i class="fas fa-envelope prefix grey-text"></i>
                  <input type="email" id="form-email" name="Email" class="form-control" required pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$">
                  <label for="form-email">Email</label>
                </div>
                <div class="md-form">
                  <i class="fas fa-phone prefix grey-text"></i>
                  <input type="tel" id="form-phone" name="Téléphone" class="form-control" required>
                  <label for="form-phone">N° de téléphone</label>
                </div>
                <div class="md-form">
                  <i class="fas fa-pencil-alt prefix grey-text"></i>
                  <textarea type="text" id="form-text" name="Message" class="form-control md-textarea" required></textarea>
                  <label for="form-text">Présentez-vous</label>
                </div>
                <div class="md-form pb-5">
                  <i class="fas fa-file prefix grey-text"></i>
                  <input type="file" id="file" name="upload" class="d-none" multiple>
                  <label for="file" id="upload" style="cursor: pointer;">Ajoutez votre CV</label>
                </div>
                <div class="text-center">
                  <button type="submit" class="btn btn-light-blue">
                    Envoyer votre candidature
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="cta d-lg-none d-flex justify-content-center col-12 mt-4">
      <div class="wrapper">
        <button>
          <a target="_blank" href="https://wa.me/message/OBA4IEB2NYR4E1" class="text-white">
            <i class="fab fa-whatsapp"></i>
            WHATSAPP
          </a>
        </button>
      </div>
    </div>
  </section>
</main>
