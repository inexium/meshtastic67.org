# alsamesh.org

![screenshot](readme-image.webp)

## Description
This static website page aims at promoting Meshtastic community in Alsace.
You can join our Discord using this link :
<a href="https://discord.gg/aRYWN5HwFU">Discord</a>

## Development commands
```sh
git clone PROJECT
cd alsamesh.org

bun install
bun dev
```

## Docker
```sh
cd alsamesh.org
docker build -t alsamesh.org .

docker run -it --rm -p 4321:4321 alsamesh.org
```

## Adding Hardware
edit /src/content/equipments.md
<br>
put corresponding image in /src/assets/content-images
