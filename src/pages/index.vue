<template>
  <div class="mx-80 my-14">
    <div class="bg-white flex w-full p-10 rounded-md drop-shadow-2xl">

      <div>
        <img class="w-auto h-auto " src="@/assets/img/Moi.jpg" alt="photo de asma ">




        <div class="bg-neutral-900 text-white w-full h-[100rem] p-5 ">
          <div class="m-2">
            <h2 class="my-2 mb-3 uppercase font-bold text-lg"> Asma Es-sabbar </h2>
            <p class="font-semibold text-sm mb-6"> Étudiante <br /> 19 ans <br /> Permis B</p>
            <p class="text-sm font-light"> Étudiante de deuxième année au B.U.T Métier du multimédia et de
              l’internet à Montbéliard, je suis actuellement à la recherche d'un <span class="font-bold">
                stage dans la période du 27 mars au 7 juin 2023. </span></p>
          </div>

          <div class="m-2 mt-6">
            <p class="text-sm font-light"> <span class="font-semibold"> Dynamique, sérieuse créative</span>
              et
              <span class="font-semibold"> passionné </span> par le monde de l'informatique je serais
              honoré d'intégrer votre entreprise et de vous montrer de quoi je suis capable.
            </p>
          </div>

          <div class="m-2">
            <h2 class="my-2 mt-14 text-lg uppercase font-bold "> Contact</h2>
            <p class="text-sm"> + 33 7 62 72 42 52 <br /> esssabbarasma17@gmail.com <br /> Avenu du 8 mai,
              25400 Audincourt </p>
          </div>
        </div>
      </div>


      <div class="m-7 ">
        <div class=" mb-10 -mt-7">
          <ligne />
        </div>


        <h1 class="uppercase font-bold my-5 mb-8 text-lg "> Étude </h1>
        <div class="flex">
          <div class="">
            <h2 class="font-bold text-base mb-28"> 2023 </h2>
            <h2 class="font-bold text-base "> 2021 </h2>
          </div>
          <div class="ml-12 ">
            <etudebar />
          </div>
          <div>
            <h2 class=" font-bold text-base ml-5 mb-1 "> BUT Métier du multimédiat et de l'internet - 2e
              année </h2>
            <p class="text-sm ml-5 mr-4 "> <span class="font-bold text-gray-700 italic"> IUT
                Belfort-Montbéliard, <br /> 25230 Montbéliard</span> <br />
              <span class=" font-semibold"> Parcours développement</span>
            </p>

            <h2 class=" font-bold text-base ml-5 mb-1 mt-11 "> Baccalauréat général </h2>
            <p class="text-sm ml-5 mr-4 "> <span class="font-bold text-gray-700 italic"> Lycée Germaine
                Tillon, 25230 Montbéliard</span> </p>

          </div>

        </div>

        <div class="mt-14 mb-10 ">
          <ligne />
        </div>



        <h1 class="uppercase font-bold my-5 mb-8 text-lg "> experience </h1>
        <div class="flex">
          <div class="">
            <h2 class="font-bold text-base mb-36"> 2023 </h2>
            <h2 class="font-bold text-base pt-2"> 2023 </h2>
          </div>
          <div class="ml-12 ">
            <experiencebar />
          </div>
          <div>
            <h2 class=" font-bold text-base ml-5 mb-1 "> Chef de projet web & développeuse </h2>
            <p class="text-sm ml-5 mr-4 "> <span class="font-bold text-gray-700 italic"> E-car Vtc,
                Montbéliard,
                25230</span>
              <br />
              Site internet de reservation et payement en ligne pour un chaffeur
              vtc.
              <br /> <a class="font-bold text-gray-700" href="https://e-car-vtc.fr/">
                https://e-car-vtc.fr/ </a> <br />
              <span class=" font-semibold"> 2 mois </span>
            </p>


            <h2 class=" font-bold text-base ml-5 mb-1 mt-11"> Équipière polivalente & Formatrice</h2>
            <p class="text-sm ml-5 mr-4 "> <span class="font-bold text-gray-700 italic"> Macdonald's,
                Audincourt, 25400</span>
              <br />
              Prise de commande et préparation de commande. Accompagnement et aide des equipier en
              formation. <br />
              <span class=" font-semibold"> Depuis avril 2022. </span>
            </p>
          </div>

        </div>

        <div class="mt-14 mb-10 ">
          <ligne />
        </div>


        <h1 class="text-lg uppercase font-bold mb-8"> skills</h1>


        <h2 class="mb-8 my-10 uppercase font-bold text-base "> Langage
          & Framework </h2>
        <p class="text-sm mb-8 font-semibold italic "> Grâce à mes études et à ma veille personnelle, j’ai pu
          prendre connaissance de nombreux outils et langages qui m'accompagnent dans mon quotidien. Comme
          les langages HTML, CSS, PHP, SQL et javascript. Ainsi que certains framework comme Vue js, Chart js
          et Tailwind CSS.
        </p>
        <div class="grid grid-cols-5 gap-2">
          <logohtml />
          <logocss />
          <logosql />
          <logojava />
          <logowordpress />
          <logochartjs />
          <logovuejs />
        </div>

        <h2 class="mb-8 my-9 uppercase font-bold text-base "> Donnée
        </h2>
        <p class="text-sm mb-8 font-semibold italic "> Aussi, au cours de ma formation j'ai eu l'occasion de
          travailler avec des outils de
          base de donné comme github,
          supabase ou encore firebase.</p>
        <div class="grid grid-cols-4 gap-4">
          <logosupabase />
          <logogit />
          <logofirebase />

        </div>

        <h2 class="mb-5 uppercase font-bold text-base "> Design
        </h2>
        <p class="text-sm mb-8 font-semibold italic "> Concernant la conception graphique, j'ai pu développer
          ma créativité
          en utilisant des
          outils comme
          figma,
          photoshop, Illustrator, Indesing, Blender.</p>
        <div class="grid grid-cols-5 gap-5">
          <logops />
          <logoillustrator />
          <logoid />
          <logofigma />

        </div>
        <div class="my-7 mr-7 ">
          <div class="mt-14 mb-10">
            <ligne />
          </div>
        </div>
        <div>
          <h1 class="text-lg uppercase font-bold mb-8"> Langue </h1>
          <p class=" uppercase font-semibold text-base "> Français : c2</p>
          <p class=" uppercase font-semibold text-base "> Anglais : c1</p>
        </div>

      </div>
    </div>
  </div>

