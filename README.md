# phyton_5
Source kode:

print(("[APLIKASI TERBILANG]"))

numbers = input ("Masukkan angka:")

numbers_mapping = {
    "1": "satu",
    "2": "dua",
    "3": "tiga",
    "4": "empat",
    "5": "lima",
    "6": "enam",
    "7": "tujuh",
    "8": "delapan",
    "9": "sembilan",
}

output = ""

for n in numbers:
    terbilang = numbers_mapping.get(n, "invalid")

    output = output + terbilang + " "

print(output)   
print("\n") 

print("[EMOJI CONVERTER]")
message = input(">>>")

emoji_mapping = {
    ":)" : "🙂",
    ":D" : "😄",
    ":|" : "😐",
}

words = message.split(" ")

output = " "
for w in words :
    output = output + emoji_mapping.get(w,w)+" "

    print(output)
print("\n")

print("[FUNGSI]")
def hallo_user():
    print("hallo user")
    print("selamat anda telah sampai tujuan")


input("start")
hallo_user()
print("finish")
print("\n")

print("[PARAMETER FUNGSI]")
def hallo_user(nama, age):
    print(f"hallo {nama} - {age}")
    print("selamat anda telah sampai tujuan")


input("start")
hallo_user("Magfira",19)       #posisional argumen
print("===============")
hallo_user("Sujain",21)
print("finish")
print("\n")

print("[KEYWORD ARGUMENT]")
def hallo_user(nama, age):
    print(f"hallo {nama} {age}")
    print("selamat anda telah sampai tujuan")


input("start")
hallo_user(age=19, nama="Magfira")
print("finish")
print("\n")

print("[RETURN VALUE]")
def multiply(a, b):
    result = a*b
    return result

#input adalah si parameter ini yaitu 2 dan 10
#proses adalah yang ada multifungsi a dan b
#output adalah hasil

result = multiply(2,10)
print(result) #hasil yang diingankan =2*10=20

Output:
<img width="960" alt="SAVE_20211110_155648" src="https://user-images.githubusercontent.com/93026923/141072914-1658bf3d-6ef1-42e0-b603-af37dd9d348b.png">
<img width="960" alt="SAVE_20211110_155658" src="https://user-images.githubusercontent.com/93026923/141072929-7a2a3432-1e2b-4596-9085-f36ec72319ad.png">
