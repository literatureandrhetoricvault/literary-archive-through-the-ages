# The Literary Archive — Through the Ages (Build 4)

GitHub Pages package. Upload `index.html`, `.nojekyll`, and this README to the root of the repository.

Build 4 performance improvements:
- Chamber III passage is rendered once and reused across all 10 questions.
- Repeated question transitions no longer re-run the full-screen blur animation.
- Background parallax and particles are reduced during the heaviest reading/question screens.
- Passage HTML is cached for all chambers.
