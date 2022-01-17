<template>
    <header>
        <nav :class="{'navcolor' : scrollPosition}">
            <div class="logo">
                <img src="" alt="">
            </div>
            <ul class="navigation" v-show="!mobile">
                <li><a href="" class="link">home</a></li>
                <li><a href="" class="link">new</a></li>
                <li><a href="" class="link">contact</a></li>
                <li><a href="" class="link">about</a></li>
            </ul>
            <div class="icon" v-show="mobile" @click="mobileNav = !mobileNav">
                <i class="fa fa-bars" aria-hidden="true"></i>
            </div>
            <div class="fade">
                <transition name="fade">
                    <ul class="mobile-nav" v-show="mobileNav">
                        <li><a href="" class="link">home</a></li>
                        <li><a href="" class="link">new</a></li>
                        <li><a href="" class="link">contact</a></li>
                        <li><a href="" class="link">about</a></li>
                    </ul>
                </transition>
            </div>

        </nav>
    </header>
    <body>
        <h4>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Consectetur molestias odio expedita rerum? At quo, nobis deserunt numquam accusamus veniam necessitatibus iure non nisi quasi, harum rerum culpa officia incidunt!
        Ad voluptate velit dicta eligendi obcaecati praesentium. Blanditiis, omnis quas deleniti tempore neque, error natus ab nisi, dicta delectus facilis corporis iste odio corrupti mollitia. Deleniti eveniet perferendis maiores officia!
        Atque vitae, saepe deserunt laboriosam quasi nisi commodi quas eum, aspernatur molestias reiciendis? Id tempora quo ea deleniti, voluptatibus iusto amet, rem, veniam laborum fugit inventore. Nesciunt amet possimus nam.
        Ex in consectetur iusto corporis maxime, similique totam voluptatem, voluptates qui ducimus veritatis quaerat voluptatum odio veniam est repellendus omnis aliquid sapiente minus aut dignissimos vitae sint. Voluptas, assumenda impedit.
        Eveniet asperiores fugit repellendus vitae veniam quas magnam eaque! Facere quidem alias maiores recusandae ipsam, harum dignissimos ex exercitationem ab totam voluptatibus consequuntur hic suscipit. Odit perferendis enim explicabo itaque?
        Error at dicta rerum labore numquam, minus temporibus itaque doloribus accusamus omnis repudiandae assumenda, tempore totam voluptatem delectus alias, quidem obcaecati sequi quos quod? Illum dolore consequuntur illo impedit laboriosam!
        Debitis et, dignissimos deserunt qui doloribus sit sapiente maxime eum ipsum officia delectus odit harum fuga veniam ullam placeat fugit nesciunt pariatur magni libero, mollitia, commodi atque incidunt iste. Architecto!
        Veniam non cumque reiciendis amet error corrupti quam laboriosam culpa dignissimos, ab corporis atque! Quaerat, officia! Alias architecto nemo quod, ipsum ab accusamus, quis beatae enim harum porro, officia excepturi?
        Doloremque magni, quaerat natus reiciendis ex optio! Beatae totam cum, similique ipsam odit fuga molestiae omnis corporis, quas facere laboriosam esse optio quos id rem impedit, rerum reprehenderit fugit aperiam?
        Possimus ut nemo doloremque tenetur neque corporis suscipit numquam molestias reiciendis natus? Quaerat libero doloremque commodi inventore, consequatur illum eveniet fugit dolores ad, neque velit facere veniam repudiandae, impedit aut.
        Libero voluptatem, rem necessitatibus veritatis autem impedit a expedita pariatur incidunt sapiente aspernatur eum quas soluta reiciendis voluptate cum! Magni totam quas ullam ab vitae iure facere, harum sed voluptatem.
        Itaque ipsum sapiente adipisci illum officia! Dolorum repellendus quod qui corporis deleniti, veritatis accusamus, distinctio quos maiores asperiores expedita quas ex numquam provident accusantium! Provident possimus exercitationem quidem dolorem ipsa.
        Necessitatibus, quod rem cumque iure iusto quibusdam dolorum vel ipsa, possimus explicabo eaque, beatae inventore maxime pariatur ab? Ducimus esse illo autem, alias voluptatum sunt inventore tenetur libero laborum dolore.
        In ut architecto accusantium at facilis soluta laudantium error vitae eum voluptate, ipsa, reprehenderit ipsum alias totam reiciendis rem excepturi? Recusandae porro neque consequuntur nesciunt. Nam, consequuntur. Veniam, eius autem?
        Explicabo voluptates quam consectetur. Dignissimos suscipit quo vitae consectetur itaque nihil tenetur amet voluptatem error eligendi maxime modi praesentium veniam, mollitia id, et reiciendis maiores, inventore eaque ducimus ab architecto.
        Delectus maiores ex esse excepturi voluptas at eum. Sint suscipit soluta ullam totam voluptatem! Odio voluptatibus sit commodi nobis suscipit mollitia! Labore fuga recusandae laborum ea voluptas minima architecto quisquam.
        Deserunt velit error voluptatibus, itaque minima enim eum odit possimus corporis autem tempore debitis reprehenderit illum sapiente? Corrupti nam et laudantium reiciendis? Maiores fugiat aliquid accusantium quaerat illum dolorem veritatis!
        Eligendi, est. Saepe cum placeat ullam, veritatis pariatur ipsa blanditiis obcaecati deserunt dicta magni repellendus neque ut voluptate. Deserunt fugit dignissimos adipisci mollitia omnis sed vel sunt nesciunt consequatur suscipit!
        Nulla, laborum pariatur quo atque iste perspiciatis laboriosam ea, dolorum, ut placeat reprehenderit. Quod magnam delectus quibusdam cum laborum corrupti! Commodi mollitia sapiente omnis impedit nulla eum beatae, sequi sit.
        Ut corporis vero dolores cupiditate ad voluptates, laborum voluptatem enim magnam iste vel ratione magni unde animi, necessitatibus reiciendis. Quasi quidem cumque voluptate libero ut corrupti sunt ad blanditiis fuga.
        Id labore, praesentium vel dolorum maxime, officiis suscipit magni fuga dolorem dicta blanditiis molestias, at et quod nihil hic consectetur veritatis similique? Magnam, iste inventore. Officiis, nulla consequatur. Perferendis, doloribus.
        Nihil impedit earum unde consectetur corrupti at est distinctio necessitatibus animi. Sunt voluptatum sit quae pariatur. Quis nisi ab vitae veniam rem quibusdam provident sequi ea aliquam, velit iure et!
        Laudantium perferendis voluptates aperiam facilis ratione aliquid eligendi sint praesentium doloremque commodi, laboriosam quas quasi excepturi, at quae iusto natus nostrum tempore explicabo earum autem! Provident omnis minima rem animi!
        Reiciendis commodi magnam illum magni debitis eligendi incidunt ad temporibus expedita. Officia delectus aspernatur eos est, eius quos numquam eligendi mollitia quaerat quasi nostrum debitis eum distinctio nihil commodi. Labore.
        Repellat voluptatum ratione similique, eligendi voluptatem atque harum aut repellendus quaerat quia eos commodi dolorem perspiciatis quo suscipit! Optio et at laborum, quam ex mollitia impedit vitae obcaecati quis totam!
        Nostrum modi suscipit, impedit nisi neque perferendis autem et temporibus, perspiciatis repellat ullam, inventore laboriosam pariatur error dicta itaque quas? Sit molestias harum itaque, corrupti illo voluptatibus? Beatae, modi voluptatem!
        Aliquid, quia. Harum, corrupti praesentium. In culpa esse repellendus corporis nobis numquam rerum blanditiis eligendi delectus atque vero, deleniti, dolores, tempora sunt hic iusto nemo amet repellat. Beatae, facere maiores!
        Ab consequatur dolorem, exercitationem soluta culpa ratione, accusamus dolor, qui laborum ducimus voluptatem sed sequi dolore nulla. Ipsa impedit ut repudiandae, assumenda quo eum mollitia obcaecati unde. Suscipit, esse vel.
        Quo accusantium ullam nesciunt distinctio ratione voluptate temporibus quaerat. Ipsam ipsa excepturi accusamus, harum praesentium officia magnam quia temporibus omnis maxime iste ipsum doloribus repellendus aspernatur nobis optio eaque necessitatibus.
        Voluptates porro sed natus autem temporibus tempore fugiat perspiciatis odit tempora aspernatur beatae at dignissimos, animi, corrupti error cum molestias amet, corporis iure. Ducimus, nesciunt adipisci sed sequi aperiam veritatis?
        Deleniti sapiente similique culpa maiores quidem placeat! Itaque sed animi consequatur quae doloribus atque, voluptatem dolor ratione sapiente totam fugit omnis quia sit quo perspiciatis dolores. In odio odit non.
        Veritatis aperiam repudiandae et aliquam cum ut laudantium quam neque non magni eveniet iusto hic quas, quo maiores, itaque mollitia similique eos corrupti, illo enim placeat? Qui, beatae quisquam. Porro!
        Excepturi, modi sequi perspiciatis esse tenetur in ipsum cum. Ipsa nulla, iste quisquam sit officiis libero excepturi dolorum exercitationem dolor doloremque unde nisi! Recusandae, quo veniam cumque voluptate veritatis maxime.
        Aspernatur asperiores esse quasi delectus architecto iusto itaque perferendis! Itaque, quos. Doloremque error magni consequuntur vel reiciendis iure tempora eos ad at. Nostrum soluta, ipsam dolore praesentium veniam unde itaque.
        Dicta neque quia est quaerat inventore excepturi! Esse voluptatum nihil doloremque, quos numquam quia modi consectetur aliquid, nobis officia, natus recusandae. Suscipit tempora eius, mollitia aut blanditiis doloremque voluptates ipsa?
        Accusamus mollitia nulla nostrum! Officia assumenda, hic ipsum quos non sit sapiente quis temporibus ullam eius neque soluta rerum! Pariatur eius asperiores eaque, eos autem quisquam iusto sint? At, excepturi.
        Aliquid necessitatibus, quisquam maiores fugiat, voluptatum aliquam assumenda esse, error eum dignissimos reiciendis dicta unde ipsam porro. Alias neque quisquam ipsa, dolorem laboriosam qui quia vitae harum cum eos odit?
        Esse alias omnis hic officiis! Accusantium quasi, ex repudiandae modi ad consectetur dolorem officiis. Distinctio maiores quia numquam eius eos, minima vero accusamus id, rem explicabo temporibus quo enim vel.
        Optio ab consectetur in rerum unde assumenda modi eius eligendi esse quo, sed quam. Eveniet corporis, fuga possimus consequuntur minima libero nesciunt ea quam voluptatum? Necessitatibus ex sed dolorem veniam!
        Autem magnam minus tempora impedit, dolorum aliquid aliquam molestiae sequi error fugiat suscipit, corporis numquam modi et a quasi beatae accusantium? Cum natus maiores expedita rem, quia debitis laudantium perspiciatis?
        Laudantium harum, rem fuga obcaecati aperiam dolores numquam animi nam aut. Ducimus vero, at molestias nulla id adipisci ad perferendis illo nemo corrupti assumenda accusantium voluptatum eveniet ipsum neque architecto?
        Doloremque quia ipsam necessitatibus recusandae ipsa voluptatem in magnam non, dolores quae eveniet, aliquid labore maxime. Cumque distinctio ipsum sapiente omnis ipsam ea dolores doloremque commodi odit deleniti, nobis maxime!
        Vel, laudantium, commodi et voluptatum modi temporibus nostrum adipisci molestias explicabo perspiciatis non tempora delectus, atque excepturi. Veniam hic unde fugiat repellendus quo illo porro architecto, eum pariatur accusantium consequatur?
        Consectetur natus voluptas nobis architecto asperiores, exercitationem inventore beatae laudantium esse ullam distinctio possimus. A in velit repellendus deserunt nostrum iusto, cupiditate libero quia eveniet ipsa, blanditiis voluptas suscipit facilis!
        Voluptatibus aut assumenda quos a excepturi ipsa possimus odio dolorem repudiandae praesentium nostrum esse at, alias suscipit in totam veritatis eligendi impedit deleniti optio modi id accusantium? Nostrum, illum neque!
        Dolorem necessitatibus tempore ducimus quia sit. Fugit nulla odio commodi consequatur molestiae, laboriosam, mollitia in nemo quo reprehenderit ipsum qui rerum placeat. Quae cupiditate fuga provident iusto assumenda inventore quos!
        Modi, cum dolor! Libero optio, ullam soluta molestiae error sunt obcaecati harum, facilis totam officiis ad cumque consequatur quisquam facere exercitationem ab ipsum in quo laborum maxime. Maiores, nihil omnis.
        Dolorem omnis est facilis officia! Harum laborum necessitatibus omnis nihil consectetur cumque labore facilis. Dignissimos quis voluptatibus incidunt doloribus molestias? Dolorum dolorem ad quo labore voluptates. Repellendus libero et exercitationem?
        Nostrum cumque, tenetur, voluptatem minus, numquam eligendi recusandae consequuntur voluptates soluta molestias cum magni. Dolorem repellendus eligendi at adipisci fugit dignissimos deserunt cumque voluptatibus! Amet, unde veritatis! Accusantium, nam odit.
        Nostrum cum blanditiis, rem, dolor distinctio officiis aliquid recusandae consequatur aliquam, facere eveniet eius in amet ab sit praesentium placeat doloremque officia. Et corrupti cumque impedit illo voluptatum iste sit.
        Sit deserunt nobis praesentium vitae iste quo sapiente saepe debitis reiciendis, laborum illum cumque ab perferendis. Suscipit maiores dicta cupiditate nemo itaque natus a hic, excepturi, voluptate quidem mollitia! Saepe!
        Placeat, eos voluptates est voluptas et deserunt culpa maiores incidunt vel expedita nam temporibus quod unde animi dolor maxime sapiente sit non aperiam ex eius explicabo iste aliquid molestias! Voluptatibus?
        Hic, facere adipisci dolore quas harum nam architecto fuga dolorem perferendis perspiciatis assumenda velit saepe voluptatem est ad, corporis cupiditate ut eos voluptas inventore. Explicabo amet voluptates ex accusantium in.
        Dolore eveniet magnam aspernatur consequuntur placeat vero libero totam, iusto ut! Sed vero quaerat velit dolor, maiores omnis nihil officia cumque fugiat reprehenderit impedit veniam blanditiis. Nihil cupiditate fuga consectetur.
        Provident qui earum omnis! Debitis saepe dolore in soluta quibusdam error sit non, perferendis alias unde, suscipit impedit quis aspernatur fugiat consectetur minus rem repellat? Placeat tempora nostrum aut dolorem?
        Accusamus sed natus omnis nam quae officia minus reprehenderit numquam illo! Eligendi eius fugiat consectetur eveniet nostrum beatae, iusto vel nulla delectus nisi est, nam pariatur? Soluta assumenda sapiente at!
        Non hic nam cumque aut architecto, quaerat laboriosam consequatur provident ad! Deserunt voluptatem voluptate debitis adipisci assumenda maxime eius laborum? Dignissimos laboriosam magni magnam, voluptate doloribus placeat rem esse possimus.
        Harum pariatur facilis expedita aut! Officia quis tenetur ratione quidem. Ipsum itaque incidunt quae sequi dicta. Repudiandae alias architecto id non nostrum, unde iste, dicta quos similique aspernatur quia corporis?
        Magnam quod itaque ratione provident ex, dolorem quis dolores omnis non voluptates, eum, excepturi deserunt voluptate quaerat soluta voluptas distinctio aut ipsum est eius minima commodi eveniet sapiente id. Nobis!
        Suscipit vero fuga minima commodi odio quasi quis asperiores voluptas sed veniam officia eveniet tempora sunt, sapiente aut quas corporis dicta magnam est quisquam! Iure tenetur delectus reiciendis perspiciatis in.
        Officiis, officia, qui delectus velit porro minima nulla, quisquam tempore harum rerum dolore libero molestiae? Facere itaque porro quod explicabo, dolores veniam, voluptatibus voluptate ullam ut totam minima eveniet sequi.
        Pariatur eius magni rem nulla recusandae nesciunt. Perspiciatis repudiandae architecto expedita laudantium alias magnam quam earum nisi, accusamus, deserunt iure nemo, adipisci assumenda molestias reiciendis molestiae! Iste nostrum neque nisi!
        Similique mollitia voluptatum ipsa modi ab maiores consequatur blanditiis fugiat. Tempore atque unde et pariatur iste corrupti autem corporis quaerat consequuntur veritatis placeat reprehenderit vel libero, iure esse a commodi!
        Blanditiis sequi, magnam quas omnis similique molestiae rerum facere pariatur amet rem saepe architecto accusamus odio sapiente reprehenderit atque explicabo repudiandae a doloremque. Rerum voluptates quae doloribus ratione. Labore, vitae!
        Temporibus necessitatibus aperiam sunt mollitia enim, commodi quam sint, dolorum neque eaque esse eveniet. Corrupti, eos porro. Quo, obcaecati veniam perspiciatis asperiores tempora sunt sit nobis deserunt ducimus delectus aperiam?
        Tempore sequi quisquam dolore corrupti quam qui sunt provident quibusdam reprehenderit atque nostrum in voluptatum neque ut perspiciatis voluptatem libero veniam nisi enim, omnis doloribus quo! Fugiat amet quisquam deleniti.
        Debitis dicta corrupti unde consequuntur at distinctio doloribus ipsa? Culpa iusto ea repellendus quaerat rerum aliquid officiis cum? Dolor adipisci optio error, assumenda iure fuga provident enim deserunt a odit.
        Enim, ducimus. Maiores nulla perspiciatis quisquam, perferendis rerum voluptate accusantium voluptatum facere temporibus, autem placeat fugit id commodi ullam voluptatem quos vitae ipsa veniam voluptatibus velit quam hic? Voluptatem, quasi.
        Nemo assumenda dolorum animi, error recusandae sed unde laborum rerum repellat inventore nulla magni accusantium labore provident? Tempora libero sequi recusandae, explicabo quaerat nemo dolorum! Eos, repellat quia! Ab, non!
        Perspiciatis nam aspernatur, vero minima voluptatibus possimus necessitatibus? Beatae incidunt mollitia praesentium ullam delectus pariatur, quod natus a nihil, cupiditate saepe possimus amet temporibus quidem at iure provident. Perspiciatis, quod.
        Voluptates repudiandae ut, asperiores in amet porro praesentium aliquam necessitatibus quasi nostrum, ducimus aliquid voluptate accusantium soluta nemo perspiciatis? Voluptate placeat explicabo molestias perspiciatis saepe porro, ea unde dignissimos sunt.
        Aspernatur eius delectus quas ipsam iusto alias doloribus suscipit quod, nam omnis dolores, ratione impedit perferendis at enim et placeat id. Asperiores inventore veniam labore ipsa eius saepe obcaecati praesentium.
        Obcaecati magnam reprehenderit ad dignissimos veritatis temporibus eius, ratione a odit est saepe provident! Provident dolor delectus quod vel fugit eos laborum sunt fugiat aliquid sed animi, cupiditate a illo.
        Omnis possimus in obcaecati unde deleniti hic voluptatum molestiae aut tempore ducimus vitae, illo doloribus soluta quia laudantium perspiciatis ea, corporis ratione dicta a. Voluptas ducimus suscipit fugit possimus est.
        Nihil commodi illo dolor delectus tenetur ipsam reprehenderit eaque natus alias voluptatibus. Non, dolorum similique, quisquam omnis id adipisci error nisi eos in perferendis soluta, corrupti accusantium. Recusandae, cumque blanditiis.
        Quaerat praesentium quia quam ut impedit corrupti architecto itaque cumque aperiam commodi. Asperiores quod inventore illo quibusdam, modi nam mollitia, natus quisquam repellat architecto, officiis incidunt est debitis libero consequatur!
        Soluta facere maxime illum, autem odit aliquid doloribus repellat modi distinctio mollitia corrupti fugit voluptatum ullam ex quod, ut libero ea quis sapiente laudantium eum suscipit harum maiores at? Temporibus?
        Voluptas optio sapiente accusantium fugit omnis amet eligendi dolores aut commodi nulla ad aspernatur, numquam porro officiis alias. Mollitia quidem id quia ut, atque repudiandae dolorum blanditiis excepturi corrupti laudantium.
        Quos debitis totam quae corrupti placeat corporis ea quidem eaque aspernatur. Maiores nobis illo reiciendis aperiam laboriosam dolores alias earum doloribus iusto nisi, architecto culpa, tempora fuga nam placeat cumque!
        Optio ipsum dolores quo minima laudantium culpa fugiat quisquam eum magni, tempore quos voluptate porro sint reprehenderit beatae placeat sed harum similique veritatis commodi! Commodi ipsum fugiat natus. In, reprehenderit!
        Non id adipisci dolore placeat eveniet repellendus similique! Laborum consectetur animi inventore maxime qui omnis. Excepturi voluptatibus mollitia quis dolor? Consequuntur porro facere, placeat voluptas ut deserunt dolorem nulla optio.
        Ad minima natus repudiandae dignissimos eum molestias consequatur soluta deserunt voluptatibus nostrum? Tenetur maiores, doloremque dolore ipsam neque incidunt officia suscipit temporibus hic magnam. Officia laboriosam tempora blanditiis dolorum eos!
        Animi fugiat perspiciatis doloremque neque, earum explicabo nostrum eveniet a! Voluptas a voluptatem, fuga quod quisquam, vel ex ab corrupti dolor, dolorem dolore repudiandae dicta natus itaque aperiam laborum. Magni?
        Corporis, sequi reprehenderit, commodi possimus eos consectetur dolorum minus quae ex fugit officiis? Sed neque dolorum consectetur odio aspernatur vel veritatis similique commodi mollitia numquam? Doloribus ad atque architecto. Sed?
        Placeat dignissimos enim officia. Quos, laboriosam harum aut voluptatibus, dolor repellat officiis natus, temporibus omnis error architecto voluptatum nisi a! At sint incidunt voluptatum ex impedit ratione recusandae maiores delectus?
        Ab assumenda possimus distinctio provident odio omnis sequi facere officia esse? Minima excepturi commodi maxime facilis voluptas modi tenetur aut vitae, cum possimus neque aliquid. Cupiditate voluptatibus eveniet error earum.
        Mollitia, quis magni consequatur quia voluptatum accusamus hic accusantium perspiciatis eius. Commodi animi officiis rem delectus nihil obcaecati pariatur aliquid explicabo, magni molestiae sed nam doloremque nulla non! Veniam, id.
        Dolorum maxime voluptatibus, fugiat recusandae provident reprehenderit quia distinctio, numquam autem aut corporis tempore maiores tempora molestiae. Debitis totam molestiae consectetur officia est, voluptates laborum distinctio necessitatibus, doloribus, molestias magni.
        Tenetur, iure nulla quod impedit corrupti voluptas vero optio, maiores accusantium, eligendi quis suscipit soluta placeat nesciunt quidem est eos numquam enim consequuntur illum deleniti eius. Nemo laboriosam quibusdam alias.
        At, quae nostrum. Quam laborum impedit odit debitis quod praesentium aperiam pariatur, accusamus labore laboriosam sapiente nulla ab necessitatibus eius. Corporis ipsum quisquam ut earum accusantium. Cum, aperiam? Accusamus, repellat.
        Quam modi deleniti vitae aliquam atque rem architecto ipsa fuga illum, accusamus est vero quidem exercitationem doloribus enim, rerum cupiditate ad iure? Adipisci mollitia deleniti impedit corrupti quasi quaerat tempora.
        Illo commodi saepe alias quo aut molestias deserunt accusantium enim quis eum? Commodi similique suscipit necessitatibus magni. A cum beatae molestiae cumque, quae dicta eius ducimus officiis in labore necessitatibus?
        Sequi saepe asperiores, fugit eos eum enim tempore corrupti quae unde quisquam facilis quo dolore beatae accusamus provident nulla aliquid recusandae, rem est quibusdam impedit. Ab inventore laboriosam qui quas?
        Modi perferendis eaque a ipsum non, quas nemo. Ratione, animi nam iure ut dolores impedit atque rerum molestiae facilis, cum, dolorem accusamus sequi eligendi neque officia illo ab tempora alias.
        Totam recusandae dolorem vel ad quas sit, assumenda velit dicta perferendis maxime perspiciatis. Eligendi architecto maxime vitae! Assumenda perspiciatis, nulla repellat vitae, vero numquam explicabo quidem ipsum maxime quasi quibusdam?
        Veritatis, sint? Quas voluptatem nihil voluptate eius porro provident facere molestiae accusamus cumque sapiente ut earum, exercitationem aperiam fugiat. Ad dignissimos ipsa distinctio ab, dicta voluptatum atque cum similique officiis?
        Ducimus facilis adipisci cum nisi repellat necessitatibus. Odio voluptatem, labore eligendi enim reiciendis dignissimos ipsa perferendis maxime aperiam, fuga quisquam, voluptates neque velit qui. Velit fugiat doloribus obcaecati quam earum?
        Sunt, earum possimus voluptate atque dicta sed totam! Minus ea, voluptates assumenda quas asperiores illum, iusto praesentium deserunt velit perferendis cum aperiam? Excepturi error quas fuga odio assumenda corporis? Laboriosam!
        Suscipit maxime corrupti quisquam voluptatibus consectetur, error autem obcaecati porro quaerat, neque quibusdam, quod aut quas voluptate odio explicabo ex facilis illo. Excepturi eveniet adipisci dolor ea aperiam ipsam dignissimos.
        Quisquam, ex ducimus cupiditate quasi sunt repellat odio quaerat deleniti labore autem enim voluptate harum optio laboriosam tempore quibusdam facilis illo quidem. Rerum tenetur eveniet ipsa doloribus ducimus sapiente cum?</h4>
    </body>
