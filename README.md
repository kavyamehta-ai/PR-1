# Expectation Decider

A probability and statistics project that explores synthetic student data to study patterns associated with passing a competitive mathematics exam.

## Project contents
- `student_data.csv` — reproducible sample dataset of 200 students.
- `expectation_decider.ipynb` — step-by-step practical analysis with formulas, tables, plots, and interpretations.
- `requirements.txt` — Python dependencies.
- `report/` — place your handwritten theory PDF here before submission.

## Dataset fields
- `study_hours`: study hours per week
- `attendance`: lecture attendance percentage
- `group_discussion`: participation (`Yes`/`No`)
- `previous_test_score`: previous internal test score out of 100
- `final_exam_pass`: outcome (`Pass`/`Fail`)

## Run locally
1. Install Python 3.10 or newer.
2. Create and activate a virtual environment (optional but recommended).
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open `expectation_decider.ipynb` and run cells from top to bottom.

## Important notes
- The data is synthetic and is intended for learning; it is not real student data.
- Random outcomes are generated using a fixed seed so the CSV is reproducible from the generation cell in the notebook.
- The probability distribution for the number of passes among 3 students uses the hypergeometric model, which matches sampling 3 students without replacement from this finite dataset.
- The Bayes theorem question uses the percentages supplied in the assignment, separately from the synthetic dataset. Its assumptions imply an overall pass probability of 2/3 and a pass probability of 7/9 given high attendance.
- Observed associations in this synthetic dataset do not establish causation.

## Submission checklist
- [ ] Run every notebook cell and save the executed notebook.
- [ ] Add your handwritten theory PDF to `report/`.
- [ ] Record a 5–10 minute face-and-screen explanation.
- [ ] Add the shareable video URL below.
- [ ] Push the complete project to a public GitHub repository.

## Video explanation
Add your Google Drive or unlisted YouTube link here: `PASTE_VIDEO_LINK_HERE`
