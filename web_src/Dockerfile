FROM repository.anxinyun.cn/base-images/nodejs12:20.10.12.2

COPY . /var/app

WORKDIR /var/app

RUN npm --registry=https://registry.npmmirror.com install

EXPOSE 8080

ENTRYPOINT [ "npm", "start" ]