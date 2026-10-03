# Bite legal pages

Privacy policy and terms for the Bite app, published with GitHub Pages at
https://bite-asia.github.io/legal/

Do not edit these pages by hand. The source is `lib/legal.json` in the
app repo (Bite-Asia/bite). After a change there:

    node scripts/gen-legal.js
    copy docs\privacy.html ..\legal\
    copy docs\terms.html ..\legal\

then commit and push this repo.
