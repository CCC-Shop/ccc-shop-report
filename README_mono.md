# ccc-shop-backend

Backend for online shopping system **CCC Shop** of database systems course.

## How to Run ?

### Install Mariadb

[Download mariadb](https://mariadb.org/download/?t=mariadb&p=mariadb&r=10.6.5&os=windows&cpu=x86_64&pkg=msi&m=blendbyte) and set username and password to root

or you can run mariadb with docker
```cmd
docker run --name mariadb -p 3306:3306 -e MARIADB_USER=root MARIADB_ROOT_PASSWORD=root -v /data/mariadb/data:/var/lib/mysql -d mariadb
```

### Create database and add initial value

run `create_table.sql` and `initial_value.sql`  under `src/query` in your database

### Install IntelliJ IDEA

[Download Path](https://www.jetbrains.com/idea/)

#### Open project with IntelliJ IDEA

![](https://i.imgur.com/hvHsQIY.png)


#### Add project SDK

- Add openjdk-17 in "File -> Project Structure"
![](https://i.imgur.com/X9ra1n7.png)
![](https://i.imgur.com/BuwKjCI.png)

#### Run application

- Right click on `CccShopApplication`
- Run `CccShopApplication` \
![](https://i.imgur.com/7bFJes3.png)


### Done!

# ccc-shop-frontend

## Project Setup

### Install Node.js [here](https://nodejs.org/en/) for Windows or install by running:

```shell=
# macOS
brew install node
# linux
sudo apt install nodejs
```

### Install Yarn
```
npm install --global yarn
yarn --version
```
## How to run
### Install project dependencies
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Done!

# Demo video for different scenario
<img src="https://i.imgur.com/RMupxMP.png" width="30%"> \

youtube channel: [https://www.youtube.com/playlist?list=PLuIs3VbIw0SmLry-_GpOQhUIGmaYZIKfI](https://www.youtube.com/playlist?list=PLuIs3VbIw0SmLry-_GpOQhUIGmaYZIKfI)

visitor scenario: [https://youtu.be/_eldVc57jGM](https://youtu.be/_eldVc57jGM)

customer scenario: [https://youtu.be/QkzACw5h_xQ](https://youtu.be/QkzACw5h_xQ)

staff scenario: [https://youtu.be/pY14iRMhgj4](https://youtu.be/pY14iRMhgj4)

admin scenario: [https://youtu.be/El9QJEijaSo](https://youtu.be/El9QJEijaSo)