# A-bill-splitter-among-friends
I built a bil splitter to calculate the price and the tip amount ,of meals shared among friends to calculate how much, each person pays




running_total=0

num_of_friends=4

appetizers=37.89
main_courses=57.34
drinks=39.39
desserts=64.21

running_total += appetizers + main_courses + drinks + desserts
print("Total bill so far:" , running_total)

tip=running_total * 0.25
print("Tip amoumt:" , tip)

running_total += tip
print("Total with tip:" ,running_total)

final_bill=running_total/num_of_friends
print("Bill per person:" ,final_bill)

each_pays=round(final_bill,2)
print("Each person pays:" ,each_pays)