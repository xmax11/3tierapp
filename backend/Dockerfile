FROM node:18-slim

WORKDIR /backend

COPY package*.json ./

RUN npm install

COPY /backend ..

EXPOSE 5432

CMD ["npm", "start"]

# --- IGNORE ---
# docker build -t backend .
# docker run -p 3000:3000 backend
# docker run -d -p 3000:3000 backend
# docker ps
# docker stop <container_id>
# docker rm <container_id>
# docker rmi backend
# docker images
# docker system prune -a
# docker logs <container_id>
# docker exec -it <container_id> sh
# docker exec -it <container_id> sh
# npm install -g nodemon
# nodemon server.js
# npm install --save-dev nodemon
# npm install --save-dev dotenv
# npm install express
# npm install mongoose
# npm install cors
# npm install body-parser
# npm install --save-dev eslint
# npm install --save-dev eslint-config-airbnb-base