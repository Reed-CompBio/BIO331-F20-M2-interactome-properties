# Module 2: Interactome Properties

In this homework, you will first implement network measures, then compare these measures across different yeast interactomes, and finally compare these measures across interactomes from yeast, human, and fly.

* **Assignment Out:** Monday, Sept 14
* **Assignment Due:** Monday, Sept 28
* **Suggested Deadlines:**  Note that the Written Assignment asks you to compare interactomes and provide figures.

:arrow_right: Friday, Sept 18 -- implement most of the network measures

:arrow_right: Monday, Sept 21 -- compare measures across yeast interactomes

:arrow_right: Thursday, Sept 24 -- compare measures across yeast, human, and fly

## :star: **Task A**: Software Preliminaries: `matplotlib`

`Matplotlib` is a plotting and visualization library for Python.  The `plot_graph.py` file contains a single function, which plots some numbers.  To see if you have it installed on your machine, try running `plot_graph.py`.  If it is not installed, try installing it in the same way you installed `graphspace_python`.  For example, you can open a Terminal (Mac) or Anaconda Command Prompt (for those using Anaconda as the package manager) and type:

```
pip install matplotlib
```

Remember you can preface the command with `sudo` if you get permissions errors.  Ask Anna if you have issues installing `matplotlib`.  

When you run `plot_graph.py`, a new file, `numbers.png` is created in the same directory in which you are running the code.  Opening this file shows a two-panel figure with one red curve and one blue curve.  Find the place in `plot_graph.py` where you can modify the colors, line styles, and markers.  A subset of the [colors](https://matplotlib.org/3.1.0/gallery/color/named_colors.html), [marker styles](https://matplotlib.org/3.3.1/api/markers_api.html), [line styles](https://matplotlib.org/3.2.1/gallery/lines_bars_and_markers/linestyles.html), for the `plot()` function are below.  They are passed as a single string, e.g., `'ro-'` is a red line with circle markers.  Order does not matter.

| Colors | Line Styles | Line Markers |
| -- | -- | -- |
| `r` - red | `-` - solid | o - circle|
| `g` - green | `- -` - dashed | `.` - point |
| `b` - blue | `-.` - dash-dot | `s` - square |
| `y` - yellow | `:` - dotted | `+` - plus |
| `m` - magenta | | `x` - x marker |
| `c` - cyan |  | `d` - diamond |
| `k` - black |  | `*` - star|

## :star: **Task B**: Calculate and Plot Degree Distribution

For Tasks B-E, work with the provided `example_graph.txt`.  

## :star: **Task C**: Calculate and Plot Average Neighbor Degree

## :star: **Task D**: Calculate and Plot Clustering Coefficient

## :star: **Task E**: Calculate and Plot Path Length Distribution

## :star: **Task F**: Compare Measures Across Yeast interactomes

## :star: **Task G**: Compare Measures Across Yeast, Human, and Fly interactomes

## Submitting

:star2: **You're Done with Tasks A-G!** You just need to submit your python code (not the networks).  Before you submit `run.py` via Moodle, look through the comments and add any additional ones that explain what your code does.  Code organization and clarity will contribute few points in grading.

### Instructions for resubmitting

As described on the [syllabus](https://www.reed.edu/biology/courses/bio331/files/syllabus.pdf), there is no penalty for re-submitting this assignment as long as you follow the instructions below. All resubmissions are due by Finals Week - ask Anna if you have any questions.

* You submit whatever you have by the deadline.
* You add a comment to the top of your code indicating that you plan to resubmit this assignment (e.g. "I plan to resubmit this assignment.")
* You schedule a meeting with Anna within one week of the deadline to make a plan.
