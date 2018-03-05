Source to image for go. Unfinished.

# Build the image
```
docker build -t go-bi .
```

#Build go-project
```
s2i build <git-repository> go-bi <image-name>
```

