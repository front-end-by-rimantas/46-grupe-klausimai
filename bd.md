# 2023-10-30
* Beklaidžiojant apie css radau tokį css extension'ą Sass. Ar naudojamas praktikoje? Man pasirodė smagus įrankis. Ypač ta vieta, kai gali su import precursorium visą "šaiką" savybių perkelt į vieną selectorių.
* Ar kursų metų dar apžvelgsim iframes. O Jeigu jau apžvelgsim, gal tuo pačiu ir position: sticky?.
* Minėjote, kad id selectoriai realiai naudojami dėl JS. Ar klaidingai supratau, kad JS'e pasiimti elementus tik su ID? Nes gi galima visa krūva ir kitų būdų: pagal klasę, tagą ir t.t. Ar vis dėlto kažkurių iš šių vengti?
* Jeigu jau JS'e parašysiu: ``` getElementsByTagName(<name>).addEventListener('click', function onClick() { // ---- } ``` Tai kas gausis? Aš ant vieno event listenerio "pakabinsiu" visus įmanomus elementus? Nebūna paskui, kad vieną klickini ir visi pagauti tagai atlieka užduotas f-ijas?
* Jeigu vistik knieti su anksčiau minėtu event listeneriu apjungti visus minėtus tagus, gal paskui per kokį nors pointerį įmanoma išskaidyti funkcijas būtent clickinamui objektui? Nu nes kartais gal norisi sutaupyti vietos, ir nerašyti 20 panašių mygtukų, 20 event listenerių - čia grynai dėl "do not repeat yourself" principo.

# 2023-10-16
* Minėjote, kad prieš merginant iš side-branch į main, dažniausiai būna kažkas atsakingas už to (merge) review. Ar git platformoje, tas žmogus gali tik leisti atitinkamiems branchams mergintis, ar ir redaguotį pateiktą kodą (papildyti kodą).
* Projektų valdymo metodologijos. Ką apie jas mums svarbu žinoti. Ir ar tai medžiaga, kuri labiau reikalinga projektų valdytojui.
* Tiksliai žinau, kad programuoti back-endą su duombazėmės, github nedraudžia. O kaip tada, "nedamuštas" produktas pateikiamas užsakovams? Tokiu atveju kodas deploy'namas ne į git live serverį, o jau į specializuotą serverį?

# 2023-10-12
* Paskaitoje minėjote, kad server side ar mato, kad modifikuojame kodą per "inspectą" labai priklauso nuo svetainės. Bet tuo pačiu inspectas sakėte, kad yra tiktai naršyklės laikinoje atmintyje. Tai jeigu vis dėlto yra galimybė tam tikroms svetainėms sekti tokia mūsų veiką, tai kokiu būdu? Išsaugo mūsų kompe tam tikrus logus?
* 2 klausimas į tą pačią temą. Ar eina uždrausti naršyklėms naudoti inspect?
* 3 klausimas. į panašią temą. Kažkada 15min buvo toks bugas, kad kai jie pradėjo naudoti mokamą turinį, rodydavo tik kelias eilutes teksto, tačiau per inspectą, arba select-all => copy => paste, galėdavai skaityti mokamą turinį. Dabar jau jie susitvarkė. Tai čia kažkoks panašus pvz, kaip galima uždrausti inspectinti turinį? 

# 2023-10-11
* Kaip veikia stiliaus position property. Ar nustatant šio property vertes, priverčiame keisti pozicionavimą tik tėvinio el atžvilgiu, ar galima ir brolinių el atžvilgiu? T. Y. Ar galima šia savybe kažkaip pritaikyti elementų išstumdymui. 
* ar html turi galimybe matyti, kad įrenginys buvo rotate'intas? Ar tiesiog pagal santikinius vienetus persistumdo viskas? 
* kuom įpatingi css frameworkai, tarkime bootstram, jie turi daugiau properties, kuriais gali modifikuoti stilių, ar tai yra tarsi stilių biblioteka? 



# 2023-10-10
* Ar nebūtų geriau "\<main\>" tagui išstumdyti naudoti vh ir vw, vietoj %? Ar kadangi main yra html vaikas, html vistiek visa viewport užima?
* Kaip su for ciklu galima itteruoti per spalvų palete nuo baltos #000000 iki juodos #FFFFFF? Kaip iteruoti vieną atspalvį (tikriausiai čia jau ateis Hue kažkur į pagalbą). Ir kokios yra spalvos kryptinės fillinimo f-ijos. Buvau girdėjęs žodelį gradientai, tai čia jaučiu apie tą patį... 
* Kuriant tinklalapius: ar yra web-safe fontų sarašas, kuriuos rekomenduotina naudoti? Jeigu naudoji kažkokį labai įmantrų fontą (kurio faktas gal ne kiekvienas tinklalapio lankytojas turés), gal yra kažkoks work-around? Persiusti fontą laikinai saugoti naršyklėje per coockies ar pan?

