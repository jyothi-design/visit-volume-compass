# Visit Volume Compass

Project 7: Hospital Patient Data Analysis System

Difficulty: Intermediate

Objective: Analyze de-identified or synthetic hospital visit records to understand patient volumes, department-wise workload, and visit trends.

Scope and boundaries: Educational operational analytics only. Avoid unnecessary personal information; do not produce diagnoses or treatment recommendations.

Suggested features:

Maintain synthetic patient and appointment records

Record visit date and department

Summarize daily/monthly visits and department workload

Analyze age bands using non-identifying aggregated data

Generate patient-visit charts and reports

Suggested MySQL entities/tables: patients(patient_id, age_band, gender_optional); departments(department_id, department_name); visits(visit_id, patient_id, department_id, visit_date, visit_type)

Data analysis and visualization: Pandas grouped visit analysis; NumPy summary statistics; Matplotlib department and monthly visit charts.

Expected outputs: Department-wise workload report, visit trends, age-band summary, and aggregated charts.

Acceptance criteria: Use synthetic/de-identified data; restrict access to records; report aggregates only; label all results as operational statistics, not clinical advice.

This project was built with [Lovable](https://lovable.dev).

**Live app**:  https://visit-volume-compass-public.vercel.app/

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/2928255b-afb6-4118-a177-743e4f8ce723).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