</template>

<script>
export default {
    data(){
        return {
            scrollPosition: null,
            mobile: null,
            mobileNav: false,
            windowWidth: null,
        }
    },
    created(){
        this.responsiveNav()
    },
    mounted(){
        window.addEventListener("resize", this.responsiveNav)
        window.addEventListener("scroll", this.updateScroll)
    },
    methods : {
        responsiveNav(){
            this.windowWidth = window.innerWidth;
            if(this.windowWidth <= 750){
                this.mobile = true
                return
            }
            this.mobile = false;
            this.mobileNav = false;

        },
        updateScroll(){
            const scrollposition = window.scrollY;
            if(scrollposition > 50){
                this.scrollPosition = true
                return
            }
            this.scrollPosition = false
        }
    }
}
</script>

<style scoped lang="scss">
header{
    position: fixed;
    background-image: linear-gradient(90deg, #003, #ccc);
    transition: 0.8 ease all;
    width: 100%;
    display: block;
    nav{
        width: 90%;
        height: 100%;
        display: flex;
        align-items: center;
        margin: 0 auto;
        flex-direction: row;
        position: relative;
        transition: 2s  ease all;
        &.navcolor{
            background-color: bisque;
        }
        .logo{
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            background: #000;
        }
        .navigation{
            display: flex;
            flex-direction: row;
            flex: 1;
            justify-content: flex-end;
            ul,
            li,
            .link{
                list-style: none;
                text-decoration: none;
                font-size: 14px;
                text-transform: uppercase;
                margin:  0;
                padding: 0;
                display: inline-block;
            }
            .link{
                display: block;
                margin-left: 16px;
                transition: .5 ease all;
                color: #000;
                border: 1px solid #000;
                padding: 4px;
                &:hover{
                    color: rgb(17, 128, 161);
                    border-color: rgb(17, 128, 161);
                }
            }

        }
        .icon{
            display: flex;
            align-items: center;
            position: absolute;
            right: 0;
            transition: 0.8 ease all;
            cursor: pointer;
        }
        .mobile-nav{
            display: flex;
            width: 250px;
            top: 0;
            left: 0;
            flex-direction: column;
            position: fixed;
            background: #ccc;
            height: 100%;
             ul,
            li,
            .link{
                list-style: none;
                text-decoration: none;
                font-size: 14px;
                text-transform: uppercase;
                margin:  0;
                padding: 0;
                display: inline-block;
            }
            .link{
                transition: .5 ease all;
                color: #000;
                border: 1px solid #000;
                padding: 4px;
                &:hover{
                    color: rgb(17, 128, 161);
                    border-color: rgb(17, 128, 161);
                }
            }
        }

    }
}
</style>