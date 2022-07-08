FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /
COPY . ./
ADD node_modules.tar.gz ./
EXPOSE 3000
CMD ["npm", "test"]

