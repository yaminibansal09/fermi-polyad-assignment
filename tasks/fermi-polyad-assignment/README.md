# fermi-polyad-assignment

Assign a gas phase vibrational line list from a quartic force field, or show that the intensities make it impossible.

Science, Chemistry.

`instruction.md` is the prompt the agent gets. `task.toml` is the manifest. The script is `/app/assign/assign.py`. It is called as `python3 /app/assign/assign.py GOAL.json ANSWER.json`. A proved answer names which Fermi terms come out of `x`. A refuted answer names one species whose line intensities are too large to be a mixing of the dipole derivatives.

Sample goals go in `/app/goals/` for writing the script. Grading uses other goals. Only `/app/assign/` is kept.

Python 3.13. License: MIT.
