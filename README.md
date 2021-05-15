# Configurations for test container ruby

1. Build this image
```
docker build -t <your-image-name-ruby>
```
2. Run the container with shell
```
docker run --rm -it <your-image-name-ruby> sh
```
3. Execute any scripts in ruby!
```
ruby <script.rb>
```
