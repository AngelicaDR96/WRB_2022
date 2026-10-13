# WRB_2022
dictionaries, objects, and codes to digitize the International Soil Classification System (WRB 2022).


# check_WRB_classification_from_db
The code automatically verifies that the data collected during a pedological survey are consistent with the rules of the International Soil Classification System (WRB 2022 - https://wrb.isric.org/files/WRB_fourth_edition_2022-12-18_errata_correction_2024-09-24.pdf). In particular, the code checks whether the principal and supplementary qualifiers attributed to a soil type are among those allowed by WRB 2022, pages 96–126.

  The code runs on a db such as the following
  ![Example_input_db](https://github.com/AngelicaDR96/WRB_2022/blob/main/Screenshot%202026-10-13%20172025.png)
  and returns a db like the following
  ![Example_output_db](https://github.com/AngelicaDR96/WRB_2022/blob/main/Screenshot%202026-10-13%20172253.png)
