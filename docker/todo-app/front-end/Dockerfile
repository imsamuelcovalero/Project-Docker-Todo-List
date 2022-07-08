FROM node:14-alpine AS todofrontend
WORKDIR /
COPY . ./
ADD node_modules.tar.gz ./
EXPOSE 3000
CMD ["npm", "start"]

