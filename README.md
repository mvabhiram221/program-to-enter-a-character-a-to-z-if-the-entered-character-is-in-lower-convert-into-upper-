# program-to-enter-a-character-a-to-z-if-the-entered-character-is-in-lower-convert-into-upper-
ch=input("Enter any character from a-z")
if ch>='A' and ch<='Z':
    ch=ch.lower()
    print("converted case of input char:",ch)
else:
    ch=ch.upper()
    print("converted case of input char:",ch)
