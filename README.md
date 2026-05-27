# Ransom-Note
ransomNote = input("Enter ransom note: ")
magazine = input("Enter magazine string: ")
for ch in ransomNote:
    if ch not in magazine:
        print(False)
        break
    magazine = magazine.replace(ch, '', 1)
else:
    print(True)
