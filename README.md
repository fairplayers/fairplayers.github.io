# fairplayers.github.io

[Hugo](https://gohugo.io) sources for [fairplayers](htt://fairplayers.fr) website.

## Start server

```
$ hugo server
```

Browse to: http://localhost:1313

## Troubleshooting

To fix `failed to extract shortcode` error:

```
$ hugo mod clean
$ hugo mod get -u ./...
```