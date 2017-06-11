# Slides

This is the source for my slides. The content is rendered using Gradle and published in the `gh-pages` branch to make slides available on-line.

## Build


```sh
./gradlew clean asciidoctor
```

If you want to have it updated with changes in real-time:

```sh
./gradlew -t asciidoctor
```

To run it locally:

```sh
./gradlew liveReload
```

and open http://localhost:35729 with your browser. It should refresh with any change.

## Deploy

To publish it:

```sh
./gradlew publishGhPages
```

## Credits

This presentation is heavily influenced by the [Melix](https://github.com/melix) slides. The good things you can find here are developed by him, except errors and bugs which are mine.
