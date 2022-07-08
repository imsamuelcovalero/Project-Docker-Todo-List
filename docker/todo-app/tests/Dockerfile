FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /app
COPY . ./app
ADD node_modules.tar.gz ./app
EXPOSE 3000
CMD ["npm", "test"]

