FROM node:10.14-alpine
WORKDIR /app
COPY ["package.json", "./"]
RUN yarn
COPY . ./
EXPOSE 3001
CMD ["yarn", "start"]