def Anagram(string1,string2):
    string1.replace(" ","").lower
    string2.replace(" ","").lower
    return sorted(string1)==sorted(string2)
str1=input("Enter string1:")
str2=input("Enter string1:")
 
if Anagram(str1,str2):
    print("anagram")
else:
    print("not an anagram") 
