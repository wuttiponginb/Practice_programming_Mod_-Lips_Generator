print("""---Mod_ Lips_Generator---

Story EX. I asked the _1._ for a __2.___, 
but he brought me a __3.__ of soup instead. 
When I told him, he said, 'Don't worry, the _4._ inside is a lifeguard.

---Please select Choice.---
1.  waiter / chef / doctor / teacher
2. glass of water / pizza / steak / bill
3. giant bowl of soup / cactus / rubber duck / bill
4. fly / spider / shrimp / toenail""")

word1 = ("waiter", "chef", "doctor", "teacher")
word2 = ("glass of water", "pizza", "steak", "bill")
word3 = ("giant bowl of soup", "cactus", "rubber duck", "bill")
word4 = ("fly", "spider", "shrimp", "toenail")

result = []
select_word1 = str(input("select word in word1: "))
for check_choice in word1:
    if check_choice == select_word1:
        result.append(check_choice)
select_word2 = str(input("select word in word2: "))
for check_choice in word2:
    if check_choice == select_word2:
        result.append(check_choice)
select_word3 = str(input("select word in word3: "))
for check_choice in word3:
    if check_choice == select_word3:
        result.append(check_choice)
select_word4 = str(input("select word in word4: "))
for check_choice in word4:
    if check_choice == select_word4:
        result.append(check_choice)
print("I asked the " + result[0] + " for a " + result[1]
+ " but he brought me a " + result[2] + " of soup instead."
"When I told him, he said, 'Don't worry, the " + result[3] + " inside is a lifeguard.")
