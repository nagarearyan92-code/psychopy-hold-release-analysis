# psychopy-hold-release-analysis
Python analysis of PsychoPy hold-release task data, focusing on early-release detection and final-release latency.
This project demonstrates a simple behavioural data-analysis workflow using output from a PsychoPy hold-release task.

The task was designed as a small practice/demo paradigm for learning how to collect and analyse response timing data from PsychoPy. The analysis focuses on separating **early releases** from **normal final releases**, which is relevant to behavioural paradigms involving response inhibition, error awareness, and release-timing measures.

## Project overview

In this task, participants press and hold the spacebar during a hold period.

There are two possible response patterns:

1. **Early release**
   - The participant releases the key during the `KEEP HOLDING` period.
   - The task records an early release.
   - In the v5 version, the task skips the final `RELEASE NOW` screen.

2. **Normal final release**
   - The participant keeps holding during the hold period.
   - The task then shows a final release signal.
   - The participant releases the key after the signal appears.

This v5 version improves on the earlier prototype by preventing early-release trials from continuing to the final release screen.

## Repository contents

```text
hold_release_psychopy_analysis_v5_clean.ipynb
cleaned_hold_release_v5_data.csv
sample PsychoPy CSV output
hold_release_demo_v5_skip_release_signal.psyexp
README.md
