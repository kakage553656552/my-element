## Changelog

### 2.15.11

*2022-11-15*

#### Bug fixes
- Docs
  - Fix Radio docs (#22178 by @bchen1029) 
  - Fix Progress docs
#### Optimization
- I18n
  - Update translation of Malaysian (#22185 by @z4q)
  - Update translation of Norwegian (#22145 by @Barsnes)
- Progress
  - Add defineBackColor and textColor prop (#22089 by @lm312)
- Statistics
  - Add new component Statistics (#22159 by @webvs2)
- Other
  - Add Web Types to improve code assistance in WebStorm IDE and other JetBrains IDEs (#22135 by @piotrtomiak)

### 2.15.10

*2022-09-13*

#### Bug fixes

- DatePicker
  - Fix props placement error (#21908 by @lqzhgood)
- Loading
  - Fix sticky DOM error (#22087 by @zzjjhh001)
- Docs
  - Fix Popover docs (#22083 by @lm312)
  - Fix Skeleton docs (#22092 by @lm312)
  - Fix DatePicker docs (#21970 by @guojiongwei)
- Tree: 
  - fix lazy-load default check problem (#21934 by @kiss-yu)

#### Optimization

- I18n
  - Add translation of Sinhalese (#21936 by @sayuri-gi)
  - Update translation of Spanish (#21924 by @jcardus)
  - Add translation of Malaysian (#22028 by @iorange0411)
  - Update translation of Swahili (#21904 by @Cholowao)
- Utils
  - update date-util.js (#22099 by @Due07)  
- DatePicker
  - add months And years type (#21918 by @akiko123456)

### 2.15.9

*2022-06-02*

#### Bug fixes

- Table
  - Fix Tabl-header shake bug (#21863 by @bofeng)
  - Fix when partial import  show `el-checkbox not imported` error (#21828 by @bobohuochai)
- FormItem
  - Fix  change rules  verification not reset bug (#21892 by @bofeng)
- Cascader
  - Fix change options unexpect error (#21759 by @louiebb)
- Docs
  - Fix Popover docs (#21843 by @lod61)
  - Fix Calendar docs (#21814 by @GoJam11)
  - Fix TimePicker docs (#21803 by @Alanscut)
  - Fix DatePicker docs (#21877 by @Nirvanaiu)
- Other
  - Fix codepen display bug (#21863 by @bofeng)

#### Optimization

- I18n
  - Add translation of Swahili (#21895 by @quilltouch)
- Chore
  - Use launch-editor-middleware in dev environment (#21633 by @polemices)
- DatePicker & Cascader
  - Optimize the dropdown animation direction (#21806 by @XivLaw)
- Tooltip
  - Optimize `getFirstElement` code (#21886 by @zhankang)
- Input
  - Optimize scss code (#21558 by @cheese-git)

### 2.15.8

*2022-04-12*

#### Bug fixes

- Drawer
  - Fix appendToBody failure problem (#21264 by @cs1707)
- Switch
  - Fix toggling value problem(#19473 by @EdwinBetanc0urt)
- Docs
  - Fix input docs (#21723 by @justforuse)
  - Fix DatePicker docs (#21663 by @justforuse)
  - Fix Skeleton docs (#21601 by @yanwydxf)
- Others
  - Fix vue version (#21736 by @ckvv)

#### Optimization

- I18n
  - add translation of Azerbaijani (#21012 by @ricardotondello)
  - update translation of Slovenian (#21729 by @patik123)
  - update translation of Slovak (#21711 by @sjaustirni )
  - add translation of Icelandic (#21709 by @aronhr)
  - add translation of Bengali (#21485 by @llwwtt)

#### Others

- Due to compatibility considerations, the PR on node-sass (#21019 by @linxsbox) of 2.15.7 release has been withdrawn and will be published in an appropriate version after re-evaluation.

### 2.15.7

*2021-11-18*

#### Bug fixes

- Select
  - fix click icon triggering dropdown (#21314 by @dennyak47)
  - fix keydown event when composition (#21336 by @bchen1029)
- Badge
  - fix type class when is-dot (#21308 by @adaex)
- Form
  - validate method reject error info (#21374 by @cs1707)
- Table
  - fix resizeObserver loop limit exceeded (#21255 by @tomieric)
  - fix toggleAllSelection bug when table is empty (#21456 by @cs1707)
  - optimize performance (#21330 by @cs1707)
- Button
  - fix disabled priority (#21375 by @cs1707)
- Descriptions
  - fix label slot bug (#21462 by @cs1707)
- SASS
  - replace node-sass with dart-sass (#21019 by @linxsbox)
- Docs
  - fix skeleton typos (#21408 by @zhhbstudio)

### 2.15.6

*2021-09-02*

#### Bug fixes

- Cascader
  - fix a bug that makes the browser jitter in zoom mode (#21207 by @cs1707)
  - optimize performance (#21231 by @cs1707)
- Select
  - fix long text overflow in multiple mode (#21237 by @cs1707)
- Dropdown
  - add disabled property (#21235 by @mshioda)
- Radio
  - fix checked state when browser go back (#21250 by @cs1707)
- Descriptions
  - fix type declaration (#21265 by @adaex)
  - avoid table style conflict (#21254 by @adaex)
- Drawer
  - fix append to body (#21264 by @cs1707)
- Local
  - fix italian mistake (#21012 by @ricardotondello)

### 2.15.5

*2021-08-04*

#### Bug fixes

- Select
  - fix resetInputHeight (#21201 by @cs1707)

### 2.15.4

*2021-08-03*

#### New features

- Descriptions 
  - add description component (#21129 by @cs1707)
- Result 
  - add result component (#21171 by @cs1707)

#### Bug fixes

- Utils 
  - fix isScroll (#21098 by @canvascat)
- Translation 
  - update it.js (#21133 by @bliberi)
- RadioGroup 
  - fix RadioGroup used in component causes exception #17908 (#20783 by @lceric)
- Message 
  - fix message[type] (#21088 by @cs1707)
- Carousel 
  - reset the timer when setActiveItem method is called (#20846 by @Nekojita1)
- Cascader 
  - fix emitPath (#21185 by @cs1707)
- Select 
  - fix select filterable bug (#17494 by @profore)
  - fix a bug that makes the browser jitter in zoom mode (#21197 by @cs1707)
- Tree 
  - fix insertChild (#21194 by @cs1707)

### 2.15.3

*2021-06-29*

#### New features

- Skeleton
  - add skeleton component (#21038 by @cs1707)
- Empty
  - add empty component (#21080 by @cs1707)

#### Bug fixes

- Local
  - fix week translations for hr locale (#21040 by @cs1707)
- Table
  - fix lazy load data (#21041 by @cs1707)
- Docs
  - fix form hide-required-asterisk description (#21045 by @cs1707)
- Drawer:
  - fix destroy (#20715 by @zj9495)
- Row
  - fix align top (#20963 by @cs1707)
- Select
  - fix the bug when the value is Boolean (#21052 by @cs1707)
- Calendar
  - fix first-day-of-week (#21057 by @cs1707)
- Utils
  - fix isScroll (#21065 by @cs1707)
  - fix(utils.dom by @fw6)
- TypeScript
  - add CascaderPanel export type (#21070 by @qige2016)
  - add spinner.d.ts (#21090 by @qige2016)
  
### 2.15.2

*2021-05-28*

#### Bug fixes

- Image
  - fix z-index and keydown event add stopPropagation (#20859 by @cs1707)
- Input
  - fix show password cursor (#20870 by @cs1707)
  - fix show password icon in edge (#20902 by @cs1707)
- Carousel
  - fix interval and scale bug (#20931 by @cs1707)
- Cascader
  - fix delete tag bug (#20939 by @cs1707)
- Drawer
  - add overflow auto (#20948 by @cs1707)
- Others
  - fix isFunction (#20912 by @cs1707)

### 2.15.1

*2021-02-23*

#### Bug fixes

- Drawer
  - bugfix (by @cs1707)
- Image
  - fix incorrect image object fit ratio in IE (#19583 by @charlie0228)
- Cascader
  - fix cascader panel active path (#20730 by @cs1707)
- Calendar 
  - fix calendar component i18n bug (#20758 by @iamkun)
- ColorPicker
  - fix bugs (by @UxieVerity)

#### Optimization

- Doc
  - update Axure resource v2.1.0 (by @iamkun)

### 2.15.0

*2021-01-15*

#### Bug fixes

- Select
  - Fix placeholder i18n bug (#17644 by @nzh63)
- Popconfirm
  - Popconfirm i18n bug by @iamkun
- Drawer
  - Fix focus bug (#20626 by @cs1707)
- Image
  - Preview optimization (#20652 by @cs1707)

#### Optimization

- Doc
  - Fix typo in french translation of datetime-picker.md (#20543 by @lonk)
  - Add format attribute description to the progress component (#20641 by @cs1707)

### 2.14.1

*2020-11-11*

#### Bug fixes

- Popover
  - Compatible with Vue 2.6 new v-slot syntax (#20424 by @iamkun)

#### Optimization

- I18n
  - Update Arabic translation (#20202 by @elkattan)
  - Update Uighur translation (#20177 by @IlhamTahir)

### 2.14.0

*2020-10-29*

#### Breaking changes

- Popconfirm
  - Rename event name to `confirm`, `cancel` (#20240 by @hugiron)

#### Bug fixes

- Progress
  - Fix attribute error (#19985 by @Caaalabash)

#### Optimization

- I18n
  - Update Russian translation (#19451 by @yangirov)
  - Update Khmer translation (#20077 by @Sovai)
  - Update Ukrainian translation (#20344 by @MammutAlex)

### 2.13.2

*2020-05-18*

#### Bug fixes

- Autocomplete
  - Fix change event bug (#19200 by @sxzz)
- Image
  - Update error status (#19194 by @lhx6538665)

#### Optimization

- I18n
  - Update ru-RU popconfirm translation (#19220 by @Opppex)
  - Update vi translation (#19244 by @quangln2810)
  - Update Catalan and Spanish translations (#19296 by @Ismaaa)
  - Update Indonesia translation (#19320) by @therour)
  - Update Brazilian Portuguese translation (#19374 by @diegomengarda)


### 2.13.1

*2020-04-13*

#### New features
- Autocomplete
  - Add change event (#17913 by @sxzz)

#### Bug fixes

- Autocomplete
  - Fix suggestion error when textarea (#18478 by @Roojay)
- Carousel
  - Fix console typo bug (#18264 by @IceFox)
- Image
  - Fix preview dose not show when preview list not contain src issue (#18975) (#19130 by @luckyCao)
  - Fix shortcut key not work at second time issue (#18983) (#19156 by @luckyCao)
  - Don't show image-viewer when preview is false (#18967 by @inooNgt)
- Transfer
  - Fix incorrect line-height of el-transfer's first list item when it was used with  el-form-item (#18917 by @Hanx)
- InputNumber
  - Correctly compute inputNumberDisabled (#18439 by @ashuser-pendo)
- Chore
  - Remove index intro (#19155 by @iamkun)
- Doc
  - Popconfirm doc update (#18324 by @iamkun)
  - Fix step-strictly docs typo (#18705 by @dream2023)
  - Fix a type error in document of steps component (#17555 by @haoranyu)

### 2.13.0

*2019-11-26*

#### New features

- Popconfirm
  - Add popconfirm component (#17548 by @iamkun)

#### Bug fixes

- BackTop
  - Use cubic bezier scrolling (by @lon)
- DatePicker
  - Fix bug of only select min date of date range problem (#17191 by @smk0621)
- Select
  - Fix select test cases (by @msidolphin)
- Tree
  - Add font-size for the style of tree empty-text (#17094 by @spengjie)
- Table
  - Column header can be costumed (#17291 by @ziyoung)
  - Update table header cell style (#17284 by @ziyoung)
  - Fix table header height after filter (#17348 by @ziyoung)
  - Fixed row-style with display not work (#17002 by @a631807682)
  - Fix header table not display (#17341 by @ziyoung)
- Calendar
  - Import el-button and el-button-group (#17376 by @masongzhi)
- MessageBox
  - Fix icon position error (#17410 by @nullptru)
- TimePicker
  - Set the selection range after scrolling up or down (#16868 by @mattheyan)
- Message
  - Fix close instace offsetHeight???#17564??? (#17852 by @gzwgq222)
- Form
  - Callback of validateField should be optional (#17314 by @CarterLi)
- Cascader
  - Fix TypeScript 3.7 compatibility (#17881 by @CarterLi)
- Menu
  - Fix router NavigationDuplicated error when using vue-router@^3.1.0 (#17269 by @iamkun)
- Dropdown
  - Update type file (#17550 by @iamkun)
- Progress
  - Add strokeLinecap prop (#17552 by @iamkun)
- InfiniteScroll
  - Skip trigger event on invisible element (#17553 by @iamkun)
- Image
  - Perfect picture preview behavior (#16985 by @luckyCao)
  - Fix shield the page when preview big image (#16796 by @luckyCao)
- Drawer 
  - Bugfix drawer-append-to-body-not-working (#16953 by @JeremyWuuuuu)
- Select
  - Fix tag show value or empty issue (17199 by @luckyCao)
- Scrollbar
  - Fix FireFox scroll bar width (#18091 by @iamkun)
  
#### Optimization

- I18n
  - Update sv-SE.js (#17926 by @FOLLGAD)
  - Update avatar component fr doc (#17762 by @blombard)
- Docs
  - Fix time-select typo (#17250 by @wacky6)
  - Fix Drawer attribute accepted value typo in es (#17122 by @haoranyu)
  - Update Spanish changelog 2.12.0 (#17364 by @Gonzalo2310)
  - Fix Changelog typo (#17874 by @renlixin)
  - Fix Loading demo (#17862 by @MBearo)
  - Add input event in input Events Table (#18061 by @zhouxinyong)
  - Delete Input repeat change event (#18085 by @zhouxinyong)

### 2.12.0

*2019-08-29*

#### New features

- Popover
  - Add close-delay prop (#16671 by @LachlanStuart)
- Theme
  - Add Chrome Extension: Element Theme Extension (#16686 by @iamkun)
- Icon
  - Add font-display to @font-face declaration (#16805 by @iamfaizalandyka)

#### Bug fixes

- Carousel
  - Fix onChange emit value (#16705 by @iamkun)
- Notification
  - Fix modifying incoming option object (#16704 by @iamkun)
- DatePicker
  - Add className for picker option (#16632 by @iamkun)
- DateTimePicker
  - Fix time-spinner not scroll to right position (#16854 by @jesse-li)
- Table
  - Prevent click handler after drag (#16850 by @ziyoung)
  - Fix chrome crash when set thead css display to none (#16956 by @luckyCao)
  - Fix wrong empty block height (#16861 by @ziyoung)
  - Not throw error when calling toggleExpansion (#16304 by @yyjjqq94)
  - Not trigger sort-change event when mounted (#17113 by @a631807682)
  - Fix setCurrentRow unable to clear highlight row (#16879 by @ziyoung)
  - Fix expand-row-keys not work when data is loaded asynchronously (#16899 by @ziyoung)
  - set toggleAllSelection as instance property (#17137 by @ziyoung)
- Tree
  - Fix distance between label and checkbox (#16799 by @Hazlank)
- Tabs
  - Fix incorrect TabItem's position (#16520 by @victorting)
  - Fix activated tab is out of visual range bug (#17033 by @nullptru)
- Calendar
  - Fix weekdays i18n issue (#16772 by @ubitoffee)
  - fix locale error by (#17208 by @iamkun)
- Cascader
  - Fix CascaderPanel display error (#16716 by @zhangHongEn)
  - Fix disable status and close button issue (#16224 by @yyjjqq94)
- Input
  - Fix Korean composition event (#15069 by @MoonHyuk)
  - Fix click event of clear button not trigger when using v-loading (#16576 by @a631807682)
- Select
  - Not toggle dropdown when filtering (#17205 by @luckyCao)
- Transfer
  - Fix style error  (#17206 by @iamkun)
- Dialog
  - update sass var (#16365 by @haoranyu)
- RadioGroup
  - Not produce invalid HTML in table if "is" attribute is specify (#17070 by @nullptru)
- Divider
  - Support custom classes (#17078 by @island205)

#### Optimization

- Checkbox
  - Improve screen reader experience (#16575 by @tylertrotter)
- Docs
  - Update changelog (#16773 by @SimonaliaChen)
  - Update contributing guide (#14800 by @sinchang)
  - Fix typo in Drawer docs (#16848 by @winkay)
  - Update custom theme (#16983 by @iamkun)
  - Add Esperanto translation (#16955 by @maxkoryukov)
  - Update input-number document about change event (#16316 by @luckyCao)
  - Update spanish doc 2.11.1 (#16961 by @Gonzalo2310)
- I18n
  - Remove translation of 'year' in catalan language as in the other languages (#14722 by @oscaralbareda)
  - Update spanish changelog 2.10.0 and 2.10.1 (#16548 by @Gonzalo2310)
  - Update ar.js (#16653 by @l3op)
- Test
  - Correct spelling error (#16672 by @boomler)
  - Refactor unit test to use data-uri (#16847 by @a631807682)
- Types
  - Fix httprequest type (#16633 by @luckyCao)

### 2.11.1

*2019-07-26*

#### Bug fixes

- Image
  - Fix Image component SSR compatibility (#16737 by @luckyCao)
- Chore
  - Update dart-sass compatibility (#16744 by @LewisChennnnn)

### 2.11.0

*2019-07-25*

#### New features

- Drawer
  - Add drawer component (#16577 by @JeremyWuuuuu)

#### Bug fixes

- Checkbox
  - Enhance css selector (#16006 by @Hazlank)
- Tree
  - Make el-tree generic (#15934 by @JeremyWuuuuu)
  - Set isCurrent prop to False (#15870 by @kkkisme)
- Dropdown
  - Fix split-button caret default color (#15931 by @JuniorTour)
- Cascader
  - Fix level 1 children is empty update problem (#16399 by @luckyCao)
  - Add sets default values when lazy is true (#16420 by @luckyCao)
  - Fix display errors when node value is duplicate (#15935 by @junyiz)
  - Expose getCheckedNodes and fix options change bug (#16709 by @SimonaliaChen)
- Calendar
  - Display correct header when range is specified (#16354 by @ziyoung)
- Submenu
  - Fix prop append-to-body (#16289 by @a631807682)
- Table 
  - Fix tree table when updating data (#16481 by @island205)
- Select
  - Fix memory leak issue (#16463 by @island205)
- InfiniteScroll
  - Update naming & doc (#16698 by @iamkun)
- Avatar
  - Fix image not center vertically issue (#16489 by @luckyCao)
- Dialog
  - Add destroyOnClose attribute (#16455 by @ziyoung)
- Image
  - Add big Image preview feature (#16333 by @luckyCao)

#### Optimization

- Docs
  - Fix dropdown demo (#16193 by @webxmsj)
  - Fix typo in table documents (#15971 by @howiefh)
- I18n
  - Update translation of Thai language (#16689 by @ponkrit)
- Chore
  - Update theme base api (#16607 by @iamkun)
  - Add form theme token (#16699 by @iamkun)
  - Mark ali inner user's access (#16609 by @iamkun)
  - Fix doc anchor bug (#16692 by @iamkun)

### 2.10.1

*2019-07-02*

#### Bug fixes

- Table
  - Fix sort icon (#15439 by @bezany)
  - Fix layout breaks when append slot exists (#16332 by @ziyoung)
  - Fix showOverflowTooltip not reactive (#16295 by @a631807682)
  - Register scrollbar in filter-panel (#16246 by @ziyoung)
- Chore
  - Fix 2.9 docs (#16233 by @ziyoung)
  - Fix index page theme intro english css style issue (#16254 by @iamkun)

#### Optimization

- Tag
  - Compatible with IE (#16334 by @ziyoung)
- Chore
  - Update Dingtalk Group QR image (#16236 by @iamkun)
- Doc
  - Update online theme roller doc (#16244 by @iamkun)

### 2.10.0

*2019-06-25*

#### New features

- I18n
  - Added Uzbek language (#15796 by @ogabek96)
- Calendar
  - Add first-day-of-week attribute (#16047 by @ziyoung)
- Avatar
  - Add avatar component (#16144 by @luckyCao)
- Upload:
  - Add capability to customize thumbnail template (#13192 by @victorzhuk)

#### Bug fixes

- Tree
  - Not highlight tree node when currentKey is null (#15668 by @yyjjqq94)
  - Fix issue #15538 caused by two Tree sharing the same data. (#15615 by @VanMess)
- Upload
  - Update the parameter `fileList` type (#15716 by @underfin)
- Table
  - Fix loading icon not display (#15868 by @ziyoung)
  - Fix background color of complex table when hovering (#15504 by @cnlon)
  - Fix current-row-key and select event bug (#15983 by @ziyoung)
  - Height accepts more units (#16013 by @ziyoung)
  - Fix reserve-selection not work (#16135 by @ziyoung)
- Docs
  - Fix Divider attribute type in zh-cn (#15889 by @haoranyu)
- Menu
  - Fixed submenu hidden bug after adding popper-append-to-body (#15391 by @PanJiaChen)
- Select
  - Fix initialInputHeight (#15989 by @yyjjqq94)
  - Fix default-first-option behavior when typing Chinese (#15431 by @VanMess)
  - fix double import problem (#16215 by @lengband)
- Message
  - Add type def for offset option (#16027 by @matjaz)
- Timeline
  - Fix reverse broken (#16091 by @ziyoung)
- Slider
  - Fix #15545 by adding explains about "input" event in Chinese (#15588 by @VanMess)
- InfiniteScroll
  - Update package name (#16125 by @iamkun)
- MessageBox
  - Fix?? distinguishCancelAndClose action not same as docs bug (#15438 by @qingdengyue)
- PopupManager
  - Fix z-index cannot be rewritten at first using (#15738 by @luckyCao)
- Docs
  - Delete an incorrect closing html tag and empty block code (#16194 by @Alexeykhr)
- Chore
  - Update test api host (#15807 by @iamkun)

#### Optimization

- Tree
  - Modify loop conditions to improve performance (#15699 by @KingJeason)
- Theme
  - Refine GA track & Update footer link forward to online theme roller (#16007 by @island205)
- Badge
  - Update badge prop check (#16198 by @iamkun)
- Avatar
  - Update theme config var (#16202 by @luckyCao)
- I18n
  - Update pt-br.js (#15776 by @gigioSouza)
  - Update Farsi translation (#15881 by @pamenary)
- Docs
  - Add missing components in quickstart (#16063 by @pape2016)
  - Update french translation (#16208 by @blombard)
  - Add description $slots.default (#15444 by @Alexeykhr)
  - Update Spanish Doc 2.9.1 (#15840 by @Gonzalo2310)
  - Fix spelling mistakes in fr (#15837 by @blombard)
  - Update changelog 2.9.2 Spanish (#16185 by @Gonzalo2310)

#### Breaking changes

- Form
  - Remove success status (#16159 by @ziyoung)

### 2.9.2

*2019-06-21*

#### Correction de bugs

- Chore
  - Correction du fichier de d??finitions TS (#15805 by @NateScarlet)

### 2.9.1

*2019-05-30*

#### Nouvelles fonctionnalit??s

- Table
  - les ??v??nements tree-props???default-expand-all, expand-row-keys, toggle-row-expansion method and expand-change sont pris en charge dans Tree Table (#15709 by @ziyoung)

#### Correction de bugs

- Table
  - Correction de quelques bugs (#15709 by @ziyoung)
- Theme
  - Mise ?? jour de l'h??te api (#15784 by @iamkun)

#### Optimisation

- Chore
  - Mise ?? jour de InfiniteScroll type (#15794 by @iamkun)

### 2.9.0

*2019-05-30*

#### Nouvelles fonctionnalit??s

- Backtop
  - Ajout du composant Backtop (#15541 by @iamkun)
- PageHeader
  - Ajout du composant PageHeader (#15714 by @ziyoung)
- InfiniteScroll
  - Ajout de la directive InfiniteScroll (#15567 by @iamkun)
- Cascader
  - Ajouter plusieurs mode et filter-method (#15611 by @SimonaliaChen)
- Message
  - Affichage en mode pile (#15639 by @island205)
- Tag
  - Ajout d'un effet de prop (#15725 by @SimonaliaChen)
- Tabs
  - Aligner le titre ?? gauche lorsque le type est carte (#15695 by @luckyCao)
- DatePicker
  - Supporte les cha??nes de caract??res litt??rales (#15525 by island205)
- Image
  - Ajout du support pour les attributs de transmission et listeners (#15578 by @VanMess)
- Theme
  - Ajout d'un popup en arri??re plan (#15412 by @iamkun)
- Chore
  - Mise ?? jour de la nouvelle page d'index 2.9.0 (#15682 by @iamkun)

#### Correction de bugs

- Table
  - Correction du comportement de sort-change lorsque la condition de tri est nulle (#15012 by @joelxr)
- Image
  - Correction de la compatibilit?? ssr et object-fit (#15346 by @SimonaliaChen)
- Input
  - Correction du style de show-word-count dans el-form (#15359 by @lvjiaxuan)
  - Correction de l'ic??ne d'erreur pas centr??e (#15354 by @YiiGuxing)
- Calendar
  - Correction du mauvais jour de la semaine quand le jour est dimanche (#15399 by @qingdengyue)
  - Correction du bug de disparition d'octobre (#15394 by @qingdengyue)
- Tabs
  - Correction de l'onglet de base imbriqu?? dans l'erreur de remplissage de card (#15461 by @SimonaliaChen)
- Tag
  - Correction du probl??me de propagation d'arr??t (#15150 by @infjer)
- Form
  - Correction de input-group dans l'erreur de hauteur de form-item (#15457 by @SimonaliaChen)
  - R??solution de l'issue de resetFields (15181 by @luckyCao)
- Tooltip
  - Correction de tabindex personnalis?? ne fonctionnant pas (#15619 by @SimonaliaChen )
- Link
  - Correction de la classe de style d'ic??ne (#15752 by @iamkun)
- Select
  - Revert d??finit la valeur ?? null une fois effac??e (#15447 by @iamkun)
- Loading
  - R??solution du probl??me de mise ?? jour de dom lorsque l'??tat de chargement change rapidement (#15123 by @FAKER-A)
- Switch
  - Label avec les ??v??nements r??currents el-switch (#15178 by @FAKER-A)
- Slider
  - Correction d'un probl??me de style lorsque la barre de d??filement est cliqu??e (#15561 by @luckyCao)
- Radio
  - R??solution de l'issue 14808 (#14809 by @OverTree)
- Form
  - R??solution du probl??me de resetFields (15181 by @luckyCao)
- Chore
  - Mise ?? jour des d??pendances et corrige le bug de d??monstration (#15324 by ziyoung)
- Type
  - Correction du type de chargement (#15635 by @iamkun)
  - Correction du type d'ic??ne (#15634 by @iamkun)
  - Fixe la d??finition du type de lien (#15402 by @iamkun)

#### Optimisation

- Cascader
  - Refactor (#15611 by @SimonaliaChen)
- Chore
  - Mise ?? jour de la logique du nouveau composant (by @iamkun)
- Docs
  - Renommage de variables dans la documentation (#15185 by @liupl)
  - Correction du type d'attribut d'image et de la valeur par d??faut (#15423 by @haoranyu)
  - Correction d'un bug de formulaire (#15228 by @SHERlocked93)

### 2.8.2

*2019-04-25*

#### Corrections de bugs

- Icon
  - Mise ?? jour (#15272 par @iamkun)
- Docs
  - Correction du style de Form et Input (#15273 par @ziyoung)

### 2.8.1

*2019-04-25*

#### Corrections de bugs

- Icon
  - Mise ?? jour de l'ic??ne du cascadeur et du select (#15264 par @SimonaliaChen)
  - Mise ?? jour (#15258 #15268 par @iamkun)

#### Optimisation

- Chore
  - Mise ?? jour du script de build (#15267 par @ziyoung)
- Docs
  - Correction de la couleur de souslignage d'un lien (#15265 par @iamkun)
- Autre
  - Correction d'une configuration de migration non compatible avec les propri??t??s et ??v??nements en camelCase (#15260 par @SimonaliaChen)

### 2.8.0

*2019-04-25*

#### Nouvelles fonctionnalit??s

- Divider
  - Ajout du composant divider (#15055 par @island205)
- Rate
  - Ajout des couleurs et des classes d'ic??nes personnalis??es en passant un objet (#15051 par @SimonaliaChen)
- Link
  - Ajout du composant Link (#15052 par @iamkun)
- Calendar
  - Ajout du composant calendar (#14908 by @ziyoung)
- Icon
  - Ajout d'une ic??ne (#15214 par @iamkun)
- Alert
  - Ajout d'un th??me sombre (#15041 par @island205)
- Image
  - Ajout du composant image (#15117 par @SimonaliaChen)
- Collapse
  - CollapseItem peut ??tre d??sactiv?? (#15076 par @ziyoung)
- Carousel
  - Ajout d'un attribut de direction et support de la direction verticale (#15122 by @ziyoung)
- Pagination
  - Ajout d'un attribut cach?? sur une seule page (#15096 par @ziyoung)
- Slider
  - Ajout des marqueurs (#15133 par @luckyCao)
- Input
  - Ajout de l'attribut show-word-count (#15075 par @luckyCao)
- InputNumber
  - Ajout de l'attribut step-strictly (#15050 par @luckyCao)
- Tooltip, Dropdown, Popover
  - Support de l'attribut tabindex (#15167 by @ziyoung)

#### Corrections de bugs

- Notification
  - Correction du word-break du titre (#15008 par @iamkun)
- Form
  - Correction d'une erreur dans les r??gles de validation (#14985 par @luckyCao)
  - Correction du style du label (#14969 par @ziyoung)
  - Les FormItem requis affiche un ast??risque lorsque le label est auto (#15144 by @ziyoung)
- Pagination
  - Fix du slot non mis ?? jour (#14711 par @lucyhao)
- Table
  - Correction d'un bug de chargement en mode lazy (#15101 by @ziyoung)
  - Correction de la largeur des cellules lorsque colspan est sup??rieur ?? 1 (#15196 by @ziyoung)
  - Am??lioration des performances (#14868 by @ziyoung)
  - Ne pas ??mettre de d??clencheurs de changement de tri pendant l'initialisation (#14625 by @PeanutWatson)
  - Comportement ??gal pour height et max-height (#14660 by @arthurdenner)
- Dialog
  - Correction de la casse des longs mots (#15027 par @iamkun)
- Alert
  - Mise ?? jour (#15186 par @ziyoung)
- Tabs
  - Correction d'un probl??me o?? le rejet d'une promesse touchait l'application (#14816 par @ffxsam)
  - Rerendu lors d'un changement de slots (#1523238 by @ziyoung)
- Message
  - Mise ?? jour (#14968 par @agoni121212)
- Select
  - Correction d'une erreur lorsque la valeur est ind??finie ou nulle (#15022 par @luckyCao)
- Tree
  - D??truire le noeud courant apr??s sa suppression (#14604 par @sinchang)
  - Am??lioration des performances (#14881 par @ChenZhuoSteve)
- Dropdown
  - Correction de style (#14907 par @doing123)
- Slider
  - Correction d'un bug clavier a11y cass?? (#14792 by @erezsob)
- Menu
  - La valeur ActiveIndex sera nulle si defaultIndex n'existe pas (#14074 par @hoythan)
- Directive
  - RepeatClick : utilisation de Date.now() au lieu de Date() (#14776 par @pavelmash)
- Upload
  - Correction du style d'affichage des images transparentes (#15039 par @iamkun)
- Th??me
  - Ajout d'une bordure (#1525256 par @iamkun)

#### Optimisation

- Chore
  - Mise ?? jour du changelog zh-cn (#14965 par @iamkun)
  - Masquer la description de la d??mo quand elle est vide (#15014 par @ziyoung)
  - Afficher les informations du serveur de d??veloppement par d??faut par @iamkun)
  - Correction d'une erreur de changelog 2.6.0 (#15026 par @iamkun)
  - Mise ?? jour de la configuration de compilation (#14821 par @abc3660170)
  - Ajout d'hmr (#15221 par @SimonaliaChen)
  - Utilisation de sourcemap dans l'environnement dev (#15087 par @ibufu)
Docs
  - Renommage de la variable dans docs (#14602 #15003 #15094 #15105 par @liupl)
  - Correction d'une erreur de t??l??chargement de doc (#15023 par @iamkun)
  - Mise ?? jour du validateur de formulaire personnalis?? doc (#15040 par @iamkun)
  - Mise ?? jour des onglets docs pour afficher les onglets verticaux (#15053 par @iamkun)
  - Utiliser eleme.cn comme domaine (#15139 par @ziyoung)
  - Correction du nom de route Image (#15194 par @iamkun)
  - Suppression de la traduction en double (#15207 par @iamkun)

#### Breaking changes

- Rate
  - Correction du support de l'affichage d??cimal en mode d??sactiv?? (#15089 par @haoranyu)
- Select
  - Utiliser le label de l'option pour r??gler le placeholder en mode filtre (#14989 par @ibufu)

### 2.7.2

*2019-04-03*

#### Corrections de bugs

- Form
  - Correction du style de `label-width` auto (#14955 par @ziyoung)

#### Optimisation
- Docs
  - Correction d'une erreur de lien img (#14957 par @iamkun)
- Chore
  - Correction d'une erreur de d??ploiement mkdir (#14952 par @iamkun)

### 2.7.1

*2019-04-03*

#### Corrections de bugs

- Select
  - D??finir la valeur ?? null lorsqu'elle est effac??e (#14322 par @aaronfulkerson)
- Input
  - Mise ?? jour des valeurs d??pendantes du DOM lors d'un changement de type (#14889 par @wacky6)
- Table
  - Faire fonctionner `defaultExpandAll' lorsqu'une colonne ??tendue existe (#14935 par @ziyoung)
- Dialog
  - Couleur d'arri??re-plan configurable (#14939 par @ziyoung)
- Form
  - `label-width` supporte la largeur automatique (#14944 by @ziyoung)

#### Optimisation
- Docs
  - Mise ?? jour de la documentation en espagnol (#14913 par @Gonzalo2310)
  - Ajout d'un document en fran??ais pour le nouveau composant (#14924 by @ziyoung)
  - Optimiser la documentation des onglets (#14938 by @ziyoung)

### 2.7.0

*2019-03-28*

#### Nouvelles fonctionnalit??s

- Table
  - Ajout du support de l'arborescence des donn??es (#14632 by @ziyoung)

#### Corrections de bugs

- Tabs
  - Utilise la couleur primaire comme couleur de l'ombre (#14558 par @Richard-Choooou)
  - Rerendu lorsque label change (#14496 par @akki-jat)
- Table
  - Le pied de page suit l'alignement des cellules du corps (#14730 by @ziyoung)
- NavMenu
  - Correction d'un bug de clic sur el-submenu (#14443 par @PanJiaChen)
- Dropdown
  - Compatible avec la nouvelle syntaxe v-slot 2.6 (#14832 by @ziyoung)
- ColorPicker
  - Correction d'une erreur de couleur hexad??cimale (#14793 par @iamkun)
- Tree
  - Revert pr #13349 (#14847 par @ziyoung)
- Tooltip
  - Affichage lorsque la valeur initiale est vraie (#14826 by @ziyoung)
- Docs
  - Mise ?? jour de la documentation du cascader (#14442 par @panhezeng)
- Style
  - Correction des media queries dans sm-only, md-only, lg-only (#14611 by @sinchang)

#### Optimisation

- Chore
  - Ajouter la description de la page web (#14802 par @iamkun)

### 2.6.3

*2019-03-21*

#### Corrections de bugs

- Correction du style de la d??mo de Cascader (#14789 par @ziyoung)
- Suppression des op??rations DOM inutiles (#14788 by @ziyoung)
- Correction DatePicker valeur par d??faut DST (#14562 par @wacky6)

### 2.6.2

*2019-03-21*

##### Nouvelles fonctionnalit??s

- DatePicker
  - Ajout d'une plage de mois pour l'attribut type (#14487 par @zxyRealm)
- i18n
  - Ajout de la locale croate (#14360 par @danijelh)

##### Corrections de bugs

- Input
  - Correction d'un r??gression (#14572 par @wacky6)
- DatePicker
  - Correction du calcul du premier jour de la semaine (#14523 par @sinchang)
  - Correction du format de valeur du s??lecteur de semaine (#13754 par @wacky6)
- Steps
  - Correction du probl??me #14502 (#14596 par @sinchang)
  - Correction du style avec le th??me simple (#14610 par @sinchang)
- Docs
  - Mise ?? jour de la doc fran??aise pour la 2.6.1 et correction de fautes de frappe (#1455555 par @smalesys)
  - Renommage d'une variable dans la documentation de la table (#14587 par @likwotsing)
  - Ajout de l'index de recherche en fran??ais (#14565 par @iamkun)
  - Correction du style de la page TimePicker (#14579 par @ziyoung)
  - Renommage d'une variable dans la page Upload (#14593 par @liupl)
  - Mise ?? jour de la traduction fran??aise (#14643 par @smalesys)
  - Mise ?? jour de la documentation du validateur de formulaire asynchrone (#14694 par @iamkun)
  - Correction d'une erreur de doc tooltip (#14748 par @iamkun)
  - Correction d'une coquille (#14751 par @2bj)
  - Correction de la surbrillance pour Webkit touch (#14703 by @VladG0r)

##### Optimisation

- T??che
  - Mise ?? jour du script de build dans le ci (#14600 par @ziyoung)
  - Mise ?? jour du tracking ga (#14560 par @iamkun)
  - Ajout d'un ??v??nement ga suppl??mentaire (#14633 par @iamkun)
  - Mise ?? jour du groupe de discussion (#14741 par @iamkun)
  - Mise ?? jour des deps de test et conf (#14735 par @wacky6)
  - Mise ?? jour de Gulp (#14745 by @ziyoung)
  - Utilisez le codepen pour afficher les d??mos et correction d'une erreur de doc (#14747 by @ziyoung)

### 2.6.1

*2019-03-03*

#### Corrections de bugs

- **Ne pas sp??cifier la version de node** (par @iamkun dans #14546)
- Correction du r??pertoire doc dans `deloy-faas.sh` (par @ziyoung dans #14553)
- Correction d'un probl??me de style de date dans le changelog de la 2.6.0 (par @island205 dans #14547)
- Correction d'une typo dans la doc (par @wack6 dans #14552)

### 2.6.0

*2019-03-01*

#### Nouvelles fonctionnalit??s
- Timeline
  - Ajout d'un composant timeline (par @jikkai dans #14248)
- DropdownItem
  - Ajout de la propri??t?? `icon` ?? `el-dropdown-item` (par @gabrielboliveira dans #14088)
- Input
  - Ajout de propri??t??s pour afficher les mots de passe (par @phshy0607 dans #13966)
- Select
  - Ajout du slot `empty` (par @elfman au #13785)
- Autocomplete
  - Ajout de la propri??t?? `highlight-first-item` (par @YamenSharaf dans #14269)
- I18n
  - Cr??ation de la locale Arm??nienne (par @hamletbarsamyan dans #14214)
- Docs
  - Traduction fran??aise (par @smalesys dans #12153, #14418, #14434)

#### Optimisation
- Alert
  - Mise ?? jour de la classe du slot par d??faut de la description de Alert (par @iamkun dans #14488)
- Input
  - Mise ?? jour de l'input de type password (par @iamkun dans #14480)
- InputNumber
  - Retrait d'un parseFloat inutile (par @JuniorTour au #14172)
- Menu
  - Ajout du support de `el-menu-item` sans index (par @georgyfarniev dans #13298)
- Table
  - Suppression de certaines op??rations du DOM (par @elfman dans #13643)
- Upload
  - Optimisation du code (par @elfman dans #13973)
- Popup
  - Optimisation du code (par @KAionro dans #14413)
- Docs
  - Ajout de d??tails sur la fa??on d'ex??cuter le mode play pour les contributeurs (par @island205 dans #14355)
  - Ajout d'un avertissement concernant Input (par @wacky6 dans #14463)
  - Mise ?? jour de la doc de Table (par @luguokong dans #14329)
  - Mise ?? jour de la doc d'Input (par @iamkun dans #14437)
  - Mise ?? jour de la doc sur le th??me (par @wangguohaohao dans #14297)
  - Le style de l'ic??ne change lorsque vous passez dessus (par @tuxinghuan dans #14295)
- Build
  - Minification du CSS et du JS pour le site d'Element (par @iamkun dans #14430)
  - Acc??l??ration de webpack (par @hetech dans #14484)
  - Utilisation du cli pour s??lectionner la version de publication (par @hetech dans #14354)
- Installation de stale pour la gestion des issues (par @island205 dans #14392)

#### Corrections de bugs
- Menu
  - Correction d'un bug de focus des sous-menus lors du changement d'onglet du navigateur (par @liupl dans #13976)
- MessageBox
  - Correction de la d??finition du type (par @NateScarlet dans #14278)
- ScrollBar
  - Emp??che le clic droit sur le bouton du pouce (par @xifeiwu dans #14196)
- Switch
  - D??clenchement de la validation du formulaire si la valeur change (par @hetech dans #14426)
- Table
  - La m??thode toggleAllSelection est maintenant une m??thode d'instance (par @letanure dans #14075)
- Tabs & Dropdown
  - Correction du style (par @hetech dans #14452)
- Tree
  - Les tips sont diff??rents des tableaux (par @ColinCll dans #14331)
- Docs
  - Correction d'une erreur de doc du DatetimePicker (par @iamkun dans #14290)
  - Probl??me d'orthographe dans la documentation du DatePicker (par @helmut dans #14481)
  - Correction du style de la doc de Pagination(par @liuchuzhang dans #14451)

#### Breaking changes
- Table
  - Fix params order of row events (by @jikkai in #12086)

### 2.5.4

*2019-02-01*

#### Corrections de bugs

- Build: Correction d'un probl??me de configuration de babel qui cassait la transition collapse (par @island205 dans #14282)

### 2.5.3

*2019-01-31*

#### Optimisation

- Optimisation du code de Message (par @vok123 dans #14029)
- Suppression des gh-pages (par @ziyoung dans #14266)
- Ajout du lien IssueHunt (par @island205 dans #14261)

#### Corrections de bugs

- Correction d'une erreur du module UMD c??t?? serveur (par @island205 dans #14242)
- Correction du style du TabBar actif (par @iamkun dans #14240)
- Correction d'une erreur de code dans la d??mo de Table (par @xunmeng dans #14253)

### 2.5.2

*2019-01-27*

#### Optimisation
- Docs:
  - Mise ?? jour du ChangeLog ES 2.5.1 (par @Gonzalo2310 dans #14231)

#### Corrections de bugs
- Build:
  - Suppression des commentaires non supprim??s dans le module umd `lib/index.js` (par @island205 dans #14233)
  - Correction d'une erreur d'exportation dans le module commonjs utilis?? dans nuxt.js (par @island205 dans #14232)
  - Correction des probl??mes de build 2.5.1 (par @iamkun dans #14228)

### 2.5.1

*2019-01-26*

#### Optimisation
- DatePicker: surbrillance du mois et de l'ann??e courants (par @Debiancc dans #14211)
- Mise ?? jour du changelog 2.5.0 (par @wacky6 dans #14217)

#### Corrections de bugs
- Correction d'un probl??me d'exportation due par la mise ?? jour du webpack (par @island205 dans #14220)
- Conservation de la docs 2.4.11 && nouveau sous-dossier pour 2.5+ (par @iamkun dans #14222)

### 2.5.0

*2019-01-25*

#### Nouvelles fonctionnalit??s
- DatePicker
  - Ajout de l'attribut `validate-event` (par @ziyoung dans #13531)
- DateTimePicker
  - `pickerOptions` supporte l'option `selectableRange` (par @eeeeeeeeeeeason)
- Tag
  - Ajout de l'??v??nement `click` (par @licdream dans #14106)
- I18n
  - Support de la langue kirghize (par @zzjframework dans #14174)

#### Optimisation
- Mise ?? niveau vers webpack@4 (par @jikkai dans #14173)
- Input
  - Simplification de l'impl??mentation, suivant un flux de donn??es ?? sens unique. Correction de plusieurs bugs li??s. (par @wacky6 dans #13471)
- Mise ?? jour du fichier Axure avec de nouveaux composants (par @ziyoung dans #13773)

#### Corrections de bugs
- Autocomplete
  - Correction de la derni??re ligne du menu d??roulant qui ??tait coup??e (#13597) (par @ziyoung)
  - Correction d'une fl??che de popper manquante (#13762) (par @liuchuzhang)
- Carrousel
  - Nettoyage du timer lorsque le composant est d??truit (#13820) (par @elfman)
- Cascader
  - Suppression de la propri??t?? obsol??te des props calcul??es (#13737) (par @iamkun)
  - Correction de la d??finition du type CascaderOption dans TypeScript (#13613) (par @NateScarlet)
  - Correction de l'ic??ne couvrant le texte (#13596) (par @ziyoung)
- Checkbox
  - Refonte du style (par @PanJiaChen)
- DatePicker
  - Ajout d'un `key` de v-for manquant dans TimeSpinner (#13547) (par @Ende93)
  - Correction du surlignage de la semaine dans la bordure de l'ann??e (#13883) (par @suyi91)
- Input
  - Correction de la r??f??rence de textarea dans le DOM (#13803) (par @laomu1988 @island205)
- Pagination
  - La valeur d'entr??e ne sera pas inf??rieure ?? 1 (#13727) (par @elfman)
- Popover
  - Correction d'un probl??me de popover avec le d??clencheur de hover (#13104) (par @goldengecko)
  - Correction d'une fuite de m??moire de l'instance popper (#13988) (par @qpxtWhite)
- Radio
  - Refonte du style (par @ohhhoney1)
- Table
  - Am??lioration du tri des tables en cliquant sur la fl??che de tri (#12890) (par @ohhoney1)
  - Correction d'un probl??me d'alignement vertical du texte vide sur IE10+ (#13638) (par @imzjy)
  - Correction de la documentation sur le type d'index (#13628) (par @ilovefafafa)
  - Correction du probl??me d'affichage `show-summary` lorsque le header multi-niveaux est fixe (#13914) (par @luckyCao)
- Tabs
  - Correction d'un bug de d??filement automatique (#13696) (par @iamkun)
  - Obtenir l'onglet correct par le nom de l'onglet (#13705) (par @iamkun)
  - Utilisez paneName au lieu de name pour d??terminer le style du panneau (#13733) (par @iamkun)
- Tree
  - Correction de la propri??t?? `showCheckbox` sur `Tree` qui ne pouvait pas affecter leurs `tree-node` enfants(par @KidneyFlower)
  - Mise ?? jour des fichiers de doc et de d??finition (#13540) (par @ziyoung)
- Upload
  - Ajout de le propri??t?? `url` au fichier upload?? lorsque `list-type` est modifi?? (#13771) (par @elfman)
- Slider
  - Correction de l'indentation du code source (#13955) (par @wacky6)
- I18n
  - Ajout des traductions manquantes en catalan (par @jaumesala)
  - Ajout de la traduction russe manquante (#13658) (par @justlp)
  - Correction des traductions en finnois (#14137) (par @jenkrisu)
- Doc
  - Mise ?? jour de la documentation espagnol depuis la 2.4.11 (#13522) (par @Gonzalo2310)
- Autres
  - Suppression d'un script inutile (par @ziyoung)
  - Correction des ancres (#13753) (par @iamkun)
  - Correction de l'incoh??rence des majuscules dans la documentation (par @wonderjar)
  - Ajout du QR code du chat DingDing au readme (#13957) (par @iamkun)
  - Ajout des logs yarn au .gitignore (#13922) (par @mimimi)
  - Suppression du sponsor duotai (#14156) (par @island205)
  - Mise ?? jour du QR code dans le readme (#13960) (par @iamkun)
  - Mise ?? jour du lien CDN, correction d'une typo (par @ziyoung)

### 2.4.11

*2018-11-21*

- Revert pr #13296. Correction d'un clic sur Menu externe causant l'effondrement du SubMenu, #13478
- Ajustement des points de rupture media query sur petit ??cran (xs), #13468 (par @alekoshen712)

### 2.4.10

*2018-11-16*

- Correction des clics multiples sur Select pour afficher la liste d??roulante, #13268
- L'ic??ne d'effacement des champs n'est pas affich??e lorsque Form est d??sactiv??, #13208
- Ajustement des styles de Select, Progress, Autocomplete, Tooltip, Collaspe, TimePicker, #13188 (par @porcelainHeart) #13210 #13266 #13266 #13257 #13290 #13347 (par @PanJiaChen)
- Ajout de l'attribut `loop` dans le composant Carrousel, #13217
- Lorsque les donn??es de Table changent, la ligne en surbrillance reste, #13200
- Le slot du header de Table peut recevoir des param??tres, #13263
- La m??thode `clearFilter` de Table peut recevoir des arguments, #13176
- La bulle d'aide n'est plus cr????e lorsqu'il n'y a pas de contenu dans la cellule de Table, #13152 (par @rongxingsun)
- Le contenu de la zone de saisie du panneau ColorPicker peut ??tre affich?? correctement, #13278
- ColorPicker ne d??clenche plus la validation des formulaires lors du glisser-d??poser, #13299
- InputNumber: ajout de la m??thode `select`, #13286 (par @st-sloth)
- AutoComplete: ajout de l'??v??nement `clear`, #12171(par arthurdenner) #13326
- Vous pouvez fermer Menu en cliquant ?? l'ext??rieur, #13296
- La m??thode `validateField` du formulaire peut recevoir des arguments, #13319
- Cascader: ajout de l'??v??nement `visible-change`, #13415
- DatePicker: a ajout d'un slot pour les s??parateurs d'intervalle, #13272 (par @milworm)
- Tree: ajout des propri??t??s `iconClass` et `currentNodeKey`, #13337 #13197 (par @isnifer)
- Progress: ajout du texte de statut #13198 (par @ali-master)
- Correction de `defaultCheckedKeys` de Tree, #13349 (par @dive2Pro)

### 2.4.9

*2018-10-26*

- Le param??tre `clearValidate` de Form supporte les strings #12990 (par @codinglobster)
- Ajout de l'attribut `type` pour Badge, #12991
- Les utilisateurs peuvent utiliser scoped-slot pour personnaliser l'en-t??te de colonne de Table #13012 (par @ivanseidel)
- Correction du champ de Select incapable d'entrer du texte sous IE, #13034 (par @GaliMU)
- Les options Select ne s'enroule pas lorsque l'espace est suffisant, #12329 (par @akki-jat)
- Lorsque la liste d??roulante de Select est ouverte, l'ic??ne de la fl??che s'affichera ??galement correctement, #12353 (par @firesh)
- Correction de l'attribut de taille de Select qui ne fonctionnait pas, #13070
- La s??lection de plusieurs valeurs peut aussi ??tre effac??e, #13049 (par @ZSkycat)
- Correction du dernier TabNav qui ne pouvait pas ??tre supprim??, #13039
- Correction d'un probl??me d'affichage du label TabNav, #13178
- Ajout d'un slot de titre pour Alert, #13082 (par @Kingwl)
- Correction d'un probl??me o?? le contenu de l'infobulle de Table ??tait incorrect, #13159 (par @elfman)
- Optimisation de l'animation de Upload lorsque le fichier est supprim??, #12987
- Style ajust?? pour InputNumber lorsque le bouton de commande n'est pas affich??, #13052

### 2.4.8

- Ne pas afficher le contour lorsque le Switch est focus, #12771
- Correction du style de Dropdown dans ButtonGroup, #12819 (par @bluejfox)
- Ajout d'un ??v??nement d'ouverture pour Dialog, #12828
- Correction de l'ordre d'affichage incorrect de TabNav, #12846
- Correction d'un probl??me qui emp??chait les Tabs de d??filer jusqu'?? l'onglet s??lectionn??, #12948
- Correction d'un probl??me de l'identificateur qui ne s'affiche pas lorsque le noeud de Tree est gliss??, #12854
- Le param??tre de l'??v??nement validation du formulaire contient le message de validation #12860 (par @YamenSharaf).
- Correction de DatePicker pour ne pas v??rifier la validit?? du temps d'entr??e de l'utilisateur, #12898
- Correction d'un probl??me avec l'attribut `render-header` de l'en-t??te de table qui ne fonctionnait pas, #12914

### 2.4.7

*2018-09-14*

- Correction de DatePicker ne d??clenchant pas la validation du formulaire, #12328 #12348
- Correction des erreurs lanc??es par DatePicker en mode multiple, #12347
- Correction d'une position incorrecte du spinner de DatePicker, #12415 (par @rang-ali)
- Correction du remplissage automatique de la zone de saisie de DatePicker, #12521 (par @abdallanayer)
- Correction du champ non-subrillant dans Cascader, #12341
- Correction d'un mauvais ordre de Tabpane, #12346
- Correction d'une position incorrecte du curseur ColorPicker, #12376 (par @cnwhy)
- Correction du style de SubMenu, #2457
- Correction de la surbrillance apr??s la s??lection de SubMenu, #12479
- Correction des valeurs incorrectes s??lectionn??es par Cascader, #12508 (par @huangjinqiang)
- Correction d'une valeur incorrecte dans le champ d'entr??e Pagination, #12525
- Correction de l'ordre dans lequel la Pagination d??clenche les ??v??nements, #12530
- Correction des filtres de table non-affich??s, #12539
- Correction de l'arbre incapable de supprimer des n??uds, #12684
- Correction de la hauteur de Select Input changeant en mode simple, #12719
- Correction d'un style du label de FormItem sous forme imbriqu??e, #12748
- Ajout de l'attribut `autocomplete` pour Input, `auto-complete` devenant obsol??te, #12514 (par @axetroy)
- Ajout des slots-scope pour Form pour afficher les informations de validation, #12715 (par @YamenSharaf)

### 2.4.6

*2018-08-09*

- Correction de Table n'affichant pas l'ic??ne de filtre lorsque `filters` est un tableau vide, #12165
- Correction de Menu ne sauvegardant pas l'??tat actif lorsque `collapse` change, #12178 (par @elfman)
- Correction du Cascader n'??chappant pas les caract??res sp??ciaux poue les Regexp, #12248
- Correction d'un bouton Radio d??sactiv?? affichant l'ombre d'une case lorsqu'on clique dessus, #12262
- Correction de arrow key qui n'a pas d'effet lorsque la valeur par d??faut est `undefined`, #12322
- Correction de la fonction de requ??te de Select non-stabilis??e en mode multi, #12181
- Correction du mot-cl?? de la requ??te Select disparaissant en mode multi, #12304
- Correction d'une largeur incorrecte de Dialog lorsqu'il est affich?? en plein ??cran, #12203
- Correction de l'affichage incorrect de Main sur IE, #12237
- Correction de Input d??clenchant deux validations de formulaire, #12260
- Correction de l'ajout d'un nouveau n??ud d'arborescence provoquant la disparition des n??uds, #12256
- Correction d'un n??ud d'arborescence non supprim?? apr??s avoir gliss??, #12279
- Correction du Popover non-visible quand InputNumber a le focus, #12284
- Ajout de l'attribut `popper-append-to-body` pour Autocomplete, #12241
- Ajout du support du modificateur `sync` pour l'attribut `page-size` de Pagination, #12281

### 2.4.5

*2018-07-26*

- Correction du r??glage de Table `class-name` qui ne fonctionne pas pour les colonnes `expand`, #12006
- Ajout de la m??thode `toggleAllSelection` pour Table, #12047
- Correction d'une mauvaise position du slot de suffixe lorsque Input contient Select, #12108
- Correction de `line-height` de l'option impossible ?? r??gler, #12120
- Correction de TimeSelect avec la valeur par d??faut `null` ne pouvant ??tre assign?? apr??s avoir ex??cut?? `resetField`, #12010
- Correction d'un ??v??nement keydown qui n'??tant pas arrow key ne fonctionne pas dans Tree, #12008
- Correction d'un n??ud parent v??rifi?? en mode lazy, #12106
- Ajout du param??tre `includeHalfChecked` pour getCheckedNodes de Tree, #12014

### 2.4.4

*2018-07-13*

- Correction du d??clenchement de la validation de Select apr??s la r??initialisation du formulaire, #11837
- Correction d'une mauvaise position du slot `suffix` de Input lorsque le slot `suffixe` est avec le slot `append`, #11951
- Correction de Input affichant toujours l'ic??ne clear m??me en lecture seule, #11967
- Correction d'un n??ud d'arborescence coch?? lorsqu'il est d??sactiv??, #11847
- Correction des `default-checked-keys` qui ne fonctionnait pas, #11971
- Correction de `empty-text` non visible lorsque le noeud de Tree est filtr??, #11971
- Correction de la position du `empty-text` surdimensionn?? dans Table, #11965
- Correction de la surbrillance de la ligne de Table lorsque `current-row-key` est assign??e ?? `null`, #11866
- Correction de l'affichage de la liste d??roulante des filtres lorsque `filters` est un tableau vide, #11864
- Correction du label de Radio qui n'arr??te pas la propagation des ??v??nements, #11912

### 2.4.3

*2018-07-03*

- Correction de `allow-drop` qui ne fonctionnait pas correctement lorsque les n??uds de Tree avaient une hauteur personnalis??e, #11797
- Maintenant vous pouvez passer un param??tre ?? la m??thode `clearValidate` du formulaire, en sp??cifiant quels r??sultats de validation FormItems doivent ??tre effac??s, #11821
- Ajout de l'attribut `distinguishCancelAndClose` pour MessageBox, #11831

### 2.4.2

*2018-06-26*

- Maintenant `class-name` et `label-class-name` de Table sont r??actifs, #11626
- Correction de Table qui mettait toujours en surbrillance la ligne cliqu??e lorsque `highlight-current-row` ??tait `false`, #11646
- Correction d'un bug de style de ButtonGroup lorsqu'il n'a qu'un seul bouton `round` ou `circle`, #11605
- Correction du style du Select de Pagination, #11622
- Correction de la m??thode `open` du menu quand `collapse` est dynamiquement chang??, #11646
- Ajout des param??tres `activeName` et `oldActiveName` au hook before-leave de Tabs, #11713
- Correction de Cascader ayant le focus apr??s avoir cliqu?? ?? l'ext??rieur, #11588
- Correction de Cascader ne se fermant pas quand l'option est cliqu??e quand `change-on-select` est `true`, #11623
- La mise ?? jour programmatique de la valeur de Select d??clenchera la validation du formulaire, #11672

### 2.4.1

*2018-06-08*

- Suppression du duplicata de la d??claration de type pour Autocomplete, #11388
- Correction du style de fl??che d??roulante de Select dans FireFox lorsqu'il est imbriqu?? dans Form, #11427
- Correction de l'ic??ne de l'option de Select qui s'affiche toujours lorsque la valeur initiale est `null`, #11460
- Correction d'un Radio d??sactiv?? affichant l'ombre de la bo??te quand on clique dessus, #11462
- Ajout de l'attribut `iconClass` pour MessageBox, #11499
- Ajout de l'attribut `stretch` pour Tabs, #11476
- Correction d'un probl??me d'ordre de rendu de TabPane lorsque Tabs est `lazy`, #11461
- Correction de Table ne conservant pas la surbrillance de la ligne actuelle lors de son ouverture, #11464
- Correction de l'??tat de la mise au point lorsque `before-leave` renvoie une promesse r??solue, #11386
- Correction de la d??sactivation du Popover qui cr??ait encore des poppers, #11426
- Correction de la boucle sans fin de Tree lorsqu'un nouveau noeud est ajout?? en mode lazy, #11430 (par @wangjingf)
- Ajout de l'??v??nement `closed` pour Dialog, #11490

### 2.4.0 Fullerene

*2018-05-28*

#### Nouvelles fonctionnalit??s
- G??n??ral
  - L'outil de d??veloppement et le bundler sont bascul??s vers le webpack natif, #11216
  - Vous pouvez maintenant d??finir globalement l'index z initial des popups, #11257
- Autocomplete
  - Ajout de l'attribut `hide-loading`, #11260
- Button
  - Vous pouvez maintenant utiliser l'attribut `size` sur les boutons circulaires pour contr??ler leur taille, #11275
- InputNumber
  - Ajout de l'attribut `precision`, #11281
- Tabs
  - Ajout de l'attribut `before-leave`, #11259
  - Ajout de l'attribut `lazy`, #11167???by @Kingwl???
- Table
  - Ajout de la m??thode `sort` pour trier manuellement la table, #11311

#### Corrections de bugs
- Input
  - Correction d'un probl??me qui provoquait un re-rendu lors de l'utilisation de l'IME chinois pour saisir rapidement du texte, #11235 (par @STLighter)
- Popover
  - Correction de l'erreur de console lorsque l'??l??ment d??clencheur est Radio ou Checkbox, #11265
- Breadcrumb
  - Correction de l'attribut `to` ne supportant pas la mise ?? jour dynamique, #11286
- Upload
  - Correction de l'erreur de console lorsqu'un fichier est r??solu dans la promesse retourn??e de la m??thode `beforeUpload`, #11297 (par @qusiba)
- Infobulle
  - Correction d'une fl??che mal positionn??e lorsque le contenu est vide, #11335
- Autocomplete
  - Correction de suggestions d'entr??e incorrectes apr??s la suppression rapide d'un mot-cl??, #11323
- ColorPicker
  - Correction d'un ??v??nement `active-change` se d??clenchant incorrectement lorsque le menu d??roulant du picker est ferm??, #11304
- Table
  - Correction d'une erreur de style du panneau de filtre surdimensionn??, #11314
  - Correction de la ligne actuellement s??lectionn??e qui n'??tait pas conserv??e lors du tri de la table, #11348
- Checkbox
  - Correction d'une checkbox unique ne supportant pas la validation, #11271
- Radio
  - Correction du Radio d??sactiv?? quand m??me s??lectionn?? en appuyant sur la touche espace, #11303
- MessageBox
  - Correction de la classe `el-popup-parent-hidden` qui n'??tait pas supprim??e ?? l'ouverture successive de MessageBox, #11371

### 2.3.9

*2018-05-18*

- Correction d'une erreur lorsque les donn??es source n'ont pas le champ sp??cifi?? par l'attribut `prop` d'une TableColumn, lorsque la souris se d??place dans les cellules de cette colonne, #11137
- L'attribut `lockScroll` des composants popup n'ajoute plus un style en ligne ?? l'??l??ment parent, mais ajoute un nom de classe, #1111114
- Correction de l'ic??ne de Progression qui ne s'affichait pas quand son `status` ??tait une exception, #11172
- Correction de l'attribut `d??sactiv??` qui ne fonctionnait pas dans la liste des r??sultats de filtrage du Cascader filtrable, #11185
- Correction d'un probl??me o?? la ligne ??tendue de la table ne peut pas ??tre r??duite si la source de donn??es est mise ?? jour apr??s son extension, #11186
- `setCurrentKey` de Tree accepte maintenant `null` comme param??tre pour annuler le noeud actuellement mis en surbrillance, #11205

### 2.3.8

*2018-05-11*

- Correction du saut du panneau DatePicker au mois courant apr??s avoir choisi une date dans un mois non courant quand `type` est dates, #10973
- Correction de l'Input effa??able affichant toujours l'ic??ne d'effacement en lecture seule, #10912
- Correction de la fermeture du panneau DatePicker sans changer la valeur d??clenchant incorrectement l'??v??nement `change`, #11017
- Correction d'un probl??me de navigation du clavier lorsque Select a regroup?? les options, #11058
- Ajout du slot nomm?? `pr??fixe` pour Select, #11063
- Ajout de la m??thode `clearValidate` pour FormItem, #11076
- Ajout de l'attribut `checkOnClickNode` pour Tree, #1111111

### 2.3.7

*2018-04-29*

- Correction d'une table qui ne mettait pas ?? jour ses largeurs de headers lorsque la barre de d??filement disparaissait ?? cause du filtrage, #10834
- Correction de l'Input effa??able affichant toujours l'ic??ne d'effacement lorsque sa valeur initiale est `null`, #10912
- Correction d'un d??clencheur incorrect de l'??v??nement `active-change` apr??s avoir chang?? la valeur li??e de ColorPicker par programmation, #10903 (par @zhangbobell)
- Correction du Select filtrable qui provoquait une boucle infinie lors de la navigation dans les options ?? l'aide du clavier si toutes les options sont d??sactiv??es, #10945

### 2.3.6

*2018-04-21*

- Correction d'un comportement incorrect du callback `allow-drop` de Tree lorsque le param??tre `type` est utilis??, #10821
- Maintenant vous pouvez entrer correctement les mots-cl??s dans le Select simple filtrable dans IE11, #10822
- Correction d'un Select simple d??clenchant incorrectement un ??v??nement `blur` apr??s avoir cliqu?? sur une option, #10822

### 2.3.5

*2018-04-20*

- Correction d'une surbrillance incorrecte dans le panneau DatePicker lorsque `type` est la semaine, #10712
- Correction d'un InputNumber vide lorsque sa valeur initiale est 0, #10714
- Ajout de l'attribut `automatic-dropdown` pour Select, #10042 (par @Seebiscuit)
- Correction de Rate d??sactiv?? quand m??me mis ?? jour par les touches de navigation, #10726 (par @Richard-Choooou)
- L'attribut `type` de DatePicker peut ??tre `dates`, o?? vous pouvez choisir plusieurs dates dans un s??lecteur, #10650 (par @Mini256)
- Ajout des ??v??nements `prev-click` et `next-click` pour Pagination, #10755
- Ajout de l'attribut `pager-count` pour Pagination, #10493 (par @chongjohn716)
- Ajout de `type` comme 3??me param??tre de l'attribut `allow-drop` de Tree, #10792
- Nous utilisons maintenant ResizeObserver pour d??tecter le redimensionnement des ??l??ments DOM, #10779

### 2.3.4

*2018-04-12*

- Suppression du double de l'attribut `showTimeout` dans la d??claration TypeScript de SubMenu, #10566 (par @kimond)
- Vous pouvez maintenant personnaliser les ??l??ments de Transfert en utilisant le scoped slot, #10577
- Correction d'un clic sur le bouton pr??c??dent d??sactiv?? et le bouton suivant de la pagination d??clenchant toujours l'??v??nement `current-current-change`, #10628
- Correction de Textarea affichant `undefined` dans le SSR lorsque sa valeur n'est pas d??finie, #10630
- Correction de la d??sactivation du style TabItem lorsque `type` est border-card, #10640
- Ajout de `$index` comme quatri??me param??tre du `formatter` de la Table, #10645
- Correction de CheckboxButton non export?? dans la d??claration TypeScript, #10666

### 2.3.3

*2018-04-04*

- Ajout de l'attribut `shadow` pour Card, #10418 (par @YunYouJun)
- Correction de Badge masqu?? lorsque `value` est `0`, #10470
- Correction de quelques bugs de Tree, #10474 #10494
- Ajout de `placement` pour Autocomplete, #10475
- L'attribut `default-time` fonctionne ??galement dans DateTimePicker, #10321 (par @RickMacTurk)
- Suppression du contour bleu de TabItem apr??s que le navigateur n'ait plus le focus ou soit minimis??, #10503
- Ajout de l'attribut `popper-append-to-body` pour SubMenu, #10515
- Suppression du feedback visuel lors du survol d'un ??l??ment BreadcrumbItem non li??, #10551
- Correction de l'??v??nement `change` d'InputNumber pour s'assurer que la valeur li??e du composant est mise ?? jour dans le gestionnaire d'??v??nements, #10553

### 2.3.2

*2018-03-29*

- Correction d'une r??gression d'Autocomplete, #10442

### 2.3.1

*2018-03-29*

- Correction d'une r??gression de `type` d'Inputqui n'??tait pas transmis ?? l'??l??ment natif, #10415
- Ajout de la m??thode `blur` pour Select, #10416

#### 2.3.0 Diamant

*2018-03-28*

#### Nouvelles fonctionnalit??s
- Table
  - Maintenant le `formatter` de TableColumn peut ??tre mis ?? jour dynamiquement, #10184 (par @elfman)
  - Ajout de l'attribut `select-on-indeterminate`, #9924 (par @syn-zeta)
- Menu
  - Ajout de l'attribut `collapse-transition`, #8809 (par @limichange)
- Input
  - Ajout de la m??thode `select`, #10229
  - Ajout de la m??thode `blur`, #10356
- ColorPicker
  - Ajout de l'attribut `predefine`, #10170 (par @elfman)
- Tree
  - Ajout des attributs `draggable`, `allow-drop` et `allow-drag`, et `node-drag-start`, `node-drag-enter`, `node-drag-leave`, `node-drag-leave`, `node-drag-over`, `node-drag-end` et `node-drop`, #9251 #10372 (par @elfman)
- Form
  - La m??thode `validate` a maintenant un deuxi??me param??tre, contenant l'information des ??l??ments de formulaire qui ont ??chou?? ?? la validation, #10279
  - Ajout de l'??v??nement `validate`, #10351
- Progress
  - Ajout de l'attribut `color`, #10352 (par @YunYouJun)
- Button
  - Ajout de l'attribut `circle`, #10359 (par @YunYouJun)

#### Corrections de bugs
- Form
  - Correction du label de FormItem non align?? avec l'Input mixte, #10189
- Menu
  - D??sormais, le menu r??duit n'affichera la bulle d'aide que lorsque le slot `title` de l'??l??ment MenuItem est d??fini, #10193 (par @PanJiaChen).
- Pagination
  - Correction d'un ??v??nement `current-current-change` qui se d??clenchait incorrectement sans interaction de l'utilisateur, #10247
- DatePicker
  - Maintenant, la date et l'heure dans le panneau d??roulant sont correctement format??es en fonction de l'attribut `format`, #10174???by @remizovvv???
- Upload
  - Correction de l'attribut `accept` qui ne fonctionnait pas quand `drag` est vrai, #10278

### 2.2.2

*2018-03-14*

- Ajout de l'??v??nement `clear` pour Input, #9988 (par @blackmiaool)
- Maintenant la saisie manuelle de ColorPicker supporte les modes `hsl`, `hsv` et `rgb`, #9991
- Correction de DatePicker ne d??clenchant pas l'??v??nement `change` lorsque sa valeur initiale est effac??e, #9986
- Maintenant les attributs li??s ?? la classe d'ic??nes de Rate supportent les mises ?? jour dynamiques, #10003
- Correction de Table avec des colonnes fixes dont la hauteur n'est pas mise ?? jour correctement si `max-height` est r??gl??, #10034
- Maintenant le mode plage de DatePicker supporte la s??lection inverse (en cliquant sur la date de fin, puis sur la date de d??but), #8156 (par @earlymeme)
- Ajout de l'attribut `d??sactiv??` pour Pagination, #10006
- Ajout des ??v??nements `after-enter` et `after-leave` pour Popover, #10047
- Correction de Select ne d??clenchant pas la validation lorsque l'utilisateur s??lectionne une option apr??s avoir ex??cut?? `resetFields` du formulaire, #10105
- Correction des largeurs incorrectes des colonnes fixes de Table dans certains cas, #10130
- Correction de MessageBox h??ritant de l'attribut `title` de son instance pr??c??dente lorsqu'il ??tait appel?? sans `title`, #10126 (par @Pochodaydaydayup)
- Ajout de l'attribut `input-size` pour Slider, #10154
- Ajout des ??v??nements `left-check-change` et `right-check-change` pour Transfer, #10156

### 2.2.1

*2018-03-02*

- Correction d'un r??tr??cissement de Aside, Header et Footer dans certaines mises en page, #9812
- Correction de Table avec un attribut `height` qui ne rendait pas dans SSR, #9876
- Correction d'une Table extensible ne calculant pas sa hauteur lorsqu'une rang??e est agrandie, #9848
- Correction d'un ??v??nement `change` qui ne se d??clenchait pas lors de la saisie manuelle de la date dans DateTimePicker, #9913
- Correction de Select affichant ses options lorsque la bo??te de saisie est cliqu??e avec le bouton droit de la souris, #9894 (par @openks)
- Ajout de l'attribut `tooltip-class` pour Slider, #9957
- Maintenant Select garde le focus apr??s la s??lection, #9857 (par @Seebiscuit)
- Ajout de l'attribut `target-order` pour Transfer, #9960

### 2.2.0 Graphite

*2018-02-12*

#### Nouvelles fonctionnalit??s
- Menu
  - Ajout des attributs `popper-class` et `disabled` pour le sous-menu, #9604 #9771
  - Le menu horizontal prend maintenant en charge le sous-menu multicouche, #9741
- Tree
  - Ajout de l'??v??nement `node-contextmenu`, #9678
  - Vous pouvez maintenant personnaliser le mod??le de n??ud en utilisant un slot avec port??e, #9686
  - Ajout des m??thodes `getNode`, `remove`, `remove`, `append`, `insertBefore`, `insertAfter`, `getCheckedKeys`, `getHalfCheckedNodes`, `getHalfCheckedNodes`, `getHalfCheckedKeys` et de l'??v??nement `check`, #9718 #9730
- Transfer
  - Ajout de la m??thode `clearQuery`, #9753
- Select
  - Ajout de l'attribut `popper-append-to-body`, #9782

#### Corrections de bugs
- Table
  - Correction d'un clic sur l'ic??ne d'expansion d'une ligne extensible qui d??clenche l'??v??nement `row-click`, #9654
  - Correction de la mise en page non mise ?? jour lorsque la largeur des colonnes est modifi??e par glisser-d??poser de l'utilisateur, #9668
  - Correction d'un probl??me de style lorsque la ligne de r??sum?? coexiste avec des colonnes fixes, #9667
- Container
  - Les composants fixes de Container ne s'??tirent pas dans IE11, #9655
- Loading
  - Correction du chargement n'apparaissant pas lorsque la valeur de `v-loading` est chang??e en true dans le hook `mounted`, #9722
- Switch
  - Correction de deux ??v??nements de clics natifs d??clench??s lorsque Switch est cliqu??, #9760

### 2.1.0 Charcoal

*2018-01-31*

#### Nouvelles fonctionnalit??s
- Cascader
  - Ajout des ??v??nements `focus` et `blur`, #9184 (par @viewweiwu)
- Table
  - La m??thode `filter-method` a maintenant un troisi??me param??tre `column`, #9196 (par @liyanlong)
- DatePicker
  - Ajout des attributs `prefix-icon` et `clear-icon`, #9237 (par @AdamSGit)
  - Ajout de l'attribut `default-time`, #9094 (par @nighca)
  - Le format `value-format` supporte maintenant `timestamp`, #9319 (par @wacky6)
- InputNumber
  - Maintenant la valeur li??e peut ??tre `undefined`, #9361
- Select
  - Ajout?? l'attribut `auto-complete`, #9388
- Form
 - Ajout de l'attribut `d??sactiv??`, #9529
 - Ajout de l'attribut `validateOnRuleChange`, #8141
- Notification
  - Ajout de la m??thode `closeAll`, #9514

#### Corrections de bugs
- InputNumber
  - Correstion du reset lors de la saisie du point des nombres d??cimaux, #9116
- Dropdown
  - Correction du mauvais positionnement du menu d??roulant lorsque la page n'a qu'une barre de d??filement horizontale dans certains navigateurs, #9138 (par @banzhuanmei)
- Table
  - Correction d'une erreur dans le calcul du nombre de colonnes fixes apr??s les changements de donn??es des colonnes, #9188???by @kolesoffac???
  - Correction de la bordure de la derni??re colonne de l'en-t??te group?? qui n'??tait pas correctement affich??e, #9326
  - Correction d'un positionnement incorrect de l'en-t??te du tableau dans Safari, #9327
  - Correction de la r??duction des lignes extensibles lorsque les donn??es de la table changent, #9462
  - Correction de rendus multiples inutiles dans certaines conditions, #9426
  - Correction d'une erreur de calcul de la largeur de colonne lors de la modification de `width` de TableColumn, #9426
- Loading
  - Correction de Loading ne se cachant pas correctement dans certaines conditions, #9313
- DatePicker
  - Correction de la m??thode `focus` qui ne fonctionnait pas en mode "range", #9437
  - Correction du clic sur le bouton "now" qui s??lectionnait toujours la date actuelle m??me si elle ??tait d??sactiv??e, #9470 (par @wacky6)
  - Correction d'une date trop serr??e lors de la navigation, #9577 (par @wacky6)
- Steps
  - Correction d'une erreur de style dans IE 11, #9454

#### Changements
- Menu
  - Le menu contextuel en mode `collapse` s'ajoute maintenant directement ?? `body`, de sorte qu'il est visible lorsqu'il est imbriqu?? dans Aside, #9263
- Table
  - Maintenant, cocher les cases dans la Table multi-s??lection ne d??clenche pas l'??v??nement `row-click`, #9467
- Loading
  - Le `z-index` du masque de chargement non plein ??cran est chang?? ?? 2000. Le `z-index` du masque de chargement plein ??cran se mettra ?? jour dynamiquement avec les composants popup, #9522
- Dropdown
  - Les attributs `show-timeout` et `hide-timeout` ne fonctionnent maintenant que lorsque le d??clencheur est `hover`, #9573

### 2.0.11

*2018-01-08*

- Correction d'un probl??me de couleur de bordure de Select dans les slots `prepend` ou `append` de Input, #9089
- Correction du param??tre `remove-tag` de l'??v??nement Select, #909090
- Ajout des attributs `show-timeout` et `hide-timeout` pour le sous-menu, #8934 (par @HugoLew)
- Correction d'un style Tooltip manquant de `show-overflow-tooltip` lors de l'importation de Table sur demande, #9130
- Correction d'un dysfonctionnement du tri des colonnes de la table apr??s l'ex??cution de `clearSort` sur cette colonne, #9100 (par @zEmily)
- Le fichier de configuration i18n pour le tch??que est renomm?? de `cz` en `cs-CZ`, #9164

### 2.0.10

*2017-12-29*

- Calcul erron?? de la hauteur du tableau lorsque la colonne fixe et la ligne de somme coexistent, #9026
- Correction d'un style de couleur non compil?? du texte vide dans le tableau, #9028
- Maintenant, DatePicker n'??met que l'??v??nement `change` quand la valeur est vraiment chang??e, #9029 (par @remizovvvv)
- Ajout de l'attribut `tabindex` pour Input, #9041 (par @dicklwm)

### 2.0.9????

*2017-12-24*

- Ajout?? la fonction de hook "avant suppression" pour Upload, #8788 (par @firesh)
- Correction de la valeur initiale de `error` qui ne fonctionnait pas pour FormItem, #8840
- La directive Loading prend maintenant en charge le nom de classe personnalis?? gr??ce ?? l'attribut `element-loading-custom-class`, #8826 (par @earlymeme)
- Correction CarouselItem devenant invisible lorsque les donn??es sont mises ?? jour de mani??re asynchrone, #8921
- Ajout de l'attribut `renderAfterExpand` pour Tree, #8972

### 2.0.8

*2017-12-12*

- Ajout de la documentation en espagnol
- Correction du `show-timeout` de Dropdown qui ne fonctionnait pas quand le d??clencheur est click, #8734 (par @presidenten)
- Correction du temps de validation des formulaires pour les r??gles dont le d??clencheur est blur, #8776
- Correction d'un ??v??nement de blur de DatePicker avec intervalle, #8784
- L'attribut `format` de TimePicker supporte maintenant AM/PM, #8620 (par @firesh)

### 2.0.7

*2017-11-29*

- Correction du style du bouton de type texte d??sactiv??, #8570

### 2.0.6

*2017-11-29*

- Correction d'un bug de style des ic??nes de tri de la table, #8405
- Correction du m??canisme de d??clenchement de Popover lorsque son `trigger` est manuel, #8467
- Ajout des attributs `prefix-icon` et `suffix-icon` pour Autocomplete, #8446 (par @liyanlong)
- Ajout de l'attribut `separator` pour Cascader, #8501
- Ajout de l'attribut `clearable` pour Input, #8509 (par @lbogdan)
- Ajout de l'attribut `background` pour Pagination, #8553

### 2.0.5

*2017-11-17*

- Correction de la r??gression Popover, Tree, Breadcrumb et Cascader dans 2.0.4, #8188 #8217 #8283
- Correction d'une fuite de m??moire de la directive `clickoutside`, #8168 #8225 (par @badpunman @STLighter)
- Correction de la hauteur du Select multiple lorsque sa valeur est effac??e, #8317 (par @luciy)
- Ajout de l'attribut `collapse-tags` pour plusieurs S??lectionner pour remplacer les balises par une ligne de texte, #8190
- Correction d'une consommation CPU ??lev??e caus??e par la table cach??e, #8351
- Maintenant vous pouvez utiliser la m??thode `doLayout` de la Table pour mettre ?? jour sa disposition, #8351

### 2.0.4

*2017-11-10*

- Accessibilit?? am??lior??e pour Cascader, Dropdown, Message, Notification, Popover, Tooltip et Tree.
- Correction du redimensionnement de Container lorsque la largeur de la fen??tre d'affichage diminue, #8042
- Correction de la suppression incorrecte de `updateKeyChildren` dans Tree, #8100
- Correction de la hauteur de la CheckboxButton avec bordure lorsque le bouton est imbriqu?? dans un formulaire, #8100
- Correction d'une erreur d'analyse du menu pour les couleurs personnalis??es, #8153 (par @zhouyixiang)

### 2.0.3

*2017-11-03*

- Correction des attributs `??ditable` et `readonly` pour DatePicker avec intervalle, #7922
- Correction d'une erreur de style des Tabs imbriqu??s, #7941
- Correction d'une erreur de style de la derni??re ??tape des Steps verticales, #7980
- Correction de la synchronisation du d??clenchement de l'??v??nement `current-current-change` pour Pagination, #7995
- Correction d'une infobulle non enregistr??e dans Menu, #7995

### 2.0.2

*2017-10-31*

- Un clic droit sur les boutons de InputNumber ne changera pas sa valeur, #7817
- La m??thode `validate` de Form peut maintenant attendre des validations asynchrones avant d'ex??cuter son callback, #7774 (par @Allenice)
- Correction de la plage de s??lection de DatePicker ne fonctionnant pas dans les navigateurs Chromium 53-57, #7838
- Correction des ic??nes manquantes de pr??visualisation et de suppression de Upload lorsque son `list-type` est picture-card, #7857
- Ajout de l'attribut `sort-by` pour TableColumn, #7828 (par @wangfengming)
- Correction de DatePicker affichant parfois un mauvais num??ro d'ann??e lors de la s??lection de la premi??re semaine en mode semaine, #7860 (par @hhh23485)
- Correction d'une erreur de style d'ic??ne des Steps verticales, #7891
- La 'hot area' pour les fl??ches de n??ud dans Tree est ??tendue, #7891

### 2.0.1

*2017-10-28*

- Correction d'une erreur de style de RadioButton et CheckboxButton, #7793
- Correction de TimePicker qui ne r??pondait pas au d??filement de la souris dans certaines conditions, #7811
- Correction des styles incomplets de certains composants lors de l'importation ?? la demande, #7811

### 2.0.0 Carbon

*2017-10-27*

#### Nouvelles fonctionnalit??s
- G??n??ral
  - Un nouveau th??me : `theme-chalk`.
  - L'accessibilit?? des ??l??ments suivants est am??lior??e : Alert, AutoComplete, Breadcrumb, Button, Checkbox, Collapse, Input, InputNumber, Menu, Progress, Radio, Rate, Slider, Switch, Upload
  - Ajout du typage TypeScript
  - Toutes les ic??nes existantes sont redessin??es. De nouvelles ic??nes sont ajout??es
  - Ajout d'une s??rie de classes bas??es sur les breakpoints qui masquent les ??l??ments lorsque la taille de la fen??tre remplit certaines conditions
  - Ajout des composants de mise en page : Container, Header, Aside, Main, Footer
  - Vous pouvez maintenant configurer la taille des composants de mani??re globale. Lors de l'importation d'un ??l??ment, vous pouvez ajouter un objet de configuration global avec une propri??t?? `size` pour configurer les tailles par d??faut pour tous les composants.
- Button
  - Ajout de l'attribut `round`. Il est utilis?? pour les boutons ?? coins ronds #6643
- TimeSelect
  - Vous pouvez maintenant naviguer en appuyant sur les touches `Up` et `Down`, et en appuyant sur `Enter` vous s??lectionnez l'heure #6023.
- TimePicker
  - Vous pouvez maintenant naviguer ?? l'aide des touches fl??ch??es, et en appuyant sur `Entr??e` vous s??lectionnez l'heure #6050.
  - Ajout de `start-placeholder` et de `end-placeholder`. Ce sont des placeholders pour les deux champs en mode intervalle #7169
  - Ajout de l'attribut `farrow-control` pour faire tourner le temps avec les fl??ches #7438
- Tree
  - Maintenant les noeuds enfants ne font pas de rendu avant la premi??re ouverture #6257
  - Ajout de l'attribut `check-descendants`. Il d??termine si les n??uds enfants sont v??rifi??s lors du contr??le de leur n??ud parent en mode `lazy` #6235
- Tag
  - Ajout?? l'attribut `size` #7203
- Datepicker
  - Maintenant `timeFormat` peut formater le TimePicker quand le type est r??gl?? sur `datetimerange` #6052
  - Ajout de `start-placeholder` et de `end-placeholder`. Ce sont des placeholders pour les deux champs en mode intervalle #7169
  - Ajout de l'attribut `value-format` pour personnaliser le format de la valeur li??e, #7367
  - Ajout de l'attribut `unlink-panels` pour dissocier les deux panneaux de date lors de la s??lection d'une plage de dates
- MessageBox
  - Ajout de l'attribut `closeOnHashChange` #6043
  - Ajout de l'attribut `center` pour que le contenu puisse ??tre centr?? #7029
  - Ajout de l'attribut `roundButton` pour afficher les boutons ronds #7029
  - Ajout de l'attribut `dangerouslyUseHTMLString`. Lorsqu'il est r??gl?? sur `true`, `message` sera interpr??t?? comme une cha??ne HTML<sup>\*</sup> #6043
  - Ajout de l'attribut `inputType` pour assigner le type de l'input int??rieur, #7651
- Dialog
  - Ajout des attributs `width`???`fullscreen`???`append-to-body`. La bo??te de dialogue peut maintenant ??tre imbriqu??e
  - Ajout de l'attribut `center` pour que le contenu puisse ??tre centr?? #7042
  - Ajout de `focus-after-closed`???`focus-after-open` pour am??liorer l'accessibilit?? #6511
- ColorPicker
  - Maintenant vous pouvez taper les couleurs dans le champ de saisie #6167
  - Ajout des attributs `size` et `disabled` #7026
  - Ajout de l'attribut `popper-class` #7351
- Message
  - Maintenant la couleur des ic??nes peut ??tre modifi??e par CSS #6207
  - Ajout de l'attribut `dangerouslyUseHTMLString`. Lorsqu'il est r??gl?? sur `true`, `message` sera interpr??t?? comme une cha??ne HTML<sup>\*</sup> #6207
  - Ajout de l'attribut `center` pour que le contenu puisse ??tre centr?? #6875
- Notification
  - Ajout de l'attribut `position` pour configurer o?? Notification appara??t #6231
  - Ajout de l'attribut `dangerouslyUseHTMLString`. Lorsqu'il est r??gl?? sur `true`, `message` sera interpr??t?? comme une cha??ne HTML<sup>\*</sup> #6231
  - Ajout de l'attribut `showClose` pour cacher le bouton de fermeture #6402
- Rate
  - Ajout de l'attribut `show-score` pour d??terminer si le score actuel est affich?? #6295
- Tabs
  - Ajout de l'attribut `tab-position` #6096
- Radio
  - Ajout des attributs `border` et `size` #6690
- Checkbox
  - Ajout des attributs `border` et `size` #6690
- Alert
  - Ajout de l'attribut `center` pour que le contenu puisse ??tre centr?? #6876
- Menu
  - Ajout des attributs `background-color`, `text-color` et `active-text-color` #7064
  - Ajout des m??thodes `open` et `close` pour ouvrir et fermer les sous-menus par programmation, #7412
- Form
  - Ajout de l'attribut `inline-message` pour d??terminer si le message de validation est affich?? en ligne #7032
  - Ajout de l'attribut `status-icon` pour afficher une ic??ne de feedback apr??s validation #7032
  - Form et FormItem ont maintenant un attribut `size`. Les composants internes h??riteront de cette taille s'ils ne sont pas sp??cifi??s sur eux-m??mes, #7428
  - La m??thode `validate` retournera maintenant une promesse si le rappel est omis, #7405
  - Ajout de la m??thode `clearValidate` pour la validation des r??sultats pour tous les ??l??ments de formulaire, #7623
- Input
  - Ajout des attributs `suffixe` et `pr??fixe` des slots nomm??s, `suffixIcon` et `prefixIcon` pour ajouter du contenu dans la zone de saisie #7032
- Breadcrumb
  - Ajout de l'attribut `separator-class` pour supporter les ic??nes comme s??parateurs d'??l??ments #7203
- Steps
  - Ajout de l'attribut `simple` pour activer les ??tapes de style simple #7274
- Pagination
  - Ajout des attributs `prev-text` et `next-text` pour personnaliser les textes des pages pr??c??dente et suivante #7005
- Loading
  - Maintenant vous pouvez personnaliser l'ic??ne et la couleur de fond avec les propri??t??s `spinner` et `background` #7390
- Autocomplete
  - Ajout de l'attribut `debounce`, #7413
- Upload
  - Ajout des attributs `limit` et `on-exceed` pour limiter le nombre de fichiers, #7405
- DateTimePicker
  - Ajout de l'attribut `time-arrow-control` pour activer `arrow-control` du TimePicker imbriqu??, #743838
- Layout
  - Ajout d'un nouveau point d'arr??t `xl` pour les fen??tres plus larges que 1920px
- Table
  - Ajout de l'attribut `span-method` pour la fusion de cellules
  - Ajout de la m??thode `clearSort` pour effacer le tri par programmation
  - Ajout de la m??thode `clearFilter` pour effacer le filtre par programmation
  - Pour les lignes extensibles, lorsqu'une ligne est ??tendue, une classe `.expanded` sera ajout??e ?? sa liste de classes, afin que vous puissiez personnaliser son style
  - Ajout de l'attribut `size`
  - Ajout de la m??thode `toggleRowExpansionRowExpansion` pour ouvrir ou r??duire les lignes extensibles par programmation
  - Ajout de l'attribut `cell-class-name` pour assigner un nom de classe aux cellules
  - Ajout de l'attribut `cell-style` pour le style des cellules
  - Ajout de l'attribut `header-row-class-name` pour assigner un nom de classe aux lignes d'en-t??te
  - Ajout de l'attribut `header-row-style` pour le style d'en-t??te
  - Ajout de l'attribut `header-cell-class-name` pour assigner un nom de classe aux cellules d'en-t??te
  - Ajout de l'attribut `header-cell-style` pour le style des cellules d'en-t??te
  - L'attribut `prop` de la tableColumn accepte maintenant les notations `object[key]`
  - Ajout de l'attribut `index` pour TableColumn pour personnaliser les index de lignes
- Select
  - Ajout de l'attribut `reserve-keyword` pour r??server le mot-cl?? de la recherche courante apr??s avoir s??lectionn?? une option.

#### Corrections de bugs
- DatePicker
  - Correction de `v-model` retournant le deuxi??me jour de la semaine s??lectionn??e en mode semaine #6038
  - Correction de la premi??re entr??e effac??e dans le type `daterange` #6021
- DateTimePicker
  - Correction de DateTimePicker et TimePicker s'affectant l'un l'autre lors de la s??lection #6090
  - Correction de l'heure et de la seconde qui peuvent ??tre au-del?? de la limite en s??lectionnant l'heure #6076
- TimePicker
  - Correction de `v-model` qui ne se mettait pas ?? jour correctement lors du blur #6023
- Dialog
  - Correction des textes ayant des bords flous lors de l'ouverture et de la fermeture des listes d??roulantes imbriqu??es #6088
- Select
  - Performances am??lior??es. Maintenant Vue dev-tool ne crashera pas quand un grand nombre de Select sont d??truits #6151
- Table
  - Correction d'un bug ou la table reste masqu??e lorsque son ??l??ment parent appara??t depuis `display : none`
  - Correction de l'extension de la largeur de la table lorsque l'??l??ment parent a `display : flex`
  - Correction d'un bug qui corrigeait le fait que les colonnes d'une table avec l'emplacement `append` disparaissaient lorsque les donn??es ??taient r??cup??r??es dynamiquement
  - Correction de l'attribut `expand-row-keys` qui ne fonctionnait pas avec la valeur initiale
  - Correction d'une d??faillance du filtre lors de la mise ?? jour de `data`
  - Correction d'une erreur de calcul dans la mise en page des colonnes fixes avec en-t??tes group??s
  - Correction d'un bug dynamique de `max-height`
  - Correction de quelques erreurs de calcul de style

#### Breaking changes
- G??n??ral
  - Suppression de `theme-default`.
  - Compatible avec Vue 2.5.2+ et IE 10+
  - L'??v??nement `change` des composants de formulaire et l'??v??nement `current-current-change` de la pagination ne se d??clenchent plus que lors de l'interaction de l'utilisateur
  - L'attribut `size` de Button et les composants de formulaire acceptent maintenant `medium`, `small` et `mini`
  - Pour faciliter l'utilisation d'ic??nes tierces, les attributs `icon` du bouton et des ??tapes, `prefix-icon` et `suffix-icon` d'Input n??cessitent maintenant un nom de classe complet
- Dialog
  - Suppression de l'attribut `taille`. Maintenant la taille de Dialog peut ??tre configur??e par `width` et `fullscreen`
  - Maintenant la visibilit?? de Dialog ne peut plus ??tre contr??l??e par `v-model`
- Rate
  - Le `text-template` est renomm?? `score-template`
- Dropdown
  - `menu-align` est renomm?? en `placement`. Maintenant il supporte plus de positions
- Transfert
  - le `footer-format` est renomm?? en `format`
- Switch
  - Les attributs commen??ant par `on-**` seront analys??s pour les ??v??nements dans JSX, ce qui rend tous les attributs `on-*` de Switch incapable de fonctionner en JSX. Ainsi, les attributs `on-**` sont renomm??s en `active-*`, et par cons??quent les attributs `off-*` sont renomm??s en `inactive-*`. Cette modification affecte les attributs suivants: `on-icon-class`, `off-icon-class`, `on-text`, `off-text`, `off-text`, `on-color`, `off-color`, `on-value`, `off-value`
  - Les attributs `active-text` et `inactive-text` n'ont plus de valeurs par d??faut
- Tag
  - L'attribut `type` accepte maintenant `success`, `info`, ` warning` et `danger`
- Menu
  - Suppression de l'attribut `theme`. La couleur du menu peut ??tre configur??e en utilisant `background-color`, `text-color` et `active-text-color`
- Input
  - Suppression de l'attribut `icon`. L'ic??ne du suffixe peut maintenant ??tre configur??e ?? l'aide de l'attribut `suffix-icon` ou du slot `suffix-icon`
  - Suppression de l'attribut `on-icon-click` et de l'??v??nement `click`. Maintenant pour ajouter le gestionnaire de clic sur les ic??nes, veuillez utiliser les slots nomm??s
  - L'??v??nement `change` se comporte maintenant comme dans l'input natif, qui ne se d??clenche qu'en cas de blur ou en appuyant sur Entr??e. Si vous avez besoin de r??pondre ?? l'entr??e de l'utilisateur en temps r??el, vous pouvez utiliser l'??v??nement `input`
- Autocomplete
  - Suppression de l'attribut `custom-item`. Le template de suggestions d'entr??e peut maintenant ??tre personnalis?? en utilisant `scoped slot`.
  - Suppression de l'attribut `props`. Vous pouvez maintenant utiliser l'attribut `value-key` pour d??signer le nom de cl?? de l'objet de suggestion d'entr??e pour l'affichage.
- Steps
  - Suppression de l'attribut `center`
  - Maintenant le Steps va remplir son conteneur parent par d??faut
- DatePicker
  - Le param??tre de l'??v??nement `change` de DatePicker est maintenant la valeur li??e elle-m??me. Son format est contr??l?? par `value-format`
- Table
  - Suppression de la prise en charge de la personnalisation du mod??le de colonne ?? l'aide de `inline-template`
  - `sort-method` s'aligne maintenant avec `Array.sort`. Il devrait retourner un nombre au lieu d'un bool??en
  - L'emplacement `append` est d??plac?? ?? l'ext??rieur de l'??l??ment `tbody` pour ??viter les rendus multiples
  - L'??v??nement `expand` est renomm?? en `expand-change`
  - Les param??tres de la m??thode `row-class-name` et `row-style` sont maintenant un objet

##
<i><sup>*</sup> Rendre du HTML arbitraire de fa??on dynamique sur votre site Web peut ??tre tr??s dangereux car cela peut facilement mener ??[des attaques XSS](https://en.wikipedia.org/wiki/Cross-site_scripting). Donc quand `dangerouslyUseHTMLString' est activ??, assurez-vous que le contenu du `message' est fiable, et **ne jamais** assigner `message` au contenu fourni par l'utilisateur.</i>.
