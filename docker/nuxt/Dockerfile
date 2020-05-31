FROM node

RUN mkdir -p /nuxt
COPY . /nuxt
WORKDIR /nuxt

RUN npm update && \
    yarn global add nuxt && \
    yarn global add vue-cli

ENV HOST 0.0.0.0
EXPOSE 3000
CMD ["yarn", "start"]