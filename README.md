# Reepham College H446 Lesson Hub

Static GitHub Pages lesson hub for OCR A Level Computer Science H446.

The index currently provides 320 flexible one-hour lesson positions: 180 for Year 12 and 140 for Year 13. This is a practical planning approximation at 10 lessons per fortnight, allowing for two weeks of Year 12 work experience and an early Year 13 finish. It is not a claim that OCR's 360 guided learning hours must equal 360 separate classroom lessons.

## Repository structure

- `index.html` — searchable Year 12/Year 13 lesson index.
- `lessons/H446Lessonxxx.html` — standalone classroom lessons.

## Adding a lesson

1. Save the lesson in `lessons/` using the next three-digit filename.
2. Add its title and OCR specification reference to `availableLessons` in `index.html`.
3. Commit and push to the default branch.

## Adjusting a new academic year

Edit the six `count` values for each year in the `programmes` section of `index.html`. Lesson numbering and half-term ranges update automatically.

## GitHub Pages

In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select the default branch and the `/ (root)` folder, then save.
