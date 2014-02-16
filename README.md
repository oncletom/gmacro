# gmacro


> GraphicsMagic macros for my personal needs. Contains additional sugar to ease my work.

# Install

```bash
npm install -g oncletom/gmacro
```

# Usage

```bash
gmacro [task] [options]
```

# Tasks

## `gmacro list`

List available tasks.

## `gmacro everyday`

A port of the following bash command:

```bash
gm convert +dither -delay 15 -loop 1 *.jpg -colors 128  -resize 500x500 ../$(basename `pwd`).gif
```

## `gmacro xyz -i [image_pattern*] -o [image_string]`

A port of the following bash command:

```bash
montage -tile 3 -geometry 4167x2773+20+20 DSC_8475.jpg DSC_8474.jpg DSC_8473.jpg lighthouse.jpg
```

With those additions:

- automatic geometry resolution
- equal border calculation
