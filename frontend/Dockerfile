FROM node:14.16.1-alpine3.13
RUN addgroup app && adduser -S -G app app
USER app
WORKDIR /app
COPY frontend/package*.json ./
RUN npm install
COPY frontend ./
ENV NAME=subin
EXPOSE 3000
CMD ["npm","start"]

