    1  apt-get update
    2  apt-get install curl -y
    3  curl -sL https://deb.nodesource.com/setup_10.x | bash
    4  apt-get install nodejs -y
    5  mkdir node-app
    6  cd node-app/
    7  echo 'console.log("nodejsapp from ubuntu...");' > index.js
    8  history