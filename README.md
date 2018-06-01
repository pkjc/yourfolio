# Yourfolio
Super simple and responsive theme for your personal website on Hugo framework.

## Installation
Before start you already need to have a Hugo on your machine. You can install it by following [these instructions](https://gohugo.io/getting-started/installing/)

Create the Hugo website template if you are starting from scratch:

```
$ hugo new site your-site-name
```

Inside the folder of your Hugo website run:

```
$ cd themes
$ git clone https://github.com/serg/yourfolio.git
```

For more information read the official [setup guide](https://gohugo.io/themes/installing-and-using-themes/) of the Hugo themes.

## Getting started
Set the theme option in your `config.yaml` for using this theme:
```
...
theme: yourfolio
...
```
Also you can copy a whole `config.yaml` file into your website folder and change it for fitting your requirements.

As example please see on the `exampleSite` folder inside the theme folder for how to configure a website and create content files.

## Check the website
Start a Hugo development server on your local machine inside your website folder:
```
$ hugo server
```
Your website will be available in browser by this path `localhost:1313`
