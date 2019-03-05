# Differences between Angular versions
Angular7 to 2, incremental improvements

#upgrade npm
sudo npm install -g npm@next
VERSION=npm -v

#Install nodejs with npm
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
sudo ln -sf /usr/local/n/versions/node/$VERSION/bin/node /usr/bin/node

# Install Angular CLI
sudo npm install -g @angular/cli@latest 

#Create project with CLI
sudo ng new $PROJECT_NAME
