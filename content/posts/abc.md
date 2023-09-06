---
title: GABCDEF
categories:
  - abc
author: abv
---

***

weight: 5
title: "Emoji Support"
date: 2019-10-01T17:55:28+08:00
lastmod: 2019-10-01T17:55:28+08:00
draft: false
author: "GABCDEF"
authorLink: "https://dillonzq.com"
description: "GABCDEF."
images: \[]
resources:

* name: "featured-image"
  src: "featured-image.jpg"

tags: \["emoji"]
categories: \["Markdown"]

twemoji: false
lightgallery: true
------------------

Emoji can be enabled in a Hugo project in a number of ways.

<!--more-->

The [`emojify`](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates#inline-shortcodes).

To enable emoji globally, set `enableEmoji` to `true` in your [site configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files.

These begin and end with a **colon** and include the **code** of an emoji:

```markdown
Gone camping! {?:}tent: Be back soon.

That is so funny! {?:}joy:
```

The rendered output looks like this:

Gone camping! :tent: Be back soon.

That is so funny! :joy:

The following **cheat sheet** is a useful reference for emoji shorthand codes.

## Smileys & Emotion

### Face Smiling

| icon | code | icon | code |
| :-: | - | :-: | - |
| :grinning: | `grinning` | :smiley: | `smiley` |
| :smile: | `smile` | :grin: | `grin` |
| :laughing: | `laughing` <br /> `satisfied` | :sweat\_smile: | `sweat_smile` |
| :rofl: | `rofl` | :joy: | `joy` |
| :slightly\_smiling\_face: | `slightly_smiling_face` | :upside\_down\_face: | `upside_down_face` |
| :wink: | `wink` | :blush: | `blush` |
| :innocent: | `innocent` | | |

### Face Affection

| icon | code | icon | code |
| :-: | - | :-: | - |
| :heart\_eyes: | `heart_eyes` | :kissing\_heart: | `kissing_heart` |
| :kissing: | `kissing` | :relaxed: | `relaxed` |
| :kissing\_closed\_eyes: | `kissing_closed_eyes` | :kissing\_smiling\_eyes: | `kissing_smiling_eyes` |

### Face Tongue

| icon | code | icon | code |
| :-: | - | :-: | - |
| :yum: | `yum` | :stuck\_out\_tongue: | `stuck_out_tongue` |
| :stuck\_out\_tongue\_winking\_eye: | `stuck_out_tongue_winking_eye` | :stuck\_out\_tongue\_closed\_eyes: | `stuck_out_tongue_closed_eyes` |
| :money\_mouth\_face: | `money_mouth_face` | | |

### Face Hand

| icon | code | icon | code |
| :-: | - | :-: | - |
| :hugs: | `hugs` | :thinking: | `thinking` |

### Face Neutral Skeptical

| icon | code | icon | code |
| :-: | - | :-: | - |
| :zipper\_mouth\_face: | `zipper_mouth_face` | :neutral\_face: | `neutral_face` |
| :expressionless: | `expressionless` | :no\_mouth: | `no_mouth` |
| :smirk: | `smirk` | :unamused: | `unamused` |
| :roll\_eyes: | `roll_eyes` | :grimacing: | `grimacing` |
| :lying\_face: | `lying_face` | | |

### Face Sleepy

| icon | code | icon | code |
| :-: | - | :-: | - |
| :relieved: | `relieved` | :pensive: | `pensive` |
| :sleepy: | `sleepy` | :drooling\_face: | `drooling_face` |
| :sleeping: | `sleeping` | | |

### Face Unwell

| icon | code | icon | code |
| :-: | - | :-: | - |
| :mask: | `mask` | :face\_with\_thermometer: | `face_with_thermometer` |
| :face\_with\_head\_bandage: | `face_with_head_bandage` | :nauseated\_face: | `nauseated_face` |
| :sneezing\_face: | `sneezing_face` | :dizzy\_face: | `dizzy_face` |

### Face Hat

| icon | code | icon | code |
| :-: | - | :-: | - |
| :cowboy\_hat\_face: | `cowboy_hat_face` | | |

### Face Glasses

| icon | code | icon | code |
| :-: | - | :-: | - |
| :sunglasses: | `sunglasses` | :nerd\_face: | `nerd_face` |

### Face Concerned

| icon | code | icon | code |
| :-: | - | :-: | - |
| :confused: | `confused` | :worried: | `worried` |
| :slightly\_frowning\_face: | `slightly_frowning_face` | :frowning\_face: | `frowning_face` |
| :open\_mouth: | `open_mouth` | :hushed: | `hushed` |
| :astonished: | `astonished` | :flushed: | `flushed` |
| :frowning: | `frowning` | :anguished: | `anguished` |
| :fearful: | `fearful` | :cold\_sweat: | `cold_sweat` |
| :disappointed\_relieved: | `disappointed_relieved` | :cry: | `cry` |
| :sob: | `sob` | :scream: | `scream` |
| :confounded: | `confounded` | :persevere: | `persevere` |
| :disappointed: | `disappointed` | :sweat: | `sweat` |
| :weary: | `weary` | :tired\_face: | `tired_face` |

### Face Negative

| icon | code | icon | code |
| :-: | - | :-: | - |
| :triumph: | `triumph` | :pout: | `pout` <br /> `rage` |
| :angry: | `angry` | :smiling\_imp: | `smiling_imp` |
| :imp: | `imp` | :skull: | `skull` |
| :skull\_and\_crossbones: | `skull_and_crossbones` | | |

### Face Costume

| icon | code | icon | code |
| :-: | - | :-: | - |
| :hankey: | `hankey` <br /> `poop` <br /> `shit` | :clown\_face: | `clown_face` |
| :japanese\_ogre: | `japanese_ogre` | :japanese\_goblin: | `japanese_goblin` |
| :ghost: | `ghost` | :alien: | `alien` |
| :space\_invader: | `space_invader` | :robot: | `robot` |

### Cat Face

| icon | code | icon | code |
| :-: | - | :-: | - |
| :smiley\_cat: | `smiley_cat` | :smile\_cat: | `smile_cat` |
| :joy\_cat: | `joy_cat` | :heart\_eyes\_cat: | `heart_eyes_cat` |
| :smirk\_cat: | `smirk_cat` | :kissing\_cat: | `kissing_cat` |
| :scream\_cat: | `scream_cat` | :crying\_cat\_face: | `crying_cat_face` |
| :pouting\_cat: | `pouting_cat` | | |

### Monkey Face

| icon | code | icon | code |
| :-: | - | :-: | - |
| :see\_no\_evil: | `see_no_evil` | :hear\_no\_evil: | `hear_no_evil` |
| :speak\_no\_evil: | `speak_no_evil` | | |

### Emotion

| icon | code | icon | code |
| :-: | - | :-: | - |
| :kiss: | `kiss` | :love\_letter: | `love_letter` |
| :cupid: | `cupid` | :gift\_heart: | `gift_heart` |
| :sparkling\_heart: | `sparkling_heart` | :heartpulse: | `heartpulse` |
| :heartbeat: | `heartbeat` | :revolving\_hearts: | `revolving_hearts` |
| :two\_hearts: | `two_hearts` | :heart\_decoration: | `heart_decoration` |
| :heavy\_heart\_exclamation: | `heavy_heart_exclamation` | :broken\_heart: | `broken_heart` |
| :heart: | `heart` | :yellow\_heart: | `yellow_heart` |
| :green\_heart: | `green_heart` | :blue\_heart: | `blue_heart` |
| :purple\_heart: | `purple_heart` | :black\_heart: | `black_heart` |
| :100: | `100` | :anger: | `anger` |
| :boom: | `boom` <br /> `collision` | :dizzy: | `dizzy` |
| :sweat\_drops: | `sweat_drops` | :dash: | `dash` |
| :hole: | `hole` | :bomb: | `bomb` |
| :speech\_balloon: | `speech_balloon` | :eye\_speech\_bubble: | `eye_speech_bubble` |
| :right\_anger\_bubble: | `right_anger_bubble` | :thought\_balloon: | `thought_balloon` |
| :zzz: | `zzz` | | |

## People & Body

### Hand Fingers Open

| icon | code | icon | code |
| :-: | - | :-: | - |
| :wave: | `wave` | :raised\_back\_of\_hand: | `raised_back_of_hand` |
| :raised\_hand\_with\_fingers\_splayed: | `raised_hand_with_fingers_splayed` | :hand: | `hand` <br /> `raised_hand` |
| :vulcan\_salute: | `vulcan_salute` | | |

### Hand Fingers Partial

| icon | code | icon | code |
| :-: | - | :-: | - |
| :ok\_hand: | `ok_hand` | :v: | `v` |
| :crossed\_fingers: | `crossed_fingers` | :metal: | `metal` |
| :call\_me\_hand: | `call_me_hand` | | |

### Hand Single Finger

| icon | code | icon | code |
| :-: | - | :-: | - |
| :point\_left: | `point_left` | :point\_right: | `point_right` |
| :point\_up\_2: | `point_up_2` | :fu: | `fu` <br /> `middle_finger` |
| :point\_down: | `point_down` | :point\_up: | `point_up` |

### Hand Fingers Closed

| icon | code | icon | code |
| :-: | - | :-: | - |
| :+1: | `+1` <br /> `thumbsup` | :-1: | `-1` <br /> `thumbsdown` |
| :fist: | `fist` <br /> `fist_raised` | :facepunch: | `facepunch` <br /> `fist_oncoming` <br /> `punch` |
| :fist\_left: | `fist_left` | :fist\_right: | `fist_right` |

### Hands

| icon | code | icon | code |
| :-: | - | :-: | - |
| :clap: | `clap` | :raised\_hands: | `raised_hands` |
| :open\_hands: | `open_hands` | :handshake: | `handshake` |
| :pray: | `pray` | | |

### Hand Prop

| icon | code | icon | code |
| :-: | - | :-: | - |
| :writing\_hand: | `writing_hand` | :nail\_care: | `nail_care` |
| :selfie: | `selfie` | | |

### Body Parts

| icon | code | icon | code |
| :-: | - | :-: | - |
| :muscle: | `muscle` | :ear: | `ear` |
| :nose: | `nose` | :eyes: | `eyes` |
| :eye: | `eye` | :tongue: | `tongue` |
| :lips: | `lips` | | |

### Person

| icon | code | icon | code |
| :-: | - | :-: | - |
| :baby: | `baby` | :boy: | `boy` |
| :girl: | `girl` | :blonde\_man: | `blonde_man` <br /> `person_with_blond_hair` |
| :man: | `man` | :woman: | `woman` |
| :blonde\_woman: | `blonde_woman` | :older\_man: | `older_man` |
| :older\_woman: | `older_woman` | | |

### Person Gesture

| icon | code | icon | code |
| :-: | - | :-: | - |
| :frowning\_woman: | `frowning_woman` <br /> `person_frowning` | :frowning\_man: | `frowning_man` |
| :person\_with\_pouting\_face: | `person_with_pouting_face` <br /> `pouting_woman` | :pouting\_man: | `pouting_man` |
| :ng\_woman: | `ng_woman` <br /> `no_good` <br /> `no_good_woman` | :ng\_man: | `ng_man` <br /> `no_good_man` |
| :ok\_woman: | `ok_woman` | :ok\_man: | `ok_man` |
| :information\_desk\_person: | `information_desk_person` <br /> `sassy_woman` <br /> `tipping_hand_woman` | :sassy\_man: | `sassy_man` <br /> `tipping_hand_man` |
| :raising\_hand: | `raising_hand` <br /> `raising_hand_woman` | :raising\_hand\_man: | `raising_hand_man` |
| :bow: | `bow` <br /> `bowing_man` | :bowing\_woman: | `bowing_woman` |
| :man\_facepalming: | `man_facepalming` | :woman\_facepalming: | `woman_facepalming` |
| :man\_shrugging: | `man_shrugging` | :woman\_shrugging: | `woman_shrugging` |

### Person Role

| icon | code | icon | code |
| :-: | - | :-: | - |
| :man\_health\_worker: | `man_health_worker` | :woman\_health\_worker: | `woman_health_worker` |
| :man\_student: | `man_student` | :woman\_student: | `woman_student` |
| :man\_teacher: | `man_teacher` | :woman\_teacher: | `woman_teacher` |
| :man\_judge: | `man_judge` | :woman\_judge: | `woman_judge` |
| :man\_farmer: | `man_farmer` | :woman\_farmer: | `woman_farmer` |
| :man\_cook: | `man_cook` | :woman\_cook: | `woman_cook` |
| :man\_mechanic: | `man_mechanic` | :woman\_mechanic: | `woman_mechanic` |
| :man\_factory\_worker: | `man_factory_worker` | :woman\_factory\_worker: | `woman_factory_worker` |
| :man\_office\_worker: | `man_office_worker` | :woman\_office\_worker: | `woman_office_worker` |
| :man\_scientist: | `man_scientist` | :woman\_scientist: | `woman_scientist` |
| :man\_technologist: | `man_technologist` | :woman\_technologist: | `woman_technologist` |
| :man\_singer: | `man_singer` | :woman\_singer: | `woman_singer` |
| :man\_artist: | `man_artist` | :woman\_artist: | `woman_artist` |
| :man\_pilot: | `man_pilot` | :woman\_pilot: | `woman_pilot` |
| :man\_astronaut: | `man_astronaut` | :woman\_astronaut: | `woman_astronaut` |
| :man\_firefighter: | `man_firefighter` | :woman\_firefighter: | `woman_firefighter` |
| :cop: | `cop` <br /> `policeman` | :policewoman: | `policewoman` |
| :detective: | `detective` <br /> `male_detective` | :female\_detective: | `female_detective` |
| :guardsman: | `guardsman` | :guardswoman: | `guardswoman` |
| :construction\_worker: | `construction_worker` <br /> `construction_worker_man` | :construction\_worker\_woman: | `construction_worker_woman` |
| :prince: | `prince` | :princess: | `princess` |
| :man\_with\_turban: | `man_with_turban` | :woman\_with\_turban: | `woman_with_turban` |
| :man\_with\_gua\_pi\_mao: | `man_with_gua_pi_mao` | :man\_in\_tuxedo: | `man_in_tuxedo` |
| :bride\_with\_veil: | `bride_with_veil` | :pregnant\_woman: | `pregnant_woman` |

### Person Fantasy

| icon | code | icon | code |
| :-: | - | :-: | - |
| :angel: | `angel` | :santa: | `santa` |
| :mrs\_claus: | `mrs_claus` | | |

### Person Activity

| icon | code | icon | code |
| :-: | - | :-: | - |
| :massage: | `massage` <br /> `massage_woman` | :massage\_man: | `massage_man` |
| :haircut: | `haircut` <br /> `haircut_woman` | :haircut\_man: | `haircut_man` |
| :walking: | `walking` <br /> `walking_man` | :walking\_woman: | `walking_woman` |
| :runner: | `runner` <br /> `running` <br /> `running_man` | :running\_woman: | `running_woman` |
| :dancer: | `dancer` | :man\_dancing: | `man_dancing` |
| :business\_suit\_levitating: | `business_suit_levitating` | :dancers: | `dancers` <br /> `dancing_women` |
| :dancing\_men: | `dancing_men` | | |

### Person Sport

| icon | code | icon | code |
| :-: | - | :-: | - |
| :person\_fencing: | `person_fencing` | :horse\_racing: | `horse_racing` |
| :skier: | `skier` | :snowboarder: | `snowboarder` |
| :golfing\_man: | `golfing_man` | :golfing\_woman: | `golfing_woman` |
| :surfer: | `surfer` <br /> `surfing_man` | :surfing\_woman: | `surfing_woman` |
| :rowboat: | `rowboat` <br /> `rowing_man` | :rowing\_woman: | `rowing_woman` |
| :swimmer: | `swimmer` <br /> `swimming_man` | :swimming\_woman: | `swimming_woman` |
| :basketball\_man: | `basketball_man` | :basketball\_woman: | `basketball_woman` |
| :weight\_lifting\_man: | `weight_lifting_man` | :weight\_lifting\_woman: | `weight_lifting_woman` |
| :bicyclist: | `bicyclist` <br /> `biking_man` | :biking\_woman: | `biking_woman` |
| :mountain\_bicyclist: | `mountain_bicyclist` <br /> `mountain_biking_man` | :mountain\_biking\_woman: | `mountain_biking_woman` |
| :man\_cartwheeling: | `man_cartwheeling` | :woman\_cartwheeling: | `woman_cartwheeling` |
| :men\_wrestling: | `men_wrestling` | :women\_wrestling: | `women_wrestling` |
| :man\_playing\_water\_polo: | `man_playing_water_polo` | :woman\_playing\_water\_polo: | `woman_playing_water_polo` |
| :man\_playing\_handball: | `man_playing_handball` | :woman\_playing\_handball: | `woman_playing_handball` |
| :man\_juggling: | `man_juggling` | :woman\_juggling: | `woman_juggling` |

### Person Resting

| icon | code | icon | code |
| :-: | - | :-: | - |
| :bath: | `bath` | :sleeping\_bed: | `sleeping_bed` |

### Family

| icon | code | icon | code |
| :-: | - | :-: | - |
| :two\_women\_holding\_hands: | `two_women_holding_hands` | :couple: | `couple` |
| :two\_men\_holding\_hands: | `two_men_holding_hands` | :couplekiss\_man\_woman: | `couplekiss_man_woman` |
| :couplekiss\_man\_man: | `couplekiss_man_man` | :couplekiss\_woman\_woman: | `couplekiss_woman_woman` |
| :couple\_with\_heart: | `couple_with_heart` <br /> `couple_with_heart_woman_man` | :couple\_with\_heart\_man\_man: | `couple_with_heart_man_man` |
| :couple\_with\_heart\_woman\_woman: | `couple_with_heart_woman_woman` | :family: | `family` <br /> `family_man_woman_boy` |
| :family\_man\_woman\_girl: | `family_man_woman_girl` | :family\_man\_woman\_girl\_boy: | `family_man_woman_girl_boy` |
| :family\_man\_woman\_boy\_boy: | `family_man_woman_boy_boy` | :family\_man\_woman\_girl\_girl: | `family_man_woman_girl_girl` |
| :family\_man\_man\_boy: | `family_man_man_boy` | :family\_man\_man\_girl: | `family_man_man_girl` |
| :family\_man\_man\_girl\_boy: | `family_man_man_girl_boy` | :family\_man\_man\_boy\_boy: | `family_man_man_boy_boy` |
| :family\_man\_man\_girl\_girl: | `family_man_man_girl_girl` | :family\_woman\_woman\_boy: | `family_woman_woman_boy` |
| :family\_woman\_woman\_girl: | `family_woman_woman_girl` | :family\_woman\_woman\_girl\_boy: | `family_woman_woman_girl_boy` |
| :family\_woman\_woman\_boy\_boy: | `family_woman_woman_boy_boy` | :family\_woman\_woman\_girl\_girl: | `family_woman_woman_girl_girl` |
| :family\_man\_boy: | `family_man_boy` | :family\_man\_boy\_boy: | `family_man_boy_boy` |
| :family\_man\_girl: | `family_man_girl` | :family\_man\_girl\_boy: | `family_man_girl_boy` |
| :family\_man\_girl\_girl: | `family_man_girl_girl` | :family\_woman\_boy: | `family_woman_boy` |
| :family\_woman\_boy\_boy: | `family_woman_boy_boy` | :family\_woman\_girl: | `family_woman_girl` |
| :family\_woman\_girl\_boy: | `family_woman_girl_boy` | :family\_woman\_girl\_girl: | `family_woman_girl_girl` |

### Person Symbol

| icon | code | icon | code |
| :-: | - | :-: | - |
| :speaking\_head: | `speaking_head` | :bust\_in\_silhouette: | `bust_in_silhouette` |
| :busts\_in\_silhouette: | `busts_in_silhouette` | :footprints: | `footprints` |

## Animals & Nature

### Animal Mammal

| icon | code | icon | code |
| :-: | - | :-: | - |
| :monkey\_face: | `monkey_face` | :monkey: | `monkey` |
| :gorilla: | `gorilla` | :dog: | `dog` |
| :dog2: | `dog2` | :poodle: | `poodle` |
| :wolf: | `wolf` | :fox\_face: | `fox_face` |
| :cat: | `cat` | :cat2: | `cat2` |
| :lion: | `lion` | :tiger: | `tiger` |
| :tiger2: | `tiger2` | :leopard: | `leopard` |
| :horse: | `horse` | :racehorse: | `racehorse` |
| :unicorn: | `unicorn` | :deer: | `deer` |
| :cow: | `cow` | :ox: | `ox` |
| :water\_buffalo: | `water_buffalo` | :cow2: | `cow2` |
| :pig: | `pig` | :pig2: | `pig2` |
| :boar: | `boar` | :pig\_nose: | `pig_nose` |
| :ram: | `ram` | :sheep: | `sheep` |
| :goat: | `goat` | :dromedary\_camel: | `dromedary_camel` |
| :camel: | `camel` | :elephant: | `elephant` |
| :rhinoceros: | `rhinoceros` | :mouse: | `mouse` |
| :mouse2: | `mouse2` | :rat: | `rat` |
| :hamster: | `hamster` | :rabbit: | `rabbit` |
| :rabbit2: | `rabbit2` | :chipmunk: | `chipmunk` |
| :bat: | `bat` | :bear: | `bear` |
| :koala: | `koala` | :panda\_face: | `panda_face` |
| :feet: | `feet` <br /> `paw_prints` | | |

### Animal Bird

| icon | code | icon | code |
| :-: | - | :-: | - |
| :turkey: | `turkey` | :chicken: | `chicken` |
| :rooster: | `rooster` | :hatching\_chick: | `hatching_chick` |
| :baby\_chick: | `baby_chick` | :hatched\_chick: | `hatched_chick` |
| :bird: | `bird` | :penguin: | `penguin` |
| :dove: | `dove` | :eagle: | `eagle` |
| :duck: | `duck` | :owl: | `owl` |

### Animal Amphibian

| icon | code | icon | code |
| :-: | - | :-: | - |
| :frog: | `frog` |

### Animal Reptile

| icon | code | icon | code |
| :-: | - | :-: | - |
| :crocodile: | `crocodile` | :turtle: | `turtle` |
| :lizard: | `lizard` | :snake: | `snake` |
| :dragon\_face: | `dragon_face` | :dragon: | `dragon` |

### Animal Marine

| icon | code | icon | code |
| :-: | - | :-: | - |
| :whale: | `whale` | :whale2: | `whale2` |
| :dolphin: | `dolphin` <br /> `flipper` | :fish: | `fish` |
| :tropical\_fish: | `tropical_fish` | :blowfish: | `blowfish` |
| :shark: | `shark` | :octopus: | `octopus` |
| :shell: | `shell` | | |

### Animal Bug

| icon | code | icon | code |
| :-: | - | :-: | - |
| :snail: | `snail` | :butterfly: | `butterfly` |
| :bug: | `bug` | :ant: | `ant` |
| :bee: | `bee` <br /> `honeybee` | :beetle: | `beetle` |
| :spider: | `spider` | :spider\_web: | `spider_web` |
| :scorpion: | `scorpion` | | |

### Plant Flower

| icon | code | icon | code |
| :-: | - | :-: | - |
| :bouquet: | `bouquet` | :cherry\_blossom: | `cherry_blossom` |
| :white\_flower: | `white_flower` | :rosette: | `rosette` |
| :rose: | `rose` | :wilted\_flower: | `wilted_flower` |
| :hibiscus: | `hibiscus` | :sunflower: | `sunflower` |
| :blossom: | `blossom` | :tulip: | `tulip` |

### Plant Other

| icon | code | icon | code |
| :-: | - | :-: | - |
| :seedling: | `seedling` | :evergreen\_tree: | `evergreen_tree` |
| :deciduous\_tree: | `deciduous_tree` | :palm\_tree: | `palm_tree` |
| :cactus: | `cactus` | :ear\_of\_rice: | `ear_of_rice` |
| :herb: | `herb` | :shamrock: | `shamrock` |
| :four\_leaf\_clover: | `four_leaf_clover` | :maple\_leaf: | `maple_leaf` |
| :fallen\_leaf: | `fallen_leaf` | :leaves: | `leaves` |

## Food & Drink

### Food Fruit

| icon | code | icon | code |
| :-: | - | :-: | - |
| :grapes: | `grapes` | :melon: | `melon` |
| :watermelon: | `watermelon` | :mandarin: | `mandarin` <br /> `orange` <br /> `tangerine` |
| :lemon: | `lemon` | :banana: | `banana` |
| :pineapple: | `pineapple` | :apple: | `apple` |
| :green\_apple: | `green_apple` | :pear: | `pear` |
| :peach: | `peach` | :cherries: | `cherries` |
| :strawberry: | `strawberry` | :kiwi\_fruit: | `kiwi_fruit` |
| :tomato: | `tomato` | | |

### Food Vegetable

| icon | code | icon | code |
| :-: | - | :-: | - |
| :avocado: | `avocado` | :eggplant: | `eggplant` |
| :potato: | `potato` | :carrot: | `carrot` |
| :corn: | `corn` | :hot\_pepper: | `hot_pepper` |
| :cucumber: | `cucumber` | :mushroom: | `mushroom` |
| :peanuts: | `peanuts` | :chestnut: | `chestnut` |

### Food Prepared

| icon | code | icon | code |
| :-: | - | :-: | - |
| :bread: | `bread` | :croissant: | `croissant` |
| :baguette\_bread: | `baguette_bread` | :pancakes: | `pancakes` |
| :cheese: | `cheese` | :meat\_on\_bone: | `meat_on_bone` |
| :poultry\_leg: | `poultry_leg` | :bacon: | `bacon` |
| :hamburger: | `hamburger` | :fries: | `fries` |
| :pizza: | `pizza` | :hotdog: | `hotdog` |
| :taco: | `taco` | :burrito: | `burrito` |
| :stuffed\_flatbread: | `stuffed_flatbread` | :egg: | `egg` |
| :fried\_egg: | `fried_egg` | :shallow\_pan\_of\_food: | `shallow_pan_of_food` |
| :stew: | `stew` | :green\_salad: | `green_salad` |
| :popcorn: | `popcorn` | | |

### Food Asian

| icon | code | icon | code |
| :-: | - | :-: | - |
| :bento: | `bento` | :rice\_cracker: | `rice_cracker` |
| :rice\_ball: | `rice_ball` | :rice: | `rice` |
| :curry: | `curry` | :ramen: | `ramen` |
| :spaghetti: | `spaghetti` | :sweet\_potato: | `sweet_potato` |
| :oden: | `oden` | :sushi: | `sushi` |
| :fried\_shrimp: | `fried_shrimp` | :fish\_cake: | `fish_cake` |
| :dango: | `dango` | | |

### Food Marine

| icon | code | icon | code |
| :-: | - | :-: | - |
| :crab: | `crab` | :shrimp: | `shrimp` |
| :squid: | `squid` | | |

### Food Sweet

| icon | code | icon | code |
| :-: | - | :-: | - |
| :icecream: | `icecream` | :shaved\_ice: | `shaved_ice` |
| :ice\_cream: | `ice_cream` | :doughnut: | `doughnut` |
| :cookie: | `cookie` | :birthday: | `birthday` |
| :cake: | `cake` | :chocolate\_bar: | `chocolate_bar` |
| :candy: | `candy` | :lollipop: | `lollipop` |
| :custard: | `custard` | :honey\_pot: | `honey_pot` |

### Drink

| icon | code | icon | code |
| :-: | - | :-: | - |
| :baby\_bottle: | `baby_bottle` | :milk\_glass: | `milk_glass` |
| :coffee: | `coffee` | :tea: | `tea` |
| :sake: | `sake` | :champagne: | `champagne` |
| :wine\_glass: | `wine_glass` | :cocktail: | `cocktail` |
| :tropical\_drink: | `tropical_drink` | :beer: | `beer` |
| :beers: | `beers` | :clinking\_glasses: | `clinking_glasses` |
| :tumbler\_glass: | `tumbler_glass` | | |

### Dishware

| icon | code | icon | code |
| :-: | - | :-: | - |
| :plate\_with\_cutlery: | `plate_with_cutlery` | :fork\_and\_knife: | `fork_and_knife` |
| :spoon: | `spoon` | :hocho: | `hocho` <br /> `knife` |
| :amphora: | `amphora` | | |

## Travel & Places

### Place Map

| icon | code | icon | code |
| :-: | - | :-: | - |
| :earth\_africa: | `earth_africa` | :earth\_americas: | `earth_americas` |
| :earth\_asia: | `earth_asia` | :globe\_with\_meridians: | `globe_with_meridians` |
| :world\_map: | `world_map` | :japan: | `japan` |

### Place Geographic

| icon | code | icon | code |
| :-: | - | :-: | - |
| :mountain\_snow: | `mountain_snow` | :mountain: | `mountain` |
| :volcano: | `volcano` | :mount\_fuji: | `mount_fuji` |
| :camping: | `camping` | :beach\_umbrella: | `beach_umbrella` |
| :desert: | `desert` | :desert\_island: | `desert_island` |
| :national\_park: | `national_park` | | |

### Place Building

| icon | code | icon | code |
| :-: | - | :-: | - |
| :stadium: | `stadium` | :classical\_building: | `classical_building` |
| :building\_construction: | `building_construction` | :houses: | `houses` |
| :derelict\_house: | `derelict_house` | :house: | `house` |
| :house\_with\_garden: | `house_with_garden` | :office: | `office` |
| :post\_office: | `post_office` | :european\_post\_office: | `european_post_office` |
| :hospital: | `hospital` | :bank: | `bank` |
| :hotel: | `hotel` | :love\_hotel: | `love_hotel` |
| :convenience\_store: | `convenience_store` | :school: | `school` |
| :department\_store: | `department_store` | :factory: | `factory` |
| :japanese\_castle: | `japanese_castle` | :european\_castle: | `european_castle` |
| :wedding: | `wedding` | :tokyo\_tower: | `tokyo_tower` |
| :statue\_of\_liberty: | `statue_of_liberty` | | |

### Place Religious

| icon | code | icon | code |
| :-: | - | :-: | - |
| :church: | `church` | :mosque: | `mosque` |
| :synagogue: | `synagogue` | :shinto\_shrine: | `shinto_shrine` |
| :kaaba: | `kaaba` | | |

### Place Other

| icon | code | icon | code |
| :-: | - | :-: | - |
| :fountain: | `fountain` | :tent: | `tent` |
| :foggy: | `foggy` | :night\_with\_stars: | `night_with_stars` |
| :cityscape: | `cityscape` | :sunrise\_over\_mountains: | `sunrise_over_mountains` |
| :sunrise: | `sunrise` | :city\_sunset: | `city_sunset` |
| :city\_sunrise: | `city_sunrise` | :bridge\_at\_night: | `bridge_at_night` |
| :hotsprings: | `hotsprings` | :carousel\_horse: | `carousel_horse` |
| :ferris\_wheel: | `ferris_wheel` | :roller\_coaster: | `roller_coaster` |
| :barber: | `barber` | :circus\_tent: | `circus_tent` |

### Transport Ground

| icon | code | icon | code |
| :-: | - | :-: | - |
| :steam\_locomotive: | `steam_locomotive` | :railway\_car: | `railway_car` |
| :bullettrain\_side: | `bullettrain_side` | :bullettrain\_front: | `bullettrain_front` |
| :train2: | `train2` | :metro: | `metro` |
| :light\_rail: | `light_rail` | :station: | `station` |
| :tram: | `tram` | :monorail: | `monorail` |
| :mountain\_railway: | `mountain_railway` | :train: | `train` |
| :bus: | `bus` | :oncoming\_bus: | `oncoming_bus` |
| :trolleybus: | `trolleybus` | :minibus: | `minibus` |
| :ambulance: | `ambulance` | :fire\_engine: | `fire_engine` |
| :police\_car: | `police_car` | :oncoming\_police\_car: | `oncoming_police_car` |
| :taxi: | `taxi` | :oncoming\_taxi: | `oncoming_taxi` |
| :car: | `car` <br /> `red_car` | :oncoming\_automobile: | `oncoming_automobile` |
| :blue\_car: | `blue_car` | :truck: | `truck` |
| :articulated\_lorry: | `articulated_lorry` | :tractor: | `tractor` |
| :racing\_car: | `racing_car` | :motorcycle: | `motorcycle` |
| :motor\_scooter: | `motor_scooter` | :bike: | `bike` |
| :kick\_scooter: | `kick_scooter` | :busstop: | `busstop` |
| :motorway: | `motorway` | :railway\_track: | `railway_track` |
| :oil\_drum: | `oil_drum` | :fuelpump: | `fuelpump` |
| :rotating\_light: | `rotating_light` | :traffic\_light: | `traffic_light` |
| :vertical\_traffic\_light: | `vertical_traffic_light` | :stop\_sign: | `stop_sign` |
| :construction: | `construction` | | |

### Transport Water

| icon | code | icon | code |
| :-: | - | :-: | - |
| :anchor: | `anchor` | :boat: | `boat` <br /> `sailboat` |
| :canoe: | `canoe` | :speedboat: | `speedboat` |
| :passenger\_ship: | `passenger_ship` | :ferry: | `ferry` |
| :motor\_boat: | `motor_boat` | :ship: | `ship` |

### Transport Air

| icon | code | icon | code |
| :-: | - | :-: | - |
| :airplane: | `airplane` | :small\_airplane: | `small_airplane` |
| :flight\_departure: | `flight_departure` | :flight\_arrival: | `flight_arrival` |
| :seat: | `seat` | :helicopter: | `helicopter` |
| :suspension\_railway: | `suspension_railway` | :mountain\_cableway: | `mountain_cableway` |
| :aerial\_tramway: | `aerial_tramway` | :artificial\_satellite: | `artificial_satellite` |
| :rocket: | `rocket` | | |

### Hotel

| icon | code | icon | code |
| :-: | - | :-: | - |
| :bellhop\_bell: | `bellhop_bell` |

### Time

| icon | code | icon | code |
| :-: | - | :-: | - |
| :hourglass: | `hourglass` | :hourglass\_flowing\_sand: | `hourglass_flowing_sand` |
| :watch: | `watch` | :alarm\_clock: | `alarm_clock` |
| :stopwatch: | `stopwatch` | :timer\_clock: | `timer_clock` |
| :mantelpiece\_clock: | `mantelpiece_clock` | :clock12: | `clock12` |
| :clock1230: | `clock1230` | :clock1: | `clock1` |
| :clock130: | `clock130` | :clock2: | `clock2` |
| :clock230: | `clock230` | :clock3: | `clock3` |
| :clock330: | `clock330` | :clock4: | `clock4` |
| :clock430: | `clock430` | :clock5: | `clock5` |
| :clock530: | `clock530` | :clock6: | `clock6` |
| :clock630: | `clock630` | :clock7: | `clock7` |
| :clock730: | `clock730` | :clock8: | `clock8` |
| :clock830: | `clock830` | :clock9: | `clock9` |
| :clock930: | `clock930` | :clock10: | `clock10` |
| :clock1030: | `clock1030` | :clock11: | `clock11` |
| :clock1130: | `clock1130` | | |

### Sky & Weather

| icon | code | icon | code |
| :-: | - | :-: | - |
| :new\_moon: | `new_moon` | :waxing\_crescent\_moon: | `waxing_crescent_moon` |
| :first\_quarter\_moon: | `first_quarter_moon` | :moon: | `moon` <br /> `waxing_gibbous_moon` |
| :full\_moon: | `full_moon` | :waning\_gibbous\_moon: | `waning_gibbous_moon` |
| :last\_quarter\_moon: | `last_quarter_moon` | :waning\_crescent\_moon: | `waning_crescent_moon` |
| :crescent\_moon: | `crescent_moon` | :new\_moon\_with\_face: | `new_moon_with_face` |
| :first\_quarter\_moon\_with\_face: | `first_quarter_moon_with_face` | :last\_quarter\_moon\_with\_face: | `last_quarter_moon_with_face` |
| :thermometer: | `thermometer` | :sunny: | `sunny` |
| :full\_moon\_with\_face: | `full_moon_with_face` | :sun\_with\_face: | `sun_with_face` |
| :star: | `star` | :star2: | `star2` |
| :stars: | `stars` | :milky\_way: | `milky_way` |
| :cloud: | `cloud` | :partly\_sunny: | `partly_sunny` |
| :cloud\_with\_lightning\_and\_rain: | `cloud_with_lightning_and_rain` | :sun\_behind\_small\_cloud: | `sun_behind_small_cloud` |
| :sun\_behind\_large\_cloud: | `sun_behind_large_cloud` | :sun\_behind\_rain\_cloud: | `sun_behind_rain_cloud` |
| :cloud\_with\_rain: | `cloud_with_rain` | :cloud\_with\_snow: | `cloud_with_snow` |
| :cloud\_with\_lightning: | `cloud_with_lightning` | :tornado: | `tornado` |
| :fog: | `fog` | :wind\_face: | `wind_face` |
| :cyclone: | `cyclone` | :rainbow: | `rainbow` |
| :closed\_umbrella: | `closed_umbrella` | :open\_umbrella: | `open_umbrella` |
| :umbrella: | `umbrella` | :parasol\_on\_ground: | `parasol_on_ground` |
| :zap: | `zap` | :snowflake: | `snowflake` |
| :snowman\_with\_snow: | `snowman_with_snow` | :snowman: | `snowman` |
| :comet: | `comet` | :fire: | `fire` |
| :droplet: | `droplet` | :ocean: | `ocean` |

## Activities

### Event

| icon | code | icon | code |
| :-: | - | :-: | - |
| :jack\_o\_lantern: | `jack_o_lantern` | :christmas\_tree: | `christmas_tree` |
| :fireworks: | `fireworks` | :sparkler: | `sparkler` |
| :sparkles: | `sparkles` | :balloon: | `balloon` |
| :tada: | `tada` | :confetti\_ball: | `confetti_ball` |
| :tanabata\_tree: | `tanabata_tree` | :bamboo: | `bamboo` |
| :dolls: | `dolls` | :flags: | `flags` |
| :wind\_chime: | `wind_chime` | :rice\_scene: | `rice_scene` |
| :ribbon: | `ribbon` | :gift: | `gift` |
| :reminder\_ribbon: | `reminder_ribbon` | :tickets: | `tickets` |
| :ticket: | `ticket` | | |

### Award Medal

| icon | code | icon | code |
| :-: | - | :-: | - |
| :medal\_military: | `medal_military` | :trophy: | `trophy` |
| :medal\_sports: | `medal_sports` | :1st\_place\_medal: | `1st_place_medal` |
| :2nd\_place\_medal: | `2nd_place_medal` | :3rd\_place\_medal: | `3rd_place_medal` |

### Sport

| icon | code | icon | code |
| :-: | - | :-: | - |
| :soccer: | `soccer` | :baseball: | `baseball` |
| :basketball: | `basketball` | :volleyball: | `volleyball` |
| :football: | `football` | :rugby\_football: | `rugby_football` |
| :tennis: | `tennis` | :bowling: | `bowling` |
| :cricket: | `cricket` | :field\_hockey: | `field_hockey` |
| :ice\_hockey: | `ice_hockey` | :ping\_pong: | `ping_pong` |
| :badminton: | `badminton` | :boxing\_glove: | `boxing_glove` |
| :martial\_arts\_uniform: | `martial_arts_uniform` | :goal\_net: | `goal_net` |
| :golf: | `golf` | :ice\_skate: | `ice_skate` |
| :fishing\_pole\_and\_fish: | `fishing_pole_and_fish` | :running\_shirt\_with\_sash: | `running_shirt_with_sash` |
| :ski: | `ski` | | |

### Game

| icon | code | icon | code |
| :-: | - | :-: | - |
| :dart: | `dart` | :8ball: | `8ball` |
| :crystal\_ball: | `crystal_ball` | :video\_game: | `video_game` |
| :joystick: | `joystick` | :slot\_machine: | `slot_machine` |
| :game\_die: | `game_die` | :spades: | `spades` |
| :hearts: | `hearts` | :diamonds: | `diamonds` |
| :clubs: | `clubs` | :black\_joker: | `black_joker` |
| :mahjong: | `mahjong` | :flower\_playing\_cards: | `flower_playing_cards` |

### Arts & Crafts

| icon | code | icon | code |
| :-: | - | :-: | - |
| :performing\_arts: | `performing_arts` | :framed\_picture: | `framed_picture` |
| :art: | `art` | | |

## Objects

### Clothing

| icon | code | icon | code |
| :-: | - | :-: | - |
| :eyeglasses: | `eyeglasses` | :dark\_sunglasses: | `dark_sunglasses` |
| :necktie: | `necktie` | :shirt: | `shirt` <br /> `tshirt` |
| :jeans: | `jeans` | :dress: | `dress` |
| :kimono: | `kimono` | :bikini: | `bikini` |
| :womans\_clothes: | `womans_clothes` | :purse: | `purse` |
| :handbag: | `handbag` | :pouch: | `pouch` |
| :shopping: | `shopping` | :school\_satchel: | `school_satchel` |
| :mans\_shoe: | `mans_shoe` <br /> `shoe` | :athletic\_shoe: | `athletic_shoe` |
| :high\_heel: | `high_heel` | :sandal: | `sandal` |
| :boot: | `boot` | :crown: | `crown` |
| :womans\_hat: | `womans_hat` | :tophat: | `tophat` |
| :mortar\_board: | `mortar_board` | :rescue\_worker\_helmet: | `rescue_worker_helmet` |
| :prayer\_beads: | `prayer_beads` | :lipstick: | `lipstick` |
| :ring: | `ring` | :gem: | `gem` |

### Sound

| icon | code | icon | code |
| :-: | - | :-: | - |
| :mute: | `mute` | :speaker: | `speaker` |
| :sound: | `sound` | :loud\_sound: | `loud_sound` |
| :loudspeaker: | `loudspeaker` | :mega: | `mega` |
| :postal\_horn: | `postal_horn` | :bell: | `bell` |
| :no\_bell: | `no_bell` | | |

### Music

| icon | code | icon | code |
| :-: | - | :-: | - |
| :musical\_score: | `musical_score` | :musical\_note: | `musical_note` |
| :notes: | `notes` | :studio\_microphone: | `studio_microphone` |
| :level\_slider: | `level_slider` | :control\_knobs: | `control_knobs` |
| :microphone: | `microphone` | :headphones: | `headphones` |
| :radio: | `radio` | | |

### Musical Instrument

| icon | code | icon | code |
| :-: | - | :-: | - |
| :saxophone: | `saxophone` | :guitar: | `guitar` |
| :musical\_keyboard: | `musical_keyboard` | :trumpet: | `trumpet` |
| :violin: | `violin` | :drum: | `drum` |

### Phone

| icon | code | icon | code |
| :-: | - | :-: | - |
| :iphone: | `iphone` | :calling: | `calling` |
| :phone: | `phone` <br /> `telephone` | :telephone\_receiver: | `telephone_receiver` |
| :pager: | `pager` | :fax: | `fax` |

### Computer

| icon | code | icon | code |
| :-: | - | :-: | - |
| :battery: | `battery` | :electric\_plug: | `electric_plug` |
| :computer: | `computer` | :desktop\_computer: | `desktop_computer` |
| :printer: | `printer` | :keyboard: | `keyboard` |
| :computer\_mouse: | `computer_mouse` | :trackball: | `trackball` |
| :minidisc: | `minidisc` | :floppy\_disk: | `floppy_disk` |
| :cd: | `cd` | :dvd: | `dvd` |

### Light & Video

| icon | code | icon | code |
| :-: | - | :-: | - |
| :movie\_camera: | `movie_camera` | :film\_strip: | `film_strip` |
| :film\_projector: | `film_projector` | :clapper: | `clapper` |
| :tv: | `tv` | :camera: | `camera` |
| :camera\_flash: | `camera_flash` | :video\_camera: | `video_camera` |
| :vhs: | `vhs` | :mag: | `mag` |
| :mag\_right: | `mag_right` | :candle: | `candle` |
| :bulb: | `bulb` | :flashlight: | `flashlight` |
| :izakaya\_lantern: | `izakaya_lantern` <br /> `lantern` | | |

### Book Paper

| icon | code | icon | code |
| :-: | - | :-: | - |
| :notebook\_with\_decorative\_cover: | `notebook_with_decorative_cover` | :closed\_book: | `closed_book` |
| :book: | `book` <br /> `open_book` | :green\_book: | `green_book` |
| :blue\_book: | `blue_book` | :orange\_book: | `orange_book` |
| :books: | `books` | :notebook: | `notebook` |
| :ledger: | `ledger` | :page\_with\_curl: | `page_with_curl` |
| :scroll: | `scroll` | :page\_facing\_up: | `page_facing_up` |
| :newspaper: | `newspaper` | :newspaper\_roll: | `newspaper_roll` |
| :bookmark\_tabs: | `bookmark_tabs` | :bookmark: | `bookmark` |
| :label: | `label` | | |

### Money

| icon | code | icon | code |
| :-: | - | :-: | - |
| :moneybag: | `moneybag` | :yen: | `yen` |
| :dollar: | `dollar` | :euro: | `euro` |
| :pound: | `pound` | :money\_with\_wings: | `money_with_wings` |
| :credit\_card: | `credit_card` | :chart: | `chart` |

### Mail

| icon | code | icon | code |
| :-: | - | :-: | - |
| :email: | `email` <br /> `envelope` | :e-mail: | `:e-mail:` |
| :incoming\_envelope: | `incoming_envelope` | :envelope\_with\_arrow: | `envelope_with_arrow` |
| :outbox\_tray: | `outbox_tray` | :inbox\_tray: | `inbox_tray` |
| :package: | `package` | :mailbox: | `mailbox` |
| :mailbox\_closed: | `mailbox_closed` | :mailbox\_with\_mail: | `mailbox_with_mail` |
| :mailbox\_with\_no\_mail: | `mailbox_with_no_mail` | :postbox: | `postbox` |
| :ballot\_box: | `ballot_box` | | |

### Writing

| icon | code | icon | code |
| :-: | - | :-: | - |
| :pencil2: | `pencil2` | :black\_nib: | `black_nib` |
| :fountain\_pen: | `fountain_pen` | :pen: | `pen` |
| :paintbrush: | `paintbrush` | :crayon: | `crayon` |
| :memo: | `memo` <br /> `pencil` | | |

### Office

| icon | code | icon | code |
| :-: | - | :-: | - |
| :briefcase: | `briefcase` | :file\_folder: | `file_folder` |
| :open\_file\_folder: | `open_file_folder` | :card\_index\_dividers: | `card_index_dividers` |
| :date: | `date` | :calendar: | `calendar` |
| :spiral\_notepad: | `spiral_notepad` | :spiral\_calendar: | `spiral_calendar` |
| :card\_index: | `card_index` | :chart\_with\_upwards\_trend: | `chart_with_upwards_trend` |
| :chart\_with\_downwards\_trend: | `chart_with_downwards_trend` | :bar\_chart: | `bar_chart` |
| :clipboard: | `clipboard` | :pushpin: | `pushpin` |
| :round\_pushpin: | `round_pushpin` | :paperclip: | `paperclip` |
| :paperclips: | `paperclips` | :straight\_ruler: | `straight_ruler` |
| :triangular\_ruler: | `triangular_ruler` | :scissors: | `scissors` |
| :card\_file\_box: | `card_file_box` | :file\_cabinet: | `file_cabinet` |
| :wastebasket: | `wastebasket` | | |

### Lock

| icon | code | icon | code |
| :-: | - | :-: | - |
| :lock: | `lock` | :unlock: | `unlock` |
| :lock\_with\_ink\_pen: | `lock_with_ink_pen` | :closed\_lock\_with\_key: | `closed_lock_with_key` |
| :key: | `key` | :old\_key: | `old_key` |

### Tool

| icon | code | icon | code |
| :-: | - | :-: | - |
| :hammer: | `hammer` | :pick: | `pick` |
| :hammer\_and\_pick: | `hammer_and_pick` | :hammer\_and\_wrench: | `hammer_and_wrench` |
| :dagger: | `dagger` | :crossed\_swords: | `crossed_swords` |
| :gun: | `gun` | :bow\_and\_arrow: | `bow_and_arrow` |
| :shield: | `shield` | :wrench: | `wrench` |
| :nut\_and\_bolt: | `nut_and_bolt` | :gear: | `gear` |
| :clamp: | `clamp` | :balance\_scale: | `balance_scale` |
| :link: | `link` | :chains: | `chains` |

### Science

| icon | code | icon | code |
| :-: | - | :-: | - |
| :alembic: | `alembic` | :microscope: | `microscope` |
| :telescope: | `telescope` | :satellite: | `satellite` |

### Medical

| icon | code | icon | code |
| :-: | - | :-: | - |
| :syringe: | `syringe` | :pill: | `pill` |

### Household

| icon | code | icon | code |
| :-: | - | :-: | - |
| :door: | `door` | :bed: | `bed` |
| :couch\_and\_lamp: | `couch_and_lamp` | :toilet: | `toilet` |
| :shower: | `shower` | :bathtub: | `bathtub` |
| :shopping\_cart: | `shopping_cart` | | |

### Other Object

| icon | code | icon | code |
| :-: | - | :-: | - |
| :smoking: | `smoking` | :coffin: | `coffin` |
| :funeral\_urn: | `funeral_urn` | :moyai: | `moyai` |

## Symbols

### Transport Sign

| icon | code | icon | code |
| :-: | - | :-: | - |
| :atm: | `atm` | :put\_litter\_in\_its\_place: | `put_litter_in_its_place` |
| :potable\_water: | `potable_water` | :wheelchair: | `wheelchair` |
| :mens: | `mens` | :womens: | `womens` |
| :restroom: | `restroom` | :baby\_symbol: | `baby_symbol` |
| :wc: | `wc` | :passport\_control: | `passport_control` |
| :customs: | `customs` | :baggage\_claim: | `baggage_claim` |
| :left\_luggage: | `left_luggage` | | |

### Warning

| icon | code | icon | code |
| :-: | - | :-: | - |
| :warning: | `warning` | :children\_crossing: | `children_crossing` |
| :no\_entry: | `no_entry` | :no\_entry\_sign: | `no_entry_sign` |
| :no\_bicycles: | `no_bicycles` | :no\_smoking: | `no_smoking` |
| :do\_not\_litter: | `do_not_litter` | :non-potable\_water: | `:non-potable_water:` |
| :no\_pedestrians: | `no_pedestrians` | :no\_mobile\_phones: | `no_mobile_phones` |
| :underage: | `underage` | :radioactive: | `radioactive` |
| :biohazard: | `biohazard` | | |

### Arrow

| icon | code | icon | code |
| :-: | - | :-: | - |
| :arrow\_up: | `arrow_up` | :arrow\_upper\_right: | `arrow_upper_right` |
| :arrow\_right: | `arrow_right` | :arrow\_lower\_right: | `arrow_lower_right` |
| :arrow\_down: | `arrow_down` | :arrow\_lower\_left: | `arrow_lower_left` |
| :arrow\_left: | `arrow_left` | :arrow\_upper\_left: | `arrow_upper_left` |
| :arrow\_up\_down: | `arrow_up_down` | :left\_right\_arrow: | `left_right_arrow` |
| :leftwards\_arrow\_with\_hook: | `leftwards_arrow_with_hook` | :arrow\_right\_hook: | `arrow_right_hook` |
| :arrow\_heading\_up: | `arrow_heading_up` | :arrow\_heading\_down: | `arrow_heading_down` |
| :arrows\_clockwise: | `arrows_clockwise` | :arrows\_counterclockwise: | `arrows_counterclockwise` |
| :back: | `back` | :end: | `end` |
| :on: | `on` | :soon: | `soon` |
| :top: | `top` | | |

### Religion

| icon | code | icon | code |
| :-: | - | :-: | - |
| :place\_of\_worship: | `place_of_worship` | :atom\_symbol: | `atom_symbol` |
| :om: | `om` | :star\_of\_david: | `star_of_david` |
| :wheel\_of\_dharma: | `wheel_of_dharma` | :yin\_yang: | `yin_yang` |
| :latin\_cross: | `latin_cross` | :orthodox\_cross: | `orthodox_cross` |
| :star\_and\_crescent: | `star_and_crescent` | :peace\_symbol: | `peace_symbol` |
| :menorah: | `menorah` | :six\_pointed\_star: | `six_pointed_star` |

### Zodiac

| icon | code | icon | code |
| :-: | - | :-: | - |
| :aries: | `aries` | :taurus: | `taurus` |
| :gemini: | `gemini` | :cancer: | `cancer` |
| :leo: | `leo` | :virgo: | `virgo` |
| :libra: | `libra` | :scorpius: | `scorpius` |
| :sagittarius: | `sagittarius` | :capricorn: | `capricorn` |
| :aquarius: | `aquarius` | :pisces: | `pisces` |
| :ophiuchus: | `ophiuchus` | | |

### Av Symbol

| icon | code | icon | code |
| :-: | - | :-: | - |
| :twisted\_rightwards\_arrows: | `twisted_rightwards_arrows` | :repeat: | `repeat` |
| :repeat\_one: | `repeat_one` | :arrow\_forward: | `arrow_forward` |
| :fast\_forward: | `fast_forward` | :next\_track\_button: | `next_track_button` |
| :play\_or\_pause\_button: | `play_or_pause_button` | :arrow\_backward: | `arrow_backward` |
| :rewind: | `rewind` | :previous\_track\_button: | `previous_track_button` |
| :arrow\_up\_small: | `arrow_up_small` | :arrow\_double\_up: | `arrow_double_up` |
| :arrow\_down\_small: | `arrow_down_small` | :arrow\_double\_down: | `arrow_double_down` |
| :pause\_button: | `pause_button` | :stop\_button: | `stop_button` |
| :record\_button: | `record_button` | :cinema: | `cinema` |
| :low\_brightness: | `low_brightness` | :high\_brightness: | `high_brightness` |
| :signal\_strength: | `signal_strength` | :vibration\_mode: | `vibration_mode` |
| :mobile\_phone\_off: | `mobile_phone_off` | | |

### Math

| icon | code | icon | code |
| :-: | - | :-: | - |
| :heavy\_multiplication\_x: | `heavy_multiplication_x` | :heavy\_plus\_sign: | `heavy_plus_sign` |
| :heavy\_minus\_sign: | `heavy_minus_sign` | :heavy\_division\_sign: | `heavy_division_sign` |

### Punctuation

| icon | code | icon | code |
| :-: | - | :-: | - |
| :bangbang: | `bangbang` | :interrobang: | `interrobang` |
| :question: | `question` | :grey\_question: | `grey_question` |
| :grey\_exclamation: | `grey_exclamation` | :exclamation: | `exclamation` <br /> `heavy_exclamation_mark` |
| :wavy\_dash: | `wavy_dash` | | |

### Currency

| icon | code | icon | code |
| :-: | - | :-: | - |
| :currency\_exchange: | `currency_exchange` | :heavy\_dollar\_sign: | `heavy_dollar_sign` |

### Keycap

| icon | code | icon | code |
| :-: | - | :-: | - |
| :hash: | `hash` | :asterisk: | `asterisk` |
| :zero: | `zero` | :one: | `one` |
| :two: | `two` | :three: | `three` |
| :four: | `four` | :five: | `five` |
| :six: | `six` | :seven: | `seven` |
| :eight: | `eight` | :nine: | `nine` |
| :keycap\_ten: | `keycap_ten` | | |

### Alphabet

| icon | code | icon | code |
| :-: | - | :-: | - |
| :capital\_abcd: | `capital_abcd` | :abcd: | `abcd` |
| :1234: | `1234` | :symbols: | `symbols` |
| :abc: | `abc` | :a: | `a` |
| :ab: | `ab` | :b: | `b` |
| :cl: | `cl` | :cool: | `cool` |
| :free: | `free` | :information\_source: | `information_source` |
| :id: | `id` | :m: | `m` |
| :new: | `new` | :ng: | `ng` |
| :o2: | `o2` | :ok: | `ok` |
| :parking: | `parking` | :sos: | `sos` |
| :up: | `up` | :vs: | `vs` |
| :koko: | `koko` | :sa: | `sa` |
| :u6708: | `u6708` | :u6709: | `u6709` |
| :u6307: | `u6307` | :ideograph\_advantage: | `ideograph_advantage` |
| :u5272: | `u5272` | :u7121: | `u7121` |
| :u7981: | `u7981` | :accept: | `accept` |
| :u7533: | `u7533` | :u5408: | `u5408` |
| :u7a7a: | `u7a7a` | :congratulations: | `congratulations` |
| :secret: | `secret` | :u55b6: | `u55b6` |
| :u6e80: | `u6e80` | | |

### Geometric

| icon | code | icon | code |
| :-: | - | :-: | - |
| :red\_circle: | `red_circle` | :large\_blue\_circle: | `large_blue_circle` |
| :black\_circle: | `black_circle` | :white\_circle: | `white_circle` |
| :black\_large\_square: | `black_large_square` | :white\_large\_square: | `white_large_square` |
| :black\_medium\_square: | `black_medium_square` | :white\_medium\_square: | `white_medium_square` |
| :black\_medium\_small\_square: | `black_medium_small_square` | :white\_medium\_small\_square: | `white_medium_small_square` |
| :black\_small\_square: | `black_small_square` | :white\_small\_square: | `white_small_square` |
| :large\_orange\_diamond: | `large_orange_diamond` | :large\_blue\_diamond: | `large_blue_diamond` |
| :small\_orange\_diamond: | `small_orange_diamond` | :small\_blue\_diamond: | `small_blue_diamond` |
| :small\_red\_triangle: | `small_red_triangle` | :small\_red\_triangle\_down: | `small_red_triangle_down` |
| :diamond\_shape\_with\_a\_dot\_inside: | `diamond_shape_with_a_dot_inside` | :radio\_button: | `radio_button` |
| :white\_square\_button: | `white_square_button` | :black\_square\_button: | `black_square_button` |

### Other Symbol

| icon | code | icon | code |
| :-: | - | :-: | - |
| :recycle: | `recycle` | :fleur\_de\_lis: | `fleur_de_lis` |
| :trident: | `trident` | :name\_badge: | `name_badge` |
| :beginner: | `beginner` | :o: | `o` |
| :white\_check\_mark: | `white_check_mark` | :ballot\_box\_with\_check: | `ballot_box_with_check` |
| :heavy\_check\_mark: | `heavy_check_mark` | :x: | `x` |
| :negative\_squared\_cross\_mark: | `negative_squared_cross_mark` | :curly\_loop: | `curly_loop` |
| :loop: | `loop` | :part\_alternation\_mark: | `part_alternation_mark` |
| :eight\_spoked\_asterisk: | `eight_spoked_asterisk` | :eight\_pointed\_black\_star: | `eight_pointed_black_star` |
| :sparkle: | `sparkle` | :copyright: | `copyright` |
| :registered: | `registered` | :tm: | `tm` |

## Flags

### Common Flags

| icon | code | icon | code |
| :-: | - | :-: | - |
| :checkered\_flag: | `checkered_flag` | :triangular\_flag\_on\_post: | `triangular_flag_on_post` |
| :crossed\_flags: | `crossed_flags` | :black\_flag: | `black_flag` |
| :white\_flag: | `white_flag` | :rainbow\_flag: | `rainbow_flag` |

### Country and Region Flags

| icon | code | icon | code |
| :-: | - | :-: | - |
| :andorra: | `andorra` | :united\_arab\_emirates: | `united_arab_emirates` |
| :afghanistan: | `afghanistan` | :antigua\_barbuda: | `antigua_barbuda` |
| :anguilla: | `anguilla` | :albania: | `albania` |
| :armenia: | `armenia` | :angola: | `angola` |
| :antarctica: | `antarctica` | :argentina: | `argentina` |
| :american\_samoa: | `american_samoa` | :austria: | `austria` |
| :australia: | `australia` | :aruba: | `aruba` |
| :aland\_islands: | `aland_islands` | :azerbaijan: | `azerbaijan` |
| :bosnia\_herzegovina: | `bosnia_herzegovina` | :barbados: | `barbados` |
| :bangladesh: | `bangladesh` | :belgium: | `belgium` |
| :burkina\_faso: | `burkina_faso` | :bulgaria: | `bulgaria` |
| :bahrain: | `bahrain` | :burundi: | `burundi` |
| :benin: | `benin` | :st\_barthelemy: | `st_barthelemy` |
| :bermuda: | `bermuda` | :brunei: | `brunei` |
| :bolivia: | `bolivia` | :caribbean\_netherlands: | `caribbean_netherlands` |
| :brazil: | `brazil` | :bahamas: | `bahamas` |
| :bhutan: | `bhutan` | :botswana: | `botswana` |
| :belarus: | `belarus` | :belize: | `belize` |
| :canada: | `canada` | :cocos\_islands: | `cocos_islands` |
| :congo\_kinshasa: | `congo_kinshasa` | :central\_african\_republic: | `central_african_republic` |
| :congo\_brazzaville: | `congo_brazzaville` | :switzerland: | `switzerland` |
| :cote\_divoire: | `cote_divoire` | :cook\_islands: | `cook_islands` |
| :chile: | `chile` | :cameroon: | `cameroon` |
| :cn: | `cn` | :colombia: | `colombia` |
| :costa\_rica: | `costa_rica` | :cuba: | `cuba` |
| :cape\_verde: | `cape_verde` | :curacao: | `curacao` |
| :christmas\_island: | `christmas_island` | :cyprus: | `cyprus` |
| :czech\_republic: | `czech_republic` | :de: | `de` |
| :djibouti: | `djibouti` | :denmark: | `denmark` |
| :dominica: | `dominica` | :dominican\_republic: | `dominican_republic` |
| :algeria: | `algeria` | :ecuador: | `ecuador` |
| :estonia: | `estonia` | :egypt: | `egypt` |
| :western\_sahara: | `western_sahara` | :eritrea: | `eritrea` |
| :es: | `es` | :ethiopia: | `ethiopia` |
| :eu: | `eu` <br /> `european_union` | :finland: | `finland` |
| :fiji: | `fiji` | :falkland\_islands: | `falkland_islands` |
| :micronesia: | `micronesia` | :faroe\_islands: | `faroe_islands` |
| :fr: | `fr` | :gabon: | `gabon` |
| :gb: | `gb` <br /> `uk` | :grenada: | `grenada` |
| :georgia: | `georgia` | :french\_guiana: | `french_guiana` |
| :guernsey: | `guernsey` | :ghana: | `ghana` |
| :gibraltar: | `gibraltar` | :greenland: | `greenland` |
| :gambia: | `gambia` | :guinea: | `guinea` |
| :guadeloupe: | `guadeloupe` | :equatorial\_guinea: | `equatorial_guinea` |
| :greece: | `greece` | :south\_georgia\_south\_sandwich\_islands: | `south_georgia_south_sandwich_islands` |
| :guatemala: | `guatemala` | :guam: | `guam` |
| :guinea\_bissau: | `guinea_bissau` | :guyana: | `guyana` |
| :hong\_kong: | `hong_kong` | :honduras: | `honduras` |
| :croatia: | `croatia` | :haiti: | `haiti` |
| :hungary: | `hungary` | :canary\_islands: | `canary_islands` |
| :indonesia: | `indonesia` | :ireland: | `ireland` |
| :israel: | `israel` | :isle\_of\_man: | `isle_of_man` |
| :india: | `india` | :british\_indian\_ocean\_territory: | `british_indian_ocean_territory` |
| :iraq: | `iraq` | :iran: | `iran` |
| :iceland: | `iceland` | :it: | `it` |
| :jersey: | `jersey` | :jamaica: | `jamaica` |
| :jordan: | `jordan` | :jp: | `jp` |
| :kenya: | `kenya` | :kyrgyzstan: | `kyrgyzstan` |
| :cambodia: | `cambodia` | :kiribati: | `kiribati` |
| :comoros: | `comoros` | :st\_kitts\_nevis: | `st_kitts_nevis` |
| :north\_korea: | `north_korea` | :kr: | `kr` |
| :kuwait: | `kuwait` | :cayman\_islands: | `cayman_islands` |
| :kazakhstan: | `kazakhstan` | :laos: | `laos` |
| :lebanon: | `lebanon` | :st\_lucia: | `st_lucia` |
| :liechtenstein: | `liechtenstein` | :sri\_lanka: | `sri_lanka` |
| :liberia: | `liberia` | :lesotho: | `lesotho` |
| :lithuania: | `lithuania` | :luxembourg: | `luxembourg` |
| :latvia: | `latvia` | :libya: | `libya` |
| :morocco: | `morocco` | :monaco: | `monaco` |
| :moldova: | `moldova` | :montenegro: | `montenegro` |
| :madagascar: | `madagascar` | :marshall\_islands: | `marshall_islands` |
| :macedonia: | `macedonia` | :mali: | `mali` |
| :myanmar: | `myanmar` | :mongolia: | `mongolia` |
| :macau: | `macau` | :northern\_mariana\_islands: | `northern_mariana_islands` |
| :martinique: | `martinique` | :mauritania: | `mauritania` |
| :montserrat: | `montserrat` | :malta: | `malta` |
| :mauritius: | `mauritius` | :maldives: | `maldives` |
| :malawi: | `malawi` | :mexico: | `mexico` |
| :malaysia: | `malaysia` | :mozambique: | `mozambique` |
| :namibia: | `namibia` | :new\_caledonia: | `new_caledonia` |
| :niger: | `niger` | :norfolk\_island: | `norfolk_island` |
| :nigeria: | `nigeria` | :nicaragua: | `nicaragua` |
| :netherlands: | `netherlands` | :norway: | `norway` |
| :nepal: | `nepal` | :nauru: | `nauru` |
| :niue: | `niue` | :new\_zealand: | `new_zealand` |
| :oman: | `oman` | :panama: | `panama` |
| :peru: | `peru` | :french\_polynesia: | `french_polynesia` |
| :papua\_new\_guinea: | `papua_new_guinea` | :philippines: | `philippines` |
| :pakistan: | `pakistan` | :poland: | `poland` |
| :st\_pierre\_miquelon: | `st_pierre_miquelon` | :pitcairn\_islands: | `pitcairn_islands` |
| :puerto\_rico: | `puerto_rico` | :palestinian\_territories: | `palestinian_territories` |
| :portugal: | `portugal` | :palau: | `palau` |
| :paraguay: | `paraguay` | :qatar: | `qatar` |
| :reunion: | `reunion` | :romania: | `romania` |
| :serbia: | `serbia` | :ru: | `ru` |
| :rwanda: | `rwanda` | :saudi\_arabia: | `saudi_arabia` |
| :solomon\_islands: | `solomon_islands` | :seychelles: | `seychelles` |
| :sudan: | `sudan` | :sweden: | `sweden` |
| :singapore: | `singapore` | :st\_helena: | `st_helena` |
| :slovenia: | `slovenia` | :slovakia: | `slovakia` |
| :sierra\_leone: | `sierra_leone` | :san\_marino: | `san_marino` |
| :senegal: | `senegal` | :somalia: | `somalia` |
| :suriname: | `suriname` | :south\_sudan: | `south_sudan` |
| :sao\_tome\_principe: | `sao_tome_principe` | :el\_salvador: | `el_salvador` |
| :sint\_maarten: | `sint_maarten` | :syria: | `syria` |
| :swaziland: | `swaziland` | :turks\_caicos\_islands: | `turks_caicos_islands` |
| :chad: | `chad` | :french\_southern\_territories: | `french_southern_territories` |
| :togo: | `togo` | :thailand: | `thailand` |
| :tajikistan: | `tajikistan` | :tokelau: | `tokelau` |
| :timor\_leste: | `timor_leste` | :turkmenistan: | `turkmenistan` |
| :tunisia: | `tunisia` | :tonga: | `tonga` |
| :tr: | `tr` | :trinidad\_tobago: | `trinidad_tobago` |
| :tuvalu: | `tuvalu` | :taiwan: | `taiwan` |
| :tanzania: | `tanzania` | :ukraine: | `ukraine` |
| :uganda: | `uganda` | :us: | `us` |
| :uruguay: | `uruguay` | :uzbekistan: | `uzbekistan` |
| :vatican\_city: | `vatican_city` | :st\_vincent\_grenadines: | `st_vincent_grenadines` |
| :venezuela: | `venezuela` | :british\_virgin\_islands: | `british_virgin_islands` |
| :us\_virgin\_islands: | `us_virgin_islands` | :vietnam: | `vietnam` |
| :vanuatu: | `vanuatu` | :wallis\_futuna: | `wallis_futuna` |
| :samoa: | `samoa` | :kosovo: | `kosovo` |
| :yemen: | `yemen` | :mayotte: | `mayotte` |
| :south\_africa: | `south_africa` | :zambia: | `zambia` |
| :zimbabwe: | `zimbabwe` | | |
