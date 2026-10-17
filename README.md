# Almirah – all source code

app/                    The Almirah app (v1.1). Single file: open index.html. README.md inside explains running it.
concept-demo/           First 62-second concept story (almirah-demo.html), its debug build, and the usage/roadmap notes.
tests/                  Python + Playwright test scripts used to check the app (scan parsing, duplicates, reminders with a
                        simulated clock, camera-blocked fallback). Paths inside point to the sandbox; edit file paths and run:
                        pip install playwright && playwright install chromium && python3 t3.py
guide-and-video-tools/  Scripts that made the screenshots, walkthrough video and the product-guide PDF
                        (capture.py, make_assets.py, build_pdf.py, guide.html, strip.html). Need ffmpeg and Playwright.

Almirah is an inventory and reminder helper, not medical advice.
