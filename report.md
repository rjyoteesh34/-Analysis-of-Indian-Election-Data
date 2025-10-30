# Rixi Lab - Final Project: Analysis of Indian Election Data
Generated project contents and sample analysis.

## Summary
- This project contains exploratory analysis on Vidhan Sabha and Lok Sabha datasets uploaded by the user.
- The analysis includes candidate demographics, average candidates per seat, turnout trends, and top parties by seats/votes where possible.

## Figures included (in `figures/`):
- vidhan_candidate_gender.png
- vidhan_avg_candidates_per_seat.png

## Sample Findings (automatically generated)
- Vidhan Sabha dataset: 327294 candidate records. Years present: [1977.0, 1978.0, 1979.0, 1980.0, 1982.0, 1983.0, 1984.0, 1985.0, 1987.0, 1989.0, 1990.0, 1991.0, 1992.0, 1993.0, 1994.0, 1995.0, 1996.0, 1997.0, 1998.0, 1999.0, 2000.0, 2001.0, 2002.0, 2003.0, 2004.0, 2005.0, 2005.1, 2006.0, 2007.0, 2008.0, 2009.0, 2010.0, 2011.0, 2012.0, 2013.0, 2014.0, 2015.0]
- Lok Sabha dataset: 73081 candidate records. Years present: [1977, 1980, 1984, 1989, 1991, 1996, 1998, 1999, 2004, 2009, 2014]

## How this was generated
- A python script performed basic cleaning (normalize party names, fill missing genders) and generated the figures saved in `figures/`

## Next steps / Recommended analyses
- Compute vote-share vs seat-share disproportionality metrics (Gini, Gallagher index).
- Produce a winner timeline for states like Uttar Pradesh and perform margin analysis.
- Build an interactive Streamlit or Dash dashboard for exploration.