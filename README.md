# Graph Summit APAC 2023 Workshop

Hands-on workshop materials for Graph Summit APAC 2023 sessions in Sydney, Melbourne, and Singapore. The workshop introduces Neo4j Graph Data Science workflows using fraud-style transaction data, Cypher exercises, notebooks, and Bloom visualization assets.

## What Is Included

- Main workshop notebook for Neo4j Graph Data Science
- Training notebooks for guided sessions
- PaySim-style transaction CSV data
- Cypher scripts for graph loading and analysis
- Neo4j Bloom perspective JSON
- Workshop slides and screenshots

## Repository Structure

```text
.
├── GDS_Workshop.ipynb
├── trainings/
│   ├── Training_session_1.ipynb
│   ├── Training_session_2.ipynb
│   └── Training_session_3.ipynb
├── data/                   # Transaction and client CSV files
├── cypher/                 # Workshop Cypher and GDS commands
├── bloom/                  # Bloom perspective
├── script/                 # PaySim config and helper scripts
├── slides/
└── img/
```

## Getting Started

Open `GDS_Workshop.ipynb` to begin the main workshop.

You can run the exercises with one of the Neo4j environments used in the original workshop:

- Neo4j Desktop
- Neo4j Sandbox
- Neo4j Aura

## Suggested Workflow

1. Load the CSV data from `data/`
2. Use the scripts in `cypher/` to create the graph model
3. Run the Graph Data Science exercises in the notebooks
4. Explore the graph visually with the Bloom perspective in `bloom/`
5. Use the screenshots in `img/` as reference outputs

## Notes

The data and notebooks are designed for a 90-minute instructor-led session. If running independently, start with the main notebook, then use the training notebooks for deeper practice.
