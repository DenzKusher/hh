print('Stock Barang')
print('1, Beras 5 kantong')
print('2, Kopi 4 sachets')
print('3, Kecap 3 botol')
print('-------------------')
print('1, Tambah stok')
print('2, Kurangi stok')

# Harga barang
harga_beras = 50000
harga_kopi = 10000
harga_kecap = 20000

pilihan1 = int(input('Pilih barang yang ingin diubah stoknya: '))

if pilihan1 == 1:
    print('Anda memilih Beras')
    pilihan2 = int(input('Mau tambah atau kurang stok? (1: Tambah / 2: Kurang): '))

    if pilihan2 == 1:
        pilihan3 = int(input('Mau tambah berapa? '))
        beras = 5 + pilihan3
        print('Total beras:', beras, 'kantong')
        total_harga = beras * harga_beras
        print('Total harga beras:', total_harga)

    elif pilihan2 == 2:
        pilihan3 = int(input('Mau kurang berapa? '))
        beras = 5 - pilihan3
        print('Total beras:', beras, 'kantong')
        total_harga = beras * harga_beras
        print('Total harga beras:', total_harga)

elif pilihan1 == 2:
    print('Anda memilih Kopi')
    pilihan2 = int(input('Mau tambah atau kurang stok? (1: Tambah / 2: Kurang): '))

    if pilihan2 == 1:
        pilihan3 = int(input('Mau tambah berapa? '))
        kopi = 4 + pilihan3
        print('Total kopi:', kopi, 'sachets')
        total_harga = kopi * harga_kopi
        print('Total harga kopi:', total_harga)

    elif pilihan2 == 2:
        pilihan3 = int(input('Mau kurang berapa? '))
        kopi = 4 - pilihan3
        print('Total kopi:', kopi, 'sachets')
        total_harga = kopi * harga_kopi
        print('Total harga kopi:', total_harga)

elif pilihan1 == 3:
    print('Anda memilih Kecap')
    pilihan2 = int(input('Mau tambah atau kurang stok? (1: Tambah / 2: Kurang): '))

    if pilihan2 == 1:
        pilihan3 = int(input('Mau tambah berapa? '))
        kecap = 3 + pilihan3
        print('Total kecap:', kecap, 'botol')
        total_harga = kecap * harga_kecap
        print('Total harga kecap:', total_harga)

    elif pilihan2 == 2:
        pilihan3 = int(input('Mau kurang berapa? '))
        kecap = 3 - pilihan3
        print('Total kecap:', kecap, 'botol')
        total_harga = kecap * harga_kecap
        print('Total harga kecap:', total_harga)
