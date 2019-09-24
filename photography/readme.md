# Phtography Portfolio

morgify -auto-orient --resize 1200x1200 *.jpg

Run this command and pipe into clipboard (`clip.exe`) to generate links to all pictures.
```bash
ls *.jpg | sed -E 's/(.*)/<a href=".\/full\/\1"> <img src=".\/\1"><\/a>/g'
```
