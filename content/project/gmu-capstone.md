+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Team Organization for Senior Softball"

# Project summary to display on homepage.
summary = "Optimizing team selection through goal programming."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "softball-field.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["operations-research", "GMU", "statistics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

The teams in the Northern Virginia Senior Softball (NVSS) league are reorganized every year with the desire to make them as even as possible and promote social interactions. This project’s goals were to develop a methodology to produce team assignments for players such that the teams are equal in regards to player ability and other attributes. Multiple regression was employed to obtain offensive, defensive, and team metrics. An integer program (IP) model was developed where constraints were aligned with the goals of the NVSS league to solve the assignment problem. The IP model was linked to a team assignment tool which allows the user to select settings and parameters before running the model.