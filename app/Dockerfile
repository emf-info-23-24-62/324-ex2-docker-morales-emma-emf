FROM node:lts

COPY /package.json package-lock.json* ./
RUN npm install


COPY server.js ./

ENV PORT=3000
EXPOSE 3000

CMD ["node", "server.js"]
