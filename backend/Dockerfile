FROM node:14.16.1-alpine3.13
WORKDIR /api
COPY backend/package*.json ./
RUN npm install
COPY backend ./
ENV NAME=subin
EXPOSE 5000
CMD ["npm","start"]

