# amilinweb-bootstrap

# DOCOMENTATION

# STEP 1 - Preperation project structures 
    - build project by name amilinweb with bootsrtarp and sass
    - create file index.html, folder css and js. 
        - file in css folder : styles.scss 
        - file in js folder  : scripts.js
    - file with type scss can be styles.css use extension "Watch Sass".

# STEP 2 - HAPPY CODING !!! 
    # CONTENTS OF HTML
        - Buat link untuk css, bootstrap, dan javascirp link untuk botstrap ada 2 yaitu css dan js (see documentation) position of link and top title in tag <head>.
        - We used bootstrap version 4.5x
        - Dalam body, saya bagi menjadi 3 bagian besar yaitu <header>, <main> dan <footer> sesuai semantic html 5. 
        - Terkait penamaan class ada yang sama dengan bootstrap

    # <header>
        - Dalam <header> saya akan meberikan <section> dengan class : color-section da id : title, jadi terdapat class yag bukan bawaan dari bootsrtap. 
        Hal ini dilakukan agar nanti saya bisa memodifikasi dengan sass. 
        - dan dalam <section> saya akan memberikan 1 buah <div> dengan class : container-fluid
        - dalam <div class="container-fluid"> terdapat tag <nav> untuk membuat navigation dan <div> untuk title 
        - <div> yang didalam  <div class="container-fluid"> kita beri class : row.
        classname ini dari bootstrp ya

    # <main>