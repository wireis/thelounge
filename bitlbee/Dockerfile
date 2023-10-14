FROM ezkrg/bitlbee-libpurple:alpine
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 6667
CMD ["ezkrg/bitlbee-libpurple", "run"]