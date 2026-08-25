# The Evolution of Machine Learning and AI

This repository contains a minimal Tutors course for the 5 ECTS module "The Evolution of Machine Learning and AI" taught by Indrakshi Dey.

## Image sources

The course, topic, and talk artwork were sourced from free Unsplash imagery:
- Course: https://images.unsplash.com/photo-1518770660439-4636190af475
- Topic: https://images.unsplash.com/photo-1526379095098-d400fd0bf935
- Talk: https://images.unsplash.com/photo-1531482615713-2afd69097998

## Build the Tutors course

```bash
deno run -A jsr:@tutors/tutors
```

This generates the `json` output folder for publishing.

## Build a local static version

```bash
deno run -A jsr:@tutors/tutors-lite
```

This generates an `html` folder that can be opened locally for quick browsing.
