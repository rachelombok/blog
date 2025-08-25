# Rachel Ombok's Personal Blog

Rachel Ombok's personal blog powered by [Hugo](https://gohugo.io/).
[blog site](https://blog.rachelombok.com)

## Requirements

The following item is required to run this blog:

* [Hugo](https://gohugo.io/)

## Installation

### 1. Clone the Repository

Run the following command to clone this repository into your computer:

```shell
$ git clone git@github.com:rachelombok/blog.git
```

### 2. Run the Blog 🎉

Type the following command to start the Hugo server:

```shell
$ hugo server -D
```

It will start the development server. You can visit the blog at: [localhost:1313](http://localhost:1313/).

To build the blog for production, run the following command:

```shell
$ hugo -D
```

To add a new blog post;
```shell
$ hugo new /blog/[blog-title]/index.md
```
And then to build it for production;
```shell
$ hugo -D
```

The static files will be generated at the `public` directory.

## License

MIT © [Risan Bagja Pradana](https://risanb.com)