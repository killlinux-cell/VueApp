<template>
    <!-- barre de navigation -->
    <nav class="navbar nav navbar-expand-lg bg-black d-none d-sm-block">
        <div class="container">
            <img src="@/assets/logo.png" width="32" height="32" alt="logo" srcset="">
            <a class="navbar-brand text-white ps-2" href="#">F.I.F</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fa-solid fa-user text-white"></i>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link text-white active" aria-current="page" href="#">Actualités</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link text-white dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Les éléphants
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Eléphants</a></li>
                            <li><a class="dropdown-item" href="#">Eléphants</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Eléphants</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link text-white dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Compétitions
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Eléphants</a></li>
                            <li><a class="dropdown-item" href="#">Eléphants</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Eléphants</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white">La F.I.F</a>
                    </li>
                </ul>
                <div class="d-flex" role="search">
                    <a href="" class="text-white fs-5">
                        <i class="fa-brands fa-facebook"></i>
                    </a>
                    <a href="" class="text-white fs-5 mx-4">
                        <i class="fa-brands fa-youtube"></i>
                    </a>
                    <a href="" class="text-white fs-5">
                        <i class="fa-brands fa-tiktok"></i>
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- barre de navigation -->
    <!-- barre chargement page -->
    <div class="progress-bar"></div>
    <!-- barre chargement page -->
    <!-- content -->
    <div class="bg-black">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="row">
                        <div class="col-md-12 py-5">
                            <button type="button"
                                class="btn btn-sm btn-outline-light rounded-5 d-flex align-items-center justify-content-between"><i
                                    class="fas fa-arrow-left me-4"></i>Retour</button>
                        </div>
                        <div class="col-md-12">
                            <div class="row">
                                <div class="col-md-7">
                                    <div class="text-success fs-4 d-sm-none">
                                        THE DIV
                                    </div>
                                    <div class="conteneur-img">
                                        <img class="w-100 img-responsive" src="@/assets/img-art.png"
                                            style="max-height: 300px;" alt="logo">
                                    </div>
                                    <div>
                                        <div class="text-success fs-4 d-none d-sm-block">
                                            THE DIV
                                        </div>
                                        <p class="mb-0 text-white" style="text-align: justify;">
                                            40 ans après l'édition de 1984, la première économie de l'espace UEMOA se
                                            prépare à faire de ce rendez-vous sportif, un coup d'éclat dans l'histoire de la
                                            CAN. Car, faut-t-il le souligner, c'est un budget de près de 174 milliards de
                                            FCFA qui a été affecté à l'organisation de cette compétition par l'état de Côte
                                            d'Ivoire.
                                            Un an avant le démarrage effectif des hostilités, les travaux de finition des stades et autres infrastructures entrant en ligne de compte dans l'accueil des différentes délégations et de leurs supporters s'accélèrent. Selon Mariam Yoda, Directrice Générale de l'Office National des Stades (ONS) dans le bilan qu'elle dressait des activités de son institution le 1er Janvier 2023, les six stades retenus pour abriter les matches de poules, les 24 centres d'entraînement des équipes et les 3 cités CAN sont en phase d'achèvement. Des nouvelles qui devraient logiquement rassurer un peu plus les populations Ivoiriennes désireuses de voir cette compétition réussir dans leur pays. L'engouement est perceptible à travers les réactions observées sur les réseaux sociaux.

                                                    Au contact des chantiers également, on ne se lasse pas de commenter l'évolution des travaux. Faire mieux que les éditions précédentes organisées dans d'autres pays, ce rêve, beaucoup le caressent en Côte d'Ivoire. Non seulement dans les villes d'Abidjan, de Bouaké, de Korhogo, de San-Pedro et de Yamoussoukro où se joueront les phases de poules. Mais également ailleurs dans le pays où chaque détail sera certainement suivi et commenté avec tranchant.

                                                    La pression monte et nul doute que la fête sera belle ! L’Afrique et le monde découvriront ce que la Côte d’Ivoire a de meilleur : son hospitalité légendaire.
                                        </p>
                                    </div>
                                    <p class="mt-4 text-success">Les équipes: </p>
                                    <div class="row gy-2">
                                        <div class="col-md-4 text-center">
                                            <div class="bg-dark p-2 rounded-3 border border-2 border-secondary">
                                                <img src="@/assets/img-art.png" class="rounded-circle"
                                                    style="height: 40px; width: 40px;" alt="">
                                                <p class="text-white mb-0">Racing Abidjan</p>
                                                <p class="text-secondary mb-0">Racing Abidjan</p>
                                            </div>
                                        </div>
                                        <div class="col-md-4 text-center">
                                            <div class="bg-dark p-2 rounded-3 border border-2 border-secondary">
                                                <img src="@/assets/img-art.png" class="rounded-circle"
                                                    style="height: 40px; width: 40px;" alt="">
                                                <p class="text-white mb-0">Racing Abidjan</p>
                                                <p class="text-secondary mb-0">Racing Abidjan</p>
                                            </div>
                                        </div>
                                        <div class="col-md-4 text-center">
                                            <div class="bg-dark p-2 rounded-3 border border-2 border-secondary">
                                                <img src="@/assets/img-art.png" class="rounded-circle"
                                                    style="height: 40px; width: 40px;" alt="">
                                                <p class="text-white mb-0">Racing Abidjan</p>
                                                <p class="text-secondary mb-0">Racing Abidjan</p>
                                            </div>
                                        </div>
                                        <div class="col-md-4 text-center">
                                            <div class="bg-dark p-2 rounded-3 border border-2 border-secondary">
                                                <img src="@/assets/img-art.png" class="rounded-circle"
                                                    style="height: 40px; width: 40px;" alt="">
                                                <p class="text-white mb-0">Racing Abidjan</p>
                                                <p class="text-secondary mb-0">Racing Abidjan</p>
                                            </div>
                                        </div>
                                        <div class="col-md-4 text-center">
                                                <div class="bg-dark p-2 rounded-3 border border-2 border-secondary">
                                                    <img src="@/assets/img-art.png" class="rounded-circle"
                                                        style="height: 40px; width: 40px;" alt="">
                                                    <p class="text-white mb-0">Racing Abidjan</p>
                                                    <p class="text-secondary mb-0">Racing Abidjan</p>
                                                </div>
                                            </div>
                                            <div class="col-md-4 text-center">
                                                <div class="bg-dark p-2 rounded-3 border border-2 border-secondary">
                                                    <img src="@/assets/img-art.png" class="rounded-circle"
                                                        style="height: 40px; width: 40px;" alt="">
                                                    <p class="text-white mb-0">Racing Abidjan</p>
                                                    <p class="text-secondary mb-0">Racing Abidjan</p>
                                                </div>
                                            </div>
                                    </div>
                                </div>
                                <div class="col-md-5 d-flex justify-content-center">
                                    <div class="bg-dark rounded-2 p-3 sticky-top"
                                        style="top: 5%; width: fit-content; height: fit-content;">
                                        <p class="text-secondary mb-3">Le 12 Decembre 2012</p>
                                        <p class="text-white text-capitalize mb-3">écrit par Isra</p>
                                        <button
                                            class="btn btn-sm btn-success rounded-5 d-flex align-items-center justify-content-between">
                                            Partager
                                            <i class="ms-3 fa-solid fa-arrow-right"></i>
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- fin content -->
    <!-- Autres -->

    <!-- Autres -->

    <!-- PUB -->
    <PubView />
  <!-- PUB -->
  
  <!-- Footer -->
  <FooterView />
  <!-- Footer -->
