FROM nodered/node-red:3.1-debian

# Copy package.json to the WORKDIR so npm builds all
# of your added nodes modules for Node-RED
WORKDIR /data

COPY package.json /data/package.json
RUN npm install
WORKDIR /usr/src/node-red