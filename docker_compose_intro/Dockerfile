FROM node:alpine

# Create app directory
WORKDIR D:\Alberto\Estudio\Inesdi-Full Stack Developer\2. Curso Nivelador\2. Actividad\Actividad

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

# Bind your app to port 8080
EXPOSE 8080

# CMD [ "node", "server.js" ]
CMD [ "node", "server_solution.js" ]