# Data variable index

* **Participant**: Unique ID for each study participant
* **level**: Difference in dB between the masker and target in a given trial.
* **repetition**: Unique ID for each repetition of a given staircase a participant took part in.
* **trial_index**: Unique ID for each type of staircase (based on its combination of independent variables).
* **trial_num**: Number of trials passed in a given staircase.
* **first**: Intensity in dB of the masker tone.
* **second**: Intensity in dB of the target tone.
* **random**: Roving added to the masker and target.
* **adjust**: Correction added to masker and target if dB value is out of bounds.
* **envelope_1**: Amplitude envelope of the masker tone.
* **n_reversal**: Total number of reversals that have occurred in a given staircase.
* **c_reversal**: Number of *consecutive* reversals that have occurred in a given staircase.
* **c_stop**: Number of *consecutive* reversals that have occurred in a given staircase *at the lowest step size* (thereby fulfilling the stop rule in Experiment 3).
* **l_reversal**: Was this trial a reversal?
* **t_step_size_up**: How large are upward steps on this trial? (in ms)
* **t_step_size_down**: How large are downward steps on this trial? (in ms)
* **resp**: Did the participant say the target was longer on a given trial? (0 for no, 1 for yes).
* **block**: Which experimental block is the participant in currently?
* **trials.thisN**: Total number of trials that have passed across the entire experiment.
* **type**: Is the tone comparison homogenous or heterogenous?
* **Time**: Amount of time participant took to complete the experiment.
* **start_id**: Unique ID representing proportional magnitude of masker tone duration.
* **Gender**: Participant gender.
* **age**: Participant age.