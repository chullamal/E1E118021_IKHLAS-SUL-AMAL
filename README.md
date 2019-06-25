# E1E118021_IKHLAS-SUL-AMAL
show_data=['nama : ikhlas', 'nim : E1E118021', 'Jurusan : IT']


print("""
    pilih menu
    1. show data
    2. delete data
    3. keluar
""")

def show_data():
    if len(show_data) <=0:
        print ("tidak ada data")
    else :
        for indeks in range(len(show_data)):
            print ("[%d] %s ")%(indeks, show_data[indeks])



def delete_data():
    if len(show_data) <=0:
        print ("tidak ada data")
    else :
        for indeks in range(len(delete_data)):
            print ("[%d] %s ")%(indeks, delete_data[indeks])

print("""
    pilih menu
    1. show data
    2. delete data
    3. keluar
""")
pilihan=(input(int("masukan pilihan"))
         

if pilihan==1:
    print def(show_data)
elif pilihan ==2:
    print def(delete_data)
         
