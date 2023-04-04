FROM node:alpine
WORKDIR /nodeapp
COPY package.json .
RUN npm install
COPY . .
CMD ["npm","start"]



# docker build -t minhmt/myexpress-app .
# docker push minhmt/myexpress-app