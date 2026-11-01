# Adding Week 7 to SETU-AIML-2026/AIML-Evolution

`topic-07-large-language-models`, in the same layout as Week 5:

| Unit | Cards |
|---|---|
| Lecture (2h) | Week 7 Panel Video (the recorded lecture) · Week 7 Lecture Slides · Week 7 Core Booklet |
| Lab at home (1h) | Week 7 Lab Walkthrough Video · Week 7 Lab File (the notebook) · Week 7 Lab (four pages) · Week 7 Form |

## Step 1: three links

| File | Paste |
|---|---|
| `unit-01-lecture/panelvideo/videoid` | The YouTube ID of your recorded lecture |
| `unit-02-lab/panelvideo/videoid` | The YouTube ID of Week7_Walkthrough_and_Wrap-up.mp4 once uploaded |
| `unit-02-lab/web-03-week7-form/weburl` | The link to the Week 7 form (from Form_07_Your_Law, via Quick import) |

A YouTube ID is the part after `v=` in the video's address, for example `y_YFt4JVNeM`.

## Step 2: add it

```bash
cd AIML-Evolution
git pull
git am /path/to/week7-large-language-models.patch
# edit the three files above, then:
git commit -am "Week 7: videos and form link"
```

Or copy the `topic-07-large-language-models` folder into the repository, then `git add`, `git commit`.

## Step 3: build and push

```bash
deno run -A jsr:@tutors/tutors
git add -A && git commit -m "Rebuild Tutors json" && git push
```

## Uploading the video to YouTube

1. Upload `Week7_Walkthrough_and_Wrap-up.mp4`; title: *Week 7 · Your Law and Its Answer Sheet: lab walkthrough and wrap-up*.
2. Paste `Week7_YouTube_description.txt` as the description. Its timestamps become chapters automatically.
3. Under Subtitles, upload `Week7_Walkthrough_and_Wrap-up.srt` (English).
4. Copy the video's ID into `unit-02-lab/panelvideo/videoid`.
