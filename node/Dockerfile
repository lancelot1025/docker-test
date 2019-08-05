FROM node:lts

RUN npm install -g cnpm --registry=https://registry.npm.taobao.org \
    && npm install -g yarn \
    && yarn --version \
    # &&  yarn global add react \
    # &&  react -v \
    && yarn global add create-react-app \
    && yarn global add @vue/cli \
    && vue --version

# CMD /bin/bash
# CMD ["/usr/local/bin/vue", "ui", "--host 0.0.0.0", "--port 4567", "--quiet", "--headless"]
# CMD ["vue", "ui", "--host=0.0.0.0", "--port=4567", "--quiet", "--headless"]