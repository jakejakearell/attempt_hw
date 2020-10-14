Toaster:

slots = (integer)
bagel_setting? = (boolean)
model_name = (string)
temp_settings = (hash)  #setting one is 200 F, ect {1:200, 2:225, 3:250}

methods

how_many_bagels =(if bagel setting is tru then slots / 2 to let user know how many bagels they can toast at once )
max_and_min_temp = (checks the lowest and values in temp_settings and returns them to user)
show_info = (prints model_name and slot_number)
bagel_color = (checks if toaster can cook bagels then returns likely color based on temp_settings)

instance

HamiltonBeach

slots = 4
bagel_setting = true
model_name = "Big warm toaster"
temp_settings = {1:200, 2:250, 3:300}

how_many_bagels = 2
max_and_min_temp = (200, 300)
show_info = "4 slot big warm toaster"
bagel_color = "setting 3 will make a black bagel"
