# My Awesome Tools

<center> <img src="./img/awesome.svg" alt="awesome-list" style="max-height: 200px"> </center>

Repositori ini dibuat untuk mendokumentasikan berbagai tools yang saya gunakakan untuk menunjang produktifitas dalam menulis code.

## Another Language
- [English](./lang/README-EN.md)

## Table of Contents
1. [Text Editor](#text-editor)
2. [Plugins](#plugins)
    - [Live Server](#live-server)
    - [Material Icon Theme](#material-icon-theme)
    - [Material Color Theme](#material-color-theme)
    - [Gitlens](#gitlens)
    - [Code Snippets](#code-snippets)
    - [Language Support](#language-support)
3. [Font](#font)
4. [Browser](#browser)
5. [Browser Extension](#browser-extension)
6. [Website Documentation](#web-documentation)
7. [Framework](#framework)

## Text Editor

Untuk text editor, saya menggunakan **Visual Studio Code** atau **vscode**. Berikut beberapa alasan mengapa menggunakan visual studio code.

- Gratis dan open source!
- Tersedia banyak _plugins_ yang selalu diupdate.
- Tersedia banyak _theme_ dan sangat ringan!

Download disini: https://code.visualstudio.com/ 
Link Github: https://github.com/Microsoft/vscode

![Microsoft Visual Studio Code](https://cloud.githubusercontent.com/assets/11839736/16642200/6624dde0-43bd-11e6-8595-c81885ba0dc2.png)

## Plugins

Saya sendiri berfokus pada pemrograman berbasis web. Berikut beberapa _plugins_ keren yang biasa saya gunakan.

### Live Server

Pernah bikin static template hanya html dan css saja? biasanya agar bisa jalan ditaruh di folder `htdocs` apache kan? Nah plugins **Live Server** ini digunanakan untuk menajalankan file html dan css tadi melalui folder project dengan membuat server local baru. Secara default akan membuat server di `localhost:5050`.

Install plugins:
```
ext install ritwickdey.LiveServer
```

![Live Server](https://github.com/ritwickdey/vscode-live-server/raw/master/images/Screenshot/vscode-live-server-explorer-menu-demo-1.gif)

### Material Icon Theme

Bosen dengan icon dari folder project vscode? cobain deh **Material Icon Theme** agar icon file serta foldermu menjadi lebih berwarna dan bagus!

Install plugins:
```
ext install PKief.material-icon-theme
```

![Material Icon Theme](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/fileIcons.png)

### Material Color Theme

Kalau yang sebelumnya ubah icon biar lebih menarik, nah ini bikin editor kamu lebih menarik dan nyaman ketika proses coding. Ada beberapa tema yang bisa dipilih dimulai dari yang dark sampai ligh. Rekomended banget deh.

Install plugins:
```
ext install Equinusocio.vsc-material-theme
```

![Material Icon Theme](https://i.imgur.com/qvxc7OA.jpg)

### GitLens

Peran git dalam proses development software udah kayak nasi dengan lauk! penting banget agar lebih nikmat :D Nah jika pakai plugins GitLens ini, proses versioning project jadi lebih mudah lagi dan jauh lebih produktif lagi. Fiitur favorit saya adalah, fitur popup mengenai informasi seputar _siapa yang commit? logsnya yang mana? kapan?_

Install plugins:
```
ext install eamodio.gitlens
```

![Gitlens](https://raw.githubusercontent.com/eamodio/vscode-gitlens/master/images/gitlens-preview.gif)

### Code Snippets

Di era modern dan serba cepat ini diperlukan berbagai tools snippets untuk bahasa pemrograman tertentu agar proses coding menjadi lebih cepat dan effisien. Jadi cocok banget kamu untuk install code snippets di text editor. Berikut beberapa code spippets yang saya gunakan.

-  ES7 React/Redux/GraphQL/React-Native => untuk pengguna react => `ext install dsznajder.es7-react-js-snippets`
- Vetur => untuk pengguna VueJS => `ext install octref.vetur`
- Javascript (ES6) Code Snippets => untuk pengguna JS => `ext install xabikos.JavaScriptSnippets`

Dan lain sebagainya, kamu bisa cari sendiri di market place sesuai dengan bahasa pemrograman yang digunakan.

### Language Support

Language Support ini hampir mirip dengan Code Snippets, biasanya satu paket. Jadi beberapa bahasa yang baru-baru seperti `stylus`, `go`, `solidity` itu tidak disupport secara default, maka perlu di install sendiri agar snippet serta syntax highlighting bisa muncul di text editor.

### Keybindings

Kalau saya dulunya pakai PHPStrorm serta WebStorm dan terbiasa dengan shortcut - shortcut yang ada di product jetbrains tersebut. Nah dari pada saya belajar lagi mengenai shortcuts yang ada di vscode, mending saya install saja keybindings nya. Jadi vscode serasa PHPStorm atau WebStorm :D

Install plugins: 
```
ext install k--kato.intellij-idea-keybindings
```

## Font

Bagi saya, pemilihan font dalam code sangat penting, apalagi yang bisa support berbagai hal seperti tanda panah dan karakter - karakter khusus. Nah agar font menjadi keren, saya rekomendasikan pakai Fira Code. 

![Fira Code](https://camo.githubusercontent.com/3a8948f34284f378ead7af5846aa432035c687ad/687474703a2f2f732e746f6e736b792e6d652f696d67732f666972615f636f64655f6c6f676f2e737667)

Cara installnya bisa dilihat di https://github.com/tonsky/FiraCode

## Browser

Saya merekomendasikan untuk menggunakan Google Chrome atau Mozilla Firefox Developer Edition. Karena kedua browser tersebut memiliki Dev Tools yang sangat lengkap. Baik debugging dan lain sebagainya.

- Google Chrome => https://www.google.com/chrome/
- Firefox Quantum Developer Edition => https://www.mozilla.org/en-US/firefox/developer/

## Browser Extension

Untuk browser extension, saya menggunakan beberapa tools keren antara lain:

1. Wappalyzer => untuk analisis stack apa yang digunakan oleh website yang dibuka. => https://www.wappalyzer.com/
2. JSON Viewer => untuk melihat data JSON yang diformat melalui browser => https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh
3. React Developer Tools => untuk melihat state proses saat development web dengan framework React => https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi
4. Redux Devtools => untuk lihat state managent saat proses developent menggunakan redux => https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd
5. Vue Devtools => vue programmer harus punya! => https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd
6. Google Translate => bisa translate langsung ketika select text di browser (gak harus buka translate.google.com) => https://chrome.google.com/webstore/detail/google-translate/aapbdbdomjkkjkaonfhkkikfgjllcleb
7. Google Calender => Cek jadwal, event dan lain sebagainya langsung dari ekstension => https://chrome.google.com/webstore/detail/google-calendar/gmbgaklkmjakoegficnlkhebmhkjfich
8. Adblock Plus => Blokir iklan gak jelas! => https://chrome.google.com/webstore/detail/adblock-plus/cfhdojbkjhnklbpkdaibdccddilifddb
9. MetaMask => mempermudah inject web3 untuk development Ethereum Network => https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn

## Website Documentation

- Search by Duckduckgo! => https://duckduckgo.com/?q=indra+kusuma&atb=v133-1_i&ia=web
- Mozilla Developer Network => https://developer.mozilla.org/en-US/
- W3Schools => https://www.w3schools.com/
- Freecodecamp => http://freecodecamp.org
- berbagai official web documentation

## Framework

Sayaa rasa penting untuk menuliskan beberapa framework yang saya pakai dalam development web saat ini. Dan berikut daftar framework yang saat pakai saat ini.

### ReactJS

Pasti kalian tidak asing dengan framework [ReactJS](https://reactjs.org). Framework open source bikinan tim Facebook ini sukses menjadi framework pilihan utama para web developer didunia begitu juga di tempat kerja saya saat ini, Tokopedia. Tokopedia menjadikan ReactJs sebagai framework utama dalam mengembangkan web platform tokopedia.

## VueJS

Konfigurasi dan *learning curve* yang rendah menjadikan framework [VueJS](https://vuejs.org/) populer dalam waktu yang singkat. Sampai saat ini saya masih menggunakan vueJS dalam mengembangkan beberapa project web. jadi framework ini sangat cocok bagi kalian yang baru menggunakan framework JavaScript.

## Enzyme

Salah satu tools bikinan AirBnB untuk unit testing react, [Enzyme](https://airbnb.io/enzyme/) menjadi pilihan saya. Mudah dalam hal setup dan gampang dalam bikin test menjadikan enzyme favorit saya.

sample projectnya di : https://github.com/idindrakusuma/react-unit-test-with-jest-and-enzyme/tree/master/src