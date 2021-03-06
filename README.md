# Audible-Text-Editor-Final
An Automated Sinhala Text editor for Visually Impaired and Blind Students

Installation

Pre-requisites

NodeJS 6.X or higher
Festival Speech Synthesis System: 2.4 or higher
  
  Setup Node.js
  Install Node.js

    $ curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
    $ sudo apt-get install -y nodejs

  Setup Festival
  Install Festival

    $ sudo apt-get update
    $ sudo apt-get install festival

  Setup Sinhala Language

    $ wget http://ucsc.lk/ltrl/public/TTS/003-23-01-2007.zip sinhala.zip
    $ sudo unzip sinhala.zip -d /usr/share/festival/voices

  Setup ATE
  Clone the repository

    $ git clone https://github.com/QuarkLabs/audible-text-editor-master.git

  Install Angular-cli

    $ sudo npm install -g @angular/cli
  
  Install dependencies with

    $ cd audible-text-editor
    $ npm install

  Build the Angular App

    $ ng build --prod

  Start Server

    $ npm start