</template>

<script>
/* import GridView from './GridView.vue'; */
import PubView from './PubView.vue';
import FooterView from './FooterView.vue';

export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: "ArticleView",
    components: {
        PubView,
        FooterView,
    },
    mounted() {
        window.addEventListener('scroll', this.updateProgressBar);
    },
    methods: {
        updateProgressBar() {
            const scrollTop = document.documentElement.scrollTop;
            const scrollHeight = document.documentElement.scrollHeight;
            const clientHeight = document.documentElement.clientHeight;
            const progress = (scrollTop / (scrollHeight - clientHeight)) * 100;
            document.querySelector('.progress-bar').style.width = progress + '%';
        }
    },
    beforeUnmount() {
        window.removeEventListener('scroll', this.updateProgressBar);
    }
};

</script>

<style scoped>
body{
    overflow-x: hidden;
}
.progress-bar {
    position: sticky;
    z-index: 2;
    top: 0;
    background-color: #76f4b0;
    height: 5px;
    width: 0%;
    transition: width 0.5s ease-out;
}

.conteneur-img {
    width: 100%;
    max-height: 20rem;
    object-fit: cover;
    border-radius: 16px;
    margin-bottom: 2.5rem;
    display: block;
}

.nav{
    position: sticky;
    top: 0;
    z-index: 5;
}

img {
    max-width: 100%;
}</style>
