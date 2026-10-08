# Two-Sample t-Test Lab (BIOL 200)

An interactive, browser-based version of the Student's t-Test activity, built to go with the Two-Sample t-Test lecture. Students compare two groups step by step, using real biology examples (lizard tail lengths, tree frog body mass, red-winged blackbird antibodies). The app checks their answers as they go.

**Live site:** https://lizferguson5.github.io/t-test/
(If you name the repository something else, the link becomes `https://lizferguson5.github.io/REPO-NAME/`.)

## What's inside

Nine tabs, meant to be worked through in order. Each tab ends with a short **Try this** list that matches the Canvas questions.

| Tab | Topic | What students do |
|---|---|---|
| 1 | Which t-test? | Sort study designs into independent vs. paired; walk through the lecture's 2-sample flowchart; review the six steps of a t-test. |
| 2 | Signal vs. noise | Use sliders to change the difference, spread and n of two groups and watch t, the rejection region and p update. |
| 3 | Worked example: lizards | Reveal the worksheet's Example 1 one step at a time, with deviation tables and the t-table lookup. |
| 4 | Your turn: frogs | Example 2, with self-checking answer boxes for every step and a conclusion builder. The data can be edited or replaced. |
| 5 | Equal variance & Welch | Compare Student's and Welch's t-tests as spreads and group sizes change; Levene's test rules and jamovi settings. |
| 6 | Paired: blackbirds | The lecture's blackbird data: differences, paired t, and a paired vs. independent comparison. |
| 7 | Significant vs. important | p-value vs. effect size (Cohen's d) as sample size grows; the lecture's evidence scale. |
| 8 | Data Lab | Paste any two columns of numbers: Levene's test, Student's/Welch's/paired t, p, effect size and full working. |
| 9 | t-table | Critical values; click a cell to have it read back in words. |

### Built-in help for students

- **Calculator** button (bottom corner, every tab), with √, x², powers, brackets, Ans and history.
- **Calculations in the answer boxes:** type something like `sqrt(0.3827/8 + 0.2855/8)` and press Enter.
- **"Stuck? Show the answer"** button on every step of Tabs 4 and 6. A revealed step is labelled "answer shown."
- **t-table** button (orange, bottom corner) on every tab.

## Using it in class

- Put the live link at the top of the Canvas assignment (see the Teacher Guide for a ready-to-paste introduction).
- Link straight to a tab by adding its name to the address: `#which`, `#signal`, `#worked`, `#frogs`, `#welch`, `#paired`, `#meaning`, `#lab`, `#tables`.
  Example: `https://lizferguson5.github.io/t-test/#frogs`
- No login, install or account is needed. It runs on laptops, tablets and phones; graphs are easiest to read on a laptop.
- Student answers are not saved. Refreshing the page clears them, so students should record answers in Canvas as they go.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app in one file (HTML, styles and code). No other dependencies. |
| `README.md` | This file. |

The **Teacher Guide** (`Two-Sample_t-Test_Lab_Teacher_Guide.docx`) and the **Canvas questions with answer key** (`Two-Sample_t-Test_Lab_Canvas_Questions.docx`) belong in Canvas or your own files, not in this repository, so students can't see the answers.