</template>

<script>

import ligne from '../components/icons/ligne.vue'
import barre from '../components/icons/barre.vue'
import rond from '../components/icons/rond.vue'
import logofigma from '../components/icons/logofigma.vue'
import logohtml from '../components/icons/logohtml.vue'
import logocss from '../components/icons/logocss.vue'
import logogit from '../components/icons/logogit.vue'
import logotailwind from '../components/icons/logotailwind.vue'
import logojava from '../components/icons/logojava.vue'
import logosql from '../components/icons/logosql.vue'
import logosupabase from '../components/icons/logosupabase.vue'
import logovuejs from '../components/icons/logovuejs.vue'
import logowordpress from '../components/icons/logowordpress.vue'
import logochartjs from '../components/icons/logochartjs.vue'
import logofirebase from '../components/icons/logofirebase.vue'
import logops from '../components/icons/logops.vue'
import logoillustrator from '../components/icons/logoillustrator.vue'
import logoid from '../components/icons/logoid.vue'
import experiencebar from '../components/icons/experiencebar.vue'
import etudebar from '../components/icons/etudebar.vue'





export default {
  components: {
    logofigma, ligne, barre, rond, logohtml, logocss, logogit, logotailwind, logojava, logosql, logosupabase, logovuejs, logowordpress, logochartjs, logofirebase, logops, logoillustrator, logoid, experiencebar, etudebar

  }
}
</script>