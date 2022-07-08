FROM node:14-alpine AS todobackend
WORKDIR /app
COPY . ./app
ADD node_modules.tar.gz ./app
EXPOSE 3001
CMD ["npm", "start"]
