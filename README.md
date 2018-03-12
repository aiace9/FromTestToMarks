# FromTestToMarks
A simple jupyter-notebook that allow you to handle the result of a test for a class. From point per exercise to final mark.

# Implemented Formula
```math
v = v_min + sum_{i in ex} p_i score_ex_i/score_tot_i (v_max- v_min)
```
where:
  * v_min, v_vmax are the minimun and maximum marks
  * p_i is the weight of the i th exercise (sum_{i in ex} p_i = 1)
  * score_ex_i score obtained by the student in the i th exercise
  * score_tot_i score of the i th exercise

