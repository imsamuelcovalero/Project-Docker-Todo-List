FROM node:14-alpine AS todofrontend
WORKDIR /app
COPY . ./app
ADD node_modules.tar.gz ./app
EXPOSE 3000
CMD ["npm", "start"]

