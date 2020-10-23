
This is how I got the project to build and a dev environement to use it

First up install YARN 

curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list


sudo apt update && sudo apt install yarn


then after in this git project directory just  do this 

yarn 

then 

yarn run build:dev

or yarn run build

