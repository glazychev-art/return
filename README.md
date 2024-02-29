# Intro

This application does nothing, just return.
Can be used in containers on different platforms.

# Build
```
docker buildx build --platform linux/amd64,linux/arm64 -t <NAMESPACE>/return . --push
```
