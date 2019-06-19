# Stresseoke

basically karaoke, but with hilighted stress and such

...current plan is to take the lyrics from https://genius.com/15906894


and display them below an embedded react component showing the youtube video for https://www.youtube.com/watch?v=9CHnHH-kUQ8

---
unanswered questions:

- how can we sync up the lyrics with the spoken words in the song?
(possible approach: https://pub.tik.ee.ethz.ch/students/2017-HS/SA-2017-92.pdf)

- what's the best way to compute the predicted stress patterns for the words? (MVP is probably just using content words, or possibly even two-peaks theory)

- what's the best way to show the words that are stressed (static vs dynamic resizing? animation? bolding?


