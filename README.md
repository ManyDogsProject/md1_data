
# Data for ManyDogs 1

- Created on 2024-01-23 by Jeffrey R. Stevens
  (<jeffrey.r.stevens@gmail.com>)
- Finalized on 2024-07-18

This repository provides the complete data and reproducible research
materials for the ManyDogs 1 project. This includes the following:

- Data
- R Markdown file for the manuscript

## Citation

If you use any of these materials, please cite:

ManyDogs Project, Espinosa, J., Hare, E., Alberghina, D., Perez
Valverde, B, & Stevens, J.R. (2024). Data for ManyDogs 1. *Journal of
Open Psychology Data*.
[doi:10.5334/jopd.109](https://doi.org/10.5334/jopd.109)

## Summary

In this project, pet dogs voluntarily participated in a two-alternative
object choice task with ostensive and non-ostensive experimental
conditions, along with warm-up (one cup, two cup) trials and an odor
control condition. We collected data from 20 sites in eight countries.
The data file (`manydogs_etal_2024_data.csv`) contains records from 704
dogs tested for the main experiment between 2022-01-20 and 2023-01-23.
Each row represents data for an individual dog.

## License

All materials presented here are released under the Creative Commons
Attribution 4.0 International Public License (CC BY 4.0). You are free
to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose,
  even commercially. Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the
  license, and indicate if changes were made. You may do so in any
  reasonable manner, but not in any way that suggests the licensor
  endorses you or your use.

No additional restrictions — You may not apply legal terms or
technological measures that legally restrict others from doing anything
the license permits.

## Files

### Data files

`manydogs_etal_2024_data.csv`

| variable                 | description                                                                                                                                                                                                               |
|:-------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date                     | Date                                                                                                                                                                                                                      |
| site                     | Abbreviation for site/location                                                                                                                                                                                            |
| subject_id               | Subject ID                                                                                                                                                                                                                |
| experiment_status        | Status of subject in experiment                                                                                                                                                                                           |
| owned_status             | Location of where dog lives                                                                                                                                                                                               |
| birthdate                | Dog date of birth                                                                                                                                                                                                         |
| sex                      | Dog sex                                                                                                                                                                                                                   |
| age                      | Dog age (years)                                                                                                                                                                                                           |
| desexed                  | Dog neuter status                                                                                                                                                                                                         |
| purebred                 | Dog purebreed status                                                                                                                                                                                                      |
| breed                    | Dog breed                                                                                                                                                                                                                 |
| breed_registry           | Dog breed registration status                                                                                                                                                                                             |
| mixed_breed              | Dog mixed breeds                                                                                                                                                                                                          |
| communication_method     | Owner’s method of communication with dog                                                                                                                                                                                  |
| gesture_frequency        | Frequency of owner using hand gestures with dog                                                                                                                                                                           |
| gaze_follow              | Frequency of dog following pointing gestures                                                                                                                                                                              |
| training_type            | Presence of dog training/activities                                                                                                                                                                                       |
| training_freq_puppy      | Frequency of puppy classes                                                                                                                                                                                                |
| training_freq_neighbor   | Frequency of good neighbor classes                                                                                                                                                                                        |
| training_freq_obedience1 | Frequency of basic obedience classes                                                                                                                                                                                      |
| training_freq_obedience2 | Frequency of advanced obedience classes                                                                                                                                                                                   |
| training_freq_rallyo     | Frequency of rally obedience activities                                                                                                                                                                                   |
| training_freq_music      | Frequency of musical freestyle activities                                                                                                                                                                                 |
| training_freq_agility    | Frequency of agility activities                                                                                                                                                                                           |
| training_freq_flyball    | Frequency of flyball activities                                                                                                                                                                                           |
| training_freq_disc       | Frequency of discdog activities                                                                                                                                                                                           |
| training_freq_conform    | Frequency of conformation activities                                                                                                                                                                                      |
| training_freq_scent      | Frequency of scent detection activities                                                                                                                                                                                   |
| training_freq_search     | Frequency of search and rescue activities                                                                                                                                                                                 |
| training_freq_sled       | Frequency of sled pulling activities                                                                                                                                                                                      |
| training_freq_pullsport  | Frequency of skijoring/canicross/bikejoring activities (attaching dogs to skiers/runners/bikers)                                                                                                                          |
| training_freq_therapy    | Frequency of therapy dog activities                                                                                                                                                                                       |
| training_freq_service    | Frequency of service dog activities                                                                                                                                                                                       |
| training_freq_hunt       | Frequency of hunting/tracking activities                                                                                                                                                                                  |
| training_freq_herd       | Frequency of herding activities                                                                                                                                                                                           |
| training_freq_other1     | Frequency of other activities (fill in activity)                                                                                                                                                                          |
| training_freq_other2     | Frequency of other activities (fill in activity)                                                                                                                                                                          |
| training_freq_other3     | Frequency of other activities (fill in activity)                                                                                                                                                                          |
| lab_exposure             | Research lab experience status                                                                                                                                                                                            |
| research_experience      | Research lab experience types                                                                                                                                                                                             |
| other_household_dogs     | Dog shared household status                                                                                                                                                                                               |
| num_household_dogs       | Number of dogs in household                                                                                                                                                                                               |
| years_owned              | Number of years dog lived with owner                                                                                                                                                                                      |
| origin                   | Dog origin                                                                                                                                                                                                                |
| guardian_gender          | Guardian gender                                                                                                                                                                                                           |
| guardian_age             | Guardian age                                                                                                                                                                                                              |
| environment              | Environment of residence                                                                                                                                                                                                  |
| cbarq_train_1            | C-BARQ training question 1                                                                                                                                                                                                |
| cbarq_train_2            | C-BARQ training question 2                                                                                                                                                                                                |
| cbarq_train_3            | C-BARQ training question 3                                                                                                                                                                                                |
| cbarq_train_4            | C-BARQ training question 4                                                                                                                                                                                                |
| cbarq_train_5            | C-BARQ training question 5                                                                                                                                                                                                |
| cbarq_train_6            | C-BARQ training question 6                                                                                                                                                                                                |
| cbarq_train_7            | C-BARQ training question 7                                                                                                                                                                                                |
| cbarq_train_8            | C-BARQ training question 8                                                                                                                                                                                                |
| continue_cbarq           | Status of whether owner continued to remaining C-BARQ questions                                                                                                                                                           |
| cbarq_aggression_1       | C-BARQ aggression question 1 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_2       | C-BARQ aggression question 2 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_3       | C-BARQ aggression question 3 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_4       | C-BARQ aggression question 4 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_5       | C-BARQ aggression question 5 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_6       | C-BARQ aggression question 6 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_7       | C-BARQ aggression question 7 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_8       | C-BARQ aggression question 8 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_9       | C-BARQ aggression question 9 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                 |
| cbarq_aggression_10      | C-BARQ aggression question 10 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_11      | C-BARQ aggression question 11 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_12      | C-BARQ aggression question 12 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_13      | C-BARQ aggression question 13 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_14      | C-BARQ aggression question 14 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_15      | C-BARQ aggression question 15 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_16      | C-BARQ aggression question 16 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_17      | C-BARQ aggression question 17 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_18      | C-BARQ aggression question 18 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_19      | C-BARQ aggression question 19 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_20      | C-BARQ aggression question 20 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_21      | C-BARQ aggression question 21 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_22      | C-BARQ aggression question 22 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_23      | C-BARQ aggression question 23 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_24      | C-BARQ aggression question 24 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_25      | C-BARQ aggression question 25 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_26      | C-BARQ aggression question 26 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_aggression_27      | C-BARQ aggression question 27 (‘Some dogs display aggressive behavior from time to time.’)                                                                                                                                |
| cbarq_fear_1             | C-BARQ fear question 1 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_2             | C-BARQ fear question 2 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_3             | C-BARQ fear question 3 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_4             | C-BARQ fear question 4 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_5             | C-BARQ fear question 5 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_6             | C-BARQ fear question 6 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_7             | C-BARQ fear question 7 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_8             | C-BARQ fear question 8 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_9             | C-BARQ fear question 9 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                 |
| cbarq_fear_10            | C-BARQ fear question 10 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_11            | C-BARQ fear question 11 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_12            | C-BARQ fear question 12 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_13            | C-BARQ fear question 13 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_14            | C-BARQ fear question 14 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_15            | C-BARQ fear question 15 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_16            | C-BARQ fear question 16 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_17            | C-BARQ fear question 17 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_fear_18            | C-BARQ fear question 18 (‘Dogs sometimes show signs of anxiety or fear when exposed to particular sounds, objects, persons or situations’)                                                                                |
| cbarq_separation_1       | C-BARQ separation question 1 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_separation_2       | C-BARQ separation question 2 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_separation_3       | C-BARQ separation question 3 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_separation_4       | C-BARQ separation question 4 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_separation_5       | C-BARQ separation question 5 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_separation_6       | C-BARQ separation question 6 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_separation_7       | C-BARQ separation question 7 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_separation_8       | C-BARQ separation question 8 (‘Some dogs show signs of anxiety or abnormal behavior when left alone, even for relatively short periods of time.’)                                                                         |
| cbarq_excitability_1     | C-BARQ excitability question 1 (‘Some dogs show relatively little reaction to sudden or potentially exciting events and disturbances in their environment, while others become highly excited at the slightest novelty.’) |
| cbarq_excitability_2     | C-BARQ excitability question 2 (‘Some dogs show relatively little reaction to sudden or potentially exciting events and disturbances in their environment, while others become highly excited at the slightest novelty.’) |
| cbarq_excitability_3     | C-BARQ excitability question 3 (‘Some dogs show relatively little reaction to sudden or potentially exciting events and disturbances in their environment, while others become highly excited at the slightest novelty.’) |
| cbarq_excitability_4     | C-BARQ excitability question 4 (‘Some dogs show relatively little reaction to sudden or potentially exciting events and disturbances in their environment, while others become highly excited at the slightest novelty.’) |
| cbarq_excitability_5     | C-BARQ excitability question 5 (‘Some dogs show relatively little reaction to sudden or potentially exciting events and disturbances in their environment, while others become highly excited at the slightest novelty.’) |
| cbarq_excitability_6     | C-BARQ excitability question 6 (‘Some dogs show relatively little reaction to sudden or potentially exciting events and disturbances in their environment, while others become highly excited at the slightest novelty.’) |
| cbarq_attachment_1       | C-BARQ attachment question 1 (‘Most dogs are strongly attached to their people, and some demand a great deal of attention and affection from them.’)                                                                      |
| cbarq_attachment_2       | C-BARQ attachment question 2 (‘Most dogs are strongly attached to their people, and some demand a great deal of attention and affection from them.’)                                                                      |
| cbarq_attachment_3       | C-BARQ attachment question 3 (‘Most dogs are strongly attached to their people, and some demand a great deal of attention and affection from them.’)                                                                      |
| cbarq_attachment_4       | C-BARQ attachment question 4 (‘Most dogs are strongly attached to their people, and some demand a great deal of attention and affection from them.’)                                                                      |
| cbarq_attachment_5       | C-BARQ attachment question 5 (‘Most dogs are strongly attached to their people, and some demand a great deal of attention and affection from them.’)                                                                      |
| cbarq_attachment_6       | C-BARQ attachment question 6 (‘Most dogs are strongly attached to their people, and some demand a great deal of attention and affection from them.’)                                                                      |
| cbarq_miscellaneous_1    | C-BARQ miscellaneous question 1 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_2    | C-BARQ miscellaneous question 2 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_3    | C-BARQ miscellaneous question 3 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_4    | C-BARQ miscellaneous question 4 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_5    | C-BARQ miscellaneous question 5 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_6    | C-BARQ miscellaneous question 6 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_7    | C-BARQ miscellaneous question 7 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_8    | C-BARQ miscellaneous question 8 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_9    | C-BARQ miscellaneous question 9 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                              |
| cbarq_miscellaneous_10   | C-BARQ miscellaneous question 10 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_11   | C-BARQ miscellaneous question 11 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_12   | C-BARQ miscellaneous question 12 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_13   | C-BARQ miscellaneous question 13 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_14   | C-BARQ miscellaneous question 14 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_15   | C-BARQ miscellaneous question 15 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_16   | C-BARQ miscellaneous question 16 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_17   | C-BARQ miscellaneous question 17 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_18   | C-BARQ miscellaneous question 18 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_19   | C-BARQ miscellaneous question 19 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_20   | C-BARQ miscellaneous question 20 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_21   | C-BARQ miscellaneous question 21 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_22   | C-BARQ miscellaneous question 22 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_23   | C-BARQ miscellaneous question 23 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_24   | C-BARQ miscellaneous question 24 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_25   | C-BARQ miscellaneous question 25 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_26   | C-BARQ miscellaneous question 26 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| cbarq_miscellaneous_27   | C-BARQ miscellaneous question 27 (‘Dogs display a wide range of miscellaneous behavior problems in addition to those already covered by this questionnaire.’)                                                             |
| first_condition          | Which experimental condition was experienced first                                                                                                                                                                        |
| onecup_1                 | Choice in one-cup warm-up trial 1                                                                                                                                                                                         |
| onecup_2                 | Choice in one-cup warm-up trial 2                                                                                                                                                                                         |
| onecup_3                 | Choice in one-cup warm-up trial 3                                                                                                                                                                                         |
| onecup_4                 | Choice in one-cup warm-up trial 4                                                                                                                                                                                         |
| onecup_5                 | Choice in one-cup warm-up trial 5                                                                                                                                                                                         |
| onecup_6                 | Choice in one-cup warm-up trial 6                                                                                                                                                                                         |
| onecup_7                 | Choice in one-cup warm-up trial 7                                                                                                                                                                                         |
| twocup_1                 | Choice in two-cup warm-up trial 1                                                                                                                                                                                         |
| twocup_2                 | Choice in two-cup warm-up trial 2                                                                                                                                                                                         |
| twocup_3                 | Choice in two-cup warm-up trial 3                                                                                                                                                                                         |
| twocup_4                 | Choice in two-cup warm-up trial 4                                                                                                                                                                                         |
| twocup_5                 | Choice in two-cup warm-up trial 5                                                                                                                                                                                         |
| twocup_6                 | Choice in two-cup warm-up trial 6                                                                                                                                                                                         |
| twocup_7                 | Choice in two-cup warm-up trial 7                                                                                                                                                                                         |
| twocup_8                 | Choice in two-cup warm-up trial 8                                                                                                                                                                                         |
| twocup_9                 | Choice in two-cup warm-up trial 9                                                                                                                                                                                         |
| twocup_10                | Choice in two-cup warm-up trial 10                                                                                                                                                                                        |
| twocup_11                | Choice in two-cup warm-up trial 11                                                                                                                                                                                        |
| twocup_12                | Choice in two-cup warm-up trial 12                                                                                                                                                                                        |
| twocup_13                | Choice in two-cup warm-up trial 13                                                                                                                                                                                        |
| twocup_14                | Choice in two-cup warm-up trial 14                                                                                                                                                                                        |
| twocup_15                | Choice in two-cup warm-up trial 15                                                                                                                                                                                        |
| twocup_16                | Choice in two-cup warm-up trial 16                                                                                                                                                                                        |
| twocup_17                | Choice in two-cup warm-up trial 17                                                                                                                                                                                        |
| twocup_18                | Choice in two-cup warm-up trial 18                                                                                                                                                                                        |
| twocup_19                | Choice in two-cup warm-up trial 19                                                                                                                                                                                        |
| twocup_20                | Choice in two-cup warm-up trial 20                                                                                                                                                                                        |
| twocup_21                | Choice in two-cup warm-up trial 21                                                                                                                                                                                        |
| twocup_22                | Choice in two-cup warm-up trial 22                                                                                                                                                                                        |
| twocup_23                | Choice in two-cup warm-up trial 23                                                                                                                                                                                        |
| nonostensive_1           | Choice in non-ostensive trial 1                                                                                                                                                                                           |
| nonostensive_2           | Choice in non-ostensive trial 2                                                                                                                                                                                           |
| nonostensive_3           | Choice in non-ostensive trial 3                                                                                                                                                                                           |
| nonostensive_4           | Choice in non-ostensive trial 4                                                                                                                                                                                           |
| nonostensive_5           | Choice in non-ostensive trial 5                                                                                                                                                                                           |
| nonostensive_6           | Choice in non-ostensive trial 6                                                                                                                                                                                           |
| nonostensive_7           | Choice in non-ostensive trial 7                                                                                                                                                                                           |
| nonostensive_8           | Choice in non-ostensive trial 8                                                                                                                                                                                           |
| nonostensive_9           | Choice in non-ostensive trial 9                                                                                                                                                                                           |
| nonostensive_10          | Choice in non-ostensive trial 10                                                                                                                                                                                          |
| nonostensive_11          | Choice in non-ostensive trial 11                                                                                                                                                                                          |
| nonostensive_12          | Choice in non-ostensive trial 12                                                                                                                                                                                          |
| nonostensive_13          | Choice in non-ostensive trial 13                                                                                                                                                                                          |
| nonostensive_14          | Choice in non-ostensive trial 14                                                                                                                                                                                          |
| ostensive_1              | Choice in ostensive trial 1                                                                                                                                                                                               |
| ostensive_2              | Choice in ostensive trial 2                                                                                                                                                                                               |
| ostensive_3              | Choice in ostensive trial 3                                                                                                                                                                                               |
| ostensive_4              | Choice in ostensive trial 4                                                                                                                                                                                               |
| ostensive_5              | Choice in ostensive trial 5                                                                                                                                                                                               |
| ostensive_6              | Choice in ostensive trial 6                                                                                                                                                                                               |
| ostensive_7              | Choice in ostensive trial 7                                                                                                                                                                                               |
| ostensive_8              | Choice in ostensive trial 8                                                                                                                                                                                               |
| ostensive_9              | Choice in ostensive trial 9                                                                                                                                                                                               |
| ostensive_10             | Choice in ostensive trial 10                                                                                                                                                                                              |
| ostensive_11             | Choice in ostensive trial 11                                                                                                                                                                                              |
| odor_1                   | Choice in odor trial 1                                                                                                                                                                                                    |
| odor_2                   | Choice in odor trial 2                                                                                                                                                                                                    |
| odor_3                   | Choice in odor trial 3                                                                                                                                                                                                    |
| odor_4                   | Choice in odor trial 4                                                                                                                                                                                                    |
| odor_5                   | Choice in odor trial 5                                                                                                                                                                                                    |
| odor_6                   | Choice in odor trial 6                                                                                                                                                                                                    |

### R Markdown documents

`manydogs_etal_2024.Rmd` - R Markdown document with R code embedded for
main manuscript and appendix

### Installation

To reproduce these results, first clone or unzip the Git repository into
a folder. Then, compile the R Markdown document
`manydogs_etal_2024.Rmd.` Open this file in RStudio and ensure that you
have packages [{knitr}](https://yihui.org/knitr/) and
[{rmarkdown}](https://rmarkdown.rstudio.com/) installed. Once installed,
use {knitr} to render the document (control-shift-K).

# Dataset Metadata

The following table is necessary for this dataset to be indexed by
search engines such as <a href="https://g.co/datasetsearch">Google
Dataset Search</a>.

<div itemscope="" itemtype="http://schema.org/Dataset">

<table>
<tr>
<th>
property
</th>
<th>
value
</th>
</tr>
<tr>
<td>
name
</td>
<td>
<code itemprop="name">Data for ManyDogs 1</code>
</td>
</tr>
<tr>
<td>
description
</td>
<td>
<code itemprop="description">The dataset from the paper
<a href="https://doi.org/10.5334/jopd.109">Data for ManyDogs 1</a>.
In this project, pet dogs voluntarily participated in a two-alternative
object choice task with ostensive and non-ostensive experimental
conditions, along with warm-up (one cup, two cup) trials and an odor
control condition. We collected data from 20 sites in nine countries.
The data file (manydogs_etal_2024_data.csv) contains records from 704
dogs tested for the main experiment between 2022-01-20 and 2023-01-23.
Each row represents data for an individual dog.</code>
</td>
</tr>
</tr>
<tr>
<td>
url
</td>
<td>
<code itemprop="url">https://github.com/ManyDogsProject/md1_data</code>
</td>
</tr>
<tr>
<td>
sameAs
</td>
<td>
<code itemprop="sameAs">https://github.com/ManyDogsProject/md1_data</code>
</td>
</tr>
<tr>
<td>
citation
</td>
<td>
<code itemprop="citation">https://doi.org/10.5334/jopd.109</code>
</td>
</tr>
<tr>
<td>
license
</td>
<td>

<div itemscope="" itemtype="http://schema.org/CreativeWork"
itemprop="license">

<table>
<tr>
<th>
property
</th>
<th>
value
</th>
</tr>
<tr>
<td>
name
</td>
<td>
<code itemprop="name">CC BY-SA 4.0</code>
</td>
</tr>
<tr>
<td>
url
</td>
<td>
<code itemprop="url">https://creativecommons.org/licenses/by-sa/4.0/</code>
</td>
</tr>
</table>

</div>

</td>
</tr>
</table>

</div>
