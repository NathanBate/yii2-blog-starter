# Personal Project: Base Blog Starter App

This was a personal project that I did for a friend and it has a narrow
application. As with an personal project, it never gets enough love as it should. I have
yii2 projects that are in production, but they cannot be a public repo.

# Base Blog Starter App

Starter project which uses the scaffolding of the [Base Blog 
Core PHP Dependency](https://github.com/NathanBate/yii2-base-blog)
to provide ready-made user management and templates.

## Installation

```shell
composer create-project nateatnts/blog-starter project-name
```

Then, go to the root project:
```shell
cd project-name
```
or whatever directory name you created.

Next, create your environment file:
```shell
cp .env.example .env
```
Open up that file in your editor of choice.  Fill in the site 
address, site name, and the database information.

Then you need to run the installation program.  
```shell
./console install
```

Next, run npm install.
```shell
npm install
```


