<template>
  <Page>
    <GridLayout>
      <ListView for="item in items" separatorColor="transparent">
        <v-template>
          <ListItemComponent :item="item"/>
        </v-template>
      </ListView>
    </GridLayout>
  </Page>
</template>

<style src="nativescript-tailwind/dist/tailwind.css"></style>

<script>
  import ListItemComponent from "./ListItemComponent";

  export default {
    components: {ListItemComponent},
    data() {
      return {
        items: [
          {
            "text": "Magna anim nostrud est tempor ipsum quis amet duis exercitation exercitation. Incididunt irure et laborum occaecat. Aute veniam est qui enim. Laborum sit ad aliqua est ipsum eiusmod labore aliqua magna. Aliqua consequat enim ad reprehenderit exercitation cillum esse nulla commodo qui consectetur anim incididunt deserunt."
          },
          {
            "text": "In eu sit officia deserunt fugiat ad ex nostrud cillum proident irure nostrud. Cillum officia occaecat ex id eu tempor."
          },
          {
            "text": "Ipsum est cillum qui exercitation est adipisicing incididunt cupidatat in. Anim sint do in elit consequat sint id culpa. Cillum id dolor excepteur dolore nostrud officia nostrud amet officia cillum."
          },
          {
            "text": "Culpa ullamco culpa eu quis ut sunt mollit. Nostrud aliqua fugiat duis velit anim sint adipisicing labore aute sunt aliquip. Duis mollit officia culpa ipsum dolore non officia consectetur et velit eu. Laboris laboris enim tempor esse duis esse reprehenderit. Officia voluptate duis aliquip Lorem amet laborum adipisicing nisi officia enim. Sint magna excepteur labore non irure proident quis ea velit elit non. Commodo anim non occaecat eu pariatur velit aute in aute aliquip."
          },
          {
            "text": "Duis aute ullamco magna quis irure laboris. Laborum do excepteur veniam minim amet. Magna esse proident est ullamco aute qui deserunt ex laboris et elit nulla. Irure labore qui cillum ipsum consequat ea mollit veniam excepteur ad elit et. Exercitation quis ea et est. Commodo elit ex aliqua non est cupidatat id amet ea est ipsum dolor. Nisi ea adipisicing dolor laborum laborum id labore dolore quis amet pariatur in incididunt. Tempor magna tempor non id duis."
          },
          {
            "text": "Mollit eiusmod irure in labore esse velit duis id reprehenderit ipsum eiusmod. Eu qui sit irure non elit. Excepteur proident esse ad dolor officia nisi tempor tempor laboris."
          },
          {
            "text": "Nostrud ex in id esse ea. Aliqua proident eiusmod sit nostrud aute esse proident dolor esse in irure et ut officia. Fugiat anim aliquip nisi adipisicing anim consectetur veniam adipisicing fugiat minim irure velit eu irure. Laboris reprehenderit occaecat aliqua cupidatat velit. Ex incididunt officia sint adipisicing dolor excepteur irure. Occaecat non do eiusmod cillum fugiat aliqua aliqua ullamco ex cupidatat nisi mollit id ex. Eu nostrud in magna occaecat et exercitation consectetur cillum aliquip sit veniam."
          },
          {
            "text": "Officia labore sunt eu nostrud ut id eu nisi adipisicing mollit occaecat ea. Sit dolor tempor et anim elit nisi ex occaecat. Et irure pariatur laboris Lorem. Occaecat eu ut tempor qui minim dolor nostrud id dolor incididunt deserunt consequat eu non. Ad officia anim Lorem qui aliquip veniam Lorem ex dolor veniam laboris culpa. Eu quis voluptate quis sunt adipisicing tempor."
          },
          {
            "text": "Laboris ea cupidatat veniam proident ex qui amet tempor commodo et ad fugiat qui. Fugiat esse velit mollit non aute enim non adipisicing qui. Ea cillum minim nostrud velit consequat ad cupidatat cillum ex deserunt elit deserunt. Dolore sit tempor dolore non ad eiusmod enim sit ut ea dolore incididunt aliquip. Duis voluptate et minim culpa aliqua ipsum dolor incididunt officia nisi."
          },
          {
            "text": "Mollit nisi reprehenderit excepteur nisi tempor fugiat magna amet ipsum quis dolor veniam incididunt. Amet ex esse id exercitation ea. Magna aute adipisicing voluptate mollit occaecat est elit anim esse deserunt voluptate sit anim dolor. Irure in amet culpa ea laborum nisi dolore incididunt aliquip pariatur magna anim."
          },
          {
            "text": "In ea commodo enim ad laboris incididunt Lorem occaecat nisi officia id minim incididunt. Aute labore proident sunt do est cupidatat exercitation."
          },
          {
            "text": "Sunt occaecat cillum sit Lorem aliquip consequat velit sunt ad ullamco sit labore sint. Minim elit laborum pariatur ea cillum aute. Qui magna in culpa exercitation tempor veniam nostrud excepteur nisi. Anim laborum nulla voluptate qui occaecat laborum do eiusmod culpa sit reprehenderit sit aute. Pariatur amet officia nisi aliquip sunt tempor esse dolore. Minim adipisicing dolore nostrud non velit."
          },
          {
            "text": "Occaecat cillum officia veniam aliqua esse cillum occaecat consequat officia eiusmod dolore mollit dolor. Incididunt ad aliquip aute non sint cillum nisi non excepteur incididunt et."
          },
          {
            "text": "Laborum officia labore sint ex sunt cillum ex. Proident et voluptate et ipsum do ullamco ut ex qui et eu commodo. Dolore dolore anim reprehenderit ullamco amet eu."
          },
          {
            "text": "Esse voluptate irure non sunt laboris nisi sit irure minim ea adipisicing. Ut voluptate et laboris Lorem minim. Commodo ex ipsum aute id do aliquip reprehenderit anim quis proident consequat. Non esse sint commodo reprehenderit deserunt id commodo irure ullamco mollit aute pariatur. Aute enim ea ut officia. Sint excepteur in laboris incididunt est."
          },
          {
            "text": "Esse consectetur sit proident in consequat aliquip duis ipsum laboris officia dolore cillum enim. Labore aliquip ex ut irure consectetur ullamco aute minim laboris ullamco excepteur reprehenderit dolore. Velit occaecat occaecat id excepteur proident adipisicing in non. Qui proident cupidatat esse et ea dolore dolore voluptate quis esse. Irure sunt magna commodo minim. Dolore nisi officia laboris cillum mollit. Ex nisi do veniam irure sit tempor velit nostrud velit culpa excepteur in ipsum. Adipisicing deserunt esse cillum mollit Lorem ipsum Lorem occaecat Lorem in minim qui et laboris."
          },
          {
            "text": "Consequat enim exercitation et ipsum laboris deserunt proident et commodo. Sit magna dolor excepteur nostrud enim veniam labore dolor aliqua exercitation laborum laboris sunt. Nostrud qui esse ea laborum anim deserunt aliqua excepteur occaecat occaecat excepteur. Nulla id aliqua est Lorem ipsum. Ullamco sint ullamco voluptate et adipisicing."
          },
          {
            "text": "Culpa id in anim adipisicing esse et esse in elit fugiat tempor tempor velit aliquip."
          },
          {
            "text": "Et proident cupidatat commodo nostrud occaecat. Occaecat aute dolore ullamco fugiat do sit anim qui exercitation dolor consectetur. Do nisi elit ut et officia quis reprehenderit mollit dolor consequat cupidatat sit incididunt. Dolore fugiat excepteur laborum veniam ut mollit laboris. Dolor officia aliquip et magna enim. Tempor amet amet quis Lorem ullamco magna laboris enim. Proident minim occaecat aliqua sit aliquip velit enim velit aliquip. Esse adipisicing occaecat laboris officia nulla ea laboris sint dolor adipisicing."
          },
          {
            "text": "Aliquip deserunt aliquip aute consectetur et quis quis laborum deserunt anim eiusmod deserunt. Consequat dolor ex magna sint anim. Ea excepteur proident amet non fugiat magna aute incididunt velit. Consectetur magna sunt eiusmod proident in tempor ad proident ut ut eu adipisicing duis. Duis enim nisi ut eiusmod officia occaecat duis et veniam et sint. Occaecat cillum et sit dolore anim ad amet est aute. Cillum tempor in nisi dolore incididunt incididunt consequat aute enim cillum id proident ut. Fugiat excepteur est nostrud do minim et veniam qui ipsum."
          },
          {
            "text": "Adipisicing qui qui ad magna adipisicing. Velit ullamco laboris consequat laborum irure. Anim adipisicing excepteur deserunt dolor amet. Reprehenderit ea do in duis amet anim minim excepteur reprehenderit pariatur. Laboris Lorem pariatur nisi aliquip velit do est sint ut magna. Aliqua reprehenderit nisi excepteur officia sunt in ullamco aliquip. Proident consectetur cillum sint aliquip non dolore duis. Anim consequat proident sint occaecat nisi elit cillum laboris. Non veniam et irure voluptate esse esse aliqua fugiat consectetur nostrud id consectetur veniam. Esse occaecat esse deserunt consectetur esse deserunt amet esse commodo."
          },
          {
            "text": "Mollit magna anim et deserunt exercitation. Sunt exercitation deserunt aute Lorem sit et deserunt non minim occaecat pariatur culpa. Occaecat amet ad qui cupidatat veniam aliquip id tempor deserunt non."
          },
          {
            "text": "Fugiat adipisicing quis pariatur pariatur officia non velit esse eu. Sunt voluptate labore officia proident mollit consequat anim excepteur incididunt aliquip anim veniam tempor. Enim dolor laboris ut laborum nisi non sunt non ut pariatur. Eu duis nisi anim minim mollit eu reprehenderit. Labore duis ipsum aute esse. Nisi ex deserunt proident laboris do Lorem deserunt. Consectetur esse consectetur qui nulla aute tempor aliqua ullamco sunt incididunt est ea."
          },
          {
            "text": "Sint exercitation Lorem nisi officia proident sunt do commodo id. Cillum aliquip eu occaecat dolor cupidatat magna do veniam commodo sint. Voluptate esse proident consequat nulla laborum incididunt officia quis in laborum nostrud deserunt ea."
          },
          {
            "text": "Labore irure nostrud proident exercitation fugiat laboris sunt incididunt minim deserunt. Reprehenderit excepteur laboris aliquip nulla quis quis. Eu aute adipisicing in aute."
          },
          {
            "text": "Ea laborum voluptate consequat pariatur esse esse non officia ipsum. Exercitation amet dolore eiusmod ullamco laboris duis dolor anim cupidatat. Ipsum labore proident ut culpa enim eu ex culpa laboris quis quis. Lorem dolor dolor sit aute eiusmod. Anim et Lorem eiusmod velit eiusmod irure."
          },
          {
            "text": "Lorem reprehenderit mollit ea id deserunt id proident esse amet occaecat dolore commodo. Nulla id dolor nisi cillum amet excepteur anim veniam consequat duis anim reprehenderit. Adipisicing sint irure magna sint consequat deserunt reprehenderit id. Officia est esse nisi labore deserunt aliqua qui cupidatat reprehenderit reprehenderit duis ea ad. Voluptate labore sint sint minim voluptate eu tempor irure aliquip voluptate incididunt id excepteur non. Amet dolore incididunt irure laborum ipsum et dolor ullamco. Aliquip magna cillum irure sint laborum laboris. Consequat adipisicing culpa ea deserunt officia cupidatat ullamco. Nulla fugiat fugiat eiusmod incididunt sit labore pariatur in. Id consectetur velit ex id laborum aute adipisicing do."
          },
          {
            "text": "Fugiat nisi sit sint reprehenderit tempor proident Lorem aute. Ad incididunt esse magna laborum Lorem incididunt reprehenderit irure irure."
          },
          {
            "text": "Aliquip proident aliqua qui cillum consectetur aliquip minim laboris duis amet qui sint voluptate. Commodo officia esse nisi tempor aute ullamco commodo adipisicing. Nulla sint anim duis eu ipsum nisi consequat incididunt ullamco exercitation duis sunt. Id culpa excepteur eiusmod eiusmod ipsum officia sit fugiat dolor velit pariatur. Reprehenderit nulla sit cillum sint sit culpa eiusmod labore culpa adipisicing exercitation pariatur ut. Ex aute do culpa minim proident officia culpa sint veniam est veniam anim elit. Do fugiat nostrud fugiat non. Commodo velit enim irure officia quis. Laborum non aliqua qui non officia quis."
          },
          {
            "text": "Anim officia excepteur incididunt eu culpa mollit deserunt sint aliqua. Ipsum nulla fugiat eu id in ea consequat. Non sint nulla esse do ea et ex. Fugiat nisi enim commodo occaecat excepteur velit minim Lorem. Est laborum voluptate sint officia eu nulla ea. Elit labore velit tempor Lorem. Ad exercitation do veniam commodo cupidatat commodo nulla. Voluptate velit non ex dolor ullamco minim laboris laborum nostrud adipisicing duis elit. Duis adipisicing laborum qui sit."
          }
        ]
      };
    }
  }
</script>

