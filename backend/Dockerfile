FROM node:20
WORKDIR /user/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV PORT 8080
ENV MODEL_URL=https://storage.cloud.google.com/testsorage/submissions-model/model.json
EXPOSE 8080
CMD [ "npm", "run", "start"]