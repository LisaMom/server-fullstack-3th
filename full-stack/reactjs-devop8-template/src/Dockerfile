
#Dockerfile
#reactjs based on node
#package.json or package-lock.json
#npm install (install node_modual)
#npm run dev => to start the project for new version of node
#npm run build
#npm start (for old version) 

#Fundamental Instruction (Base Image) => 
FROM node:22-alpine

#Configuration Instruction 
WORKDIR /app
COPY package*.json ./
RUN npm install
#copy other file (source code) 
# . . is mean copy all directory 
COPY . . 

CMD ["npm", "start"]