# 2023-10-09
* Ar JS yra deconstructorius?
* Aną paskaitą mokėmės išskaidyti vizualų tinklalapį į sudarančius blokus, o šiuos į elementus. Ar teisingai manau, kad greičiausiai išmokti front-endo ir būtų toks būdas. Imti puslapio nuotrauką ir bandyti iš pagrindų jį sukurtį?
* HTTP Methods. Čia kaip suprantu labiau prie duomenų bazių. Eisime prie back-endo?

# 2023-10-08

# 2023-10-07

# 2023-10-06
* Liepėte visada naudoti === arba !==. O jeigu lyginsi tikrai vertes, kurios negali niekada tapti kažkuo kitu. Kaip pvz. Indeksas i for loope? Arba kokiu atveju conditional carType === "wagon", gali tapti true, jei ne identiškam stringui? Gal tokiais atvejais, užtenka == ? 
*

# 2023-10-05
* this pointeris. Kada veikia, o kada nelabai :)
* Kodėl sukuriant objektą skripte pagal function konstruktorių, pats konstruktorius gali būti defined vėliau, negu kuriamas objektas? O kuriant objektą, pagal klasę, to padaryti nebegalima. t.y. klasė turi būti defined anksčiau nei kuriamas objektas...
* Kuriant objektą pagal class su default values: const cat2 = new Cat(); veikia taip pat, kaip const cat2 = new Cat; Ar interpreteris pats prirašo skliaustus ir rašyti su skliaustais būtų tvarkingiau, ar tai nėra taip svarbu?


# 2023-10-04
* JS'e galima inicijuoti variable 1 eilutėje. O ar galima daryti taip: let a, b;  a = b = 0; ??? Ir ar sveikintina tokia praktika?
* Ar return statementas privalo būti būtinai per vieną eilute? t.y. nuo return žodelio iki ; negali būti new line?
* skirtumas tarp šitų f-ijų pavidalų: "const solve = (x, y) => x / y" ir "const solve = (x) => (y) => y / x". Kodėl pirmu atveju eiliškumas x/y, o kitu y/x norint gauti tą patį ats.


# 2023-10-03
* Ar JS'e galima regular type pass'int by reference? Realiai, kai naudojiesi f-ijoje kintamuoje, kuris nėra argument list'e, taip ir gaunasi?
* try-throw-catch ; mokysimės prie JS ar vėliau?
* JS paskutinė savaitė - toliau imsime html ir css, o JS freestyle? :D
* Klausimas ne į temą. jeigu yra domain'as asd.lt, jis dažnmiausiai redirektina į kitą adresą. Kaip shadowint, maskuot, kad įvykus redirektinimui, bei toliau naršant tame psl, matytusi tik domain adresas: asd.lt. Čia jau domain fukncionalumas, ar jau pačios svetainės? 

# 2023-10-02
* Kaip galima išsiloginti kodo veikimo laiką? 
* Best code writing practices for running code smoother. 
* Sprendžiant sudėtingesnius uždavinius labai išsiplečiu su kodo apimtimi. F-ijos tampa gremėzdiškos, nors pagal gerąją praktija f+ija turi atlikti tik 1 darbą. Gal yra kažkokia "litanija", kaip turi atrodyti programos architektūra ir kaip ji turi būti taisyklingai "lipdoma" .

# 2023-09-28
* The for statement creates a loop with 3 optional expressions; for(exp1;exp2;exp3), which are mandatory?
* BigInt panaudojimas full-stacke?
* JS HTML DOM - ar šitą mokinsimės, ar čia jau užklasinė veikla? ar labiau gilinsimės php html dom?

# 2023-09-27
* variable variables.. ten kaip ir viskas aišku - eval('variable'). Ar galima metodui pritaikyti variable method? Kažką tokio? user.${'is married'} ? user.eval('is married').....
* Minėjai, kad išsprendei visus 8 kyu uždavinius... tai kaip ten su STRANGE_STRING[]?
* Kaip JS faile includinti (bloką kodo)/package iš kito JS failo. .. #include, #require kokie nors?

# 2023-09-26
* obj["jonas"] ir obj.jonas skirtumai, panaudojimo galimybėse...
* void paskirtis javascripte. ar tai operatorius, ar funkcija, ar duomenų tipas?
* funkcijos su nežinamu kiekiu argumentų ir jų iteracija. radau tokia sintaksę:
  function(...arg) { // to do stuff }
  kaip atrodytų sintaksė, kai pirmieji argumentai žinomi, maždaug taip? :
  function(arg1, arg2, ...args) { to do stuff }

# 2023-09-25
* Atom IDE buvo toks funkcionalumas, kad editini savo front-endą, ir dešinėj lango pusėj matai savo besikeičiantį psl.
  Ar neina taip padaryti ant VSCode?
* Jeigu jau JS leidžia sudaryti multiTYPE array, tai kodėl "reikėtų" laikytis tekstinių elementų su tik vienu kabučių tipu? Dėl tvarkingumo?
* OBJECT == ASSOCIATIVE ARRAY in JS?
