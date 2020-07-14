# Nekopara
Theme


/* Аниме/Манга/Ранобэ рядом с пунктами истории */
.history-page a:before {
  display: inline-block;
  vertical-align: top;
  width: 72px;
}
.history-page a[href ^= "/a"]:before {
  content: '[Аниме] ';
  color: #34a853;
}
.history-page a[href ^= "/m"]:before {
  content: '[Манга] ';
  color: #9c27b0;
}
.history-page a[href ^= "/r"]:before {
  content: '[Ранобэ] ';
  color: #039be5;
}
[data-locale="en"] .history-page a[href ^= "/a"]:before {
  content: '[Anime] ';
}
[data-locale="en"] .history-page a[href ^= "/m"]:before {
  content: '[Manga] ';
}
[data-locale="en"] .history-page a[href ^= "/r"]:before {
  content: '[Ranobe] ';
}
/* END of Аниме/Манга/Ранобэ рядом с пунктами истории */
