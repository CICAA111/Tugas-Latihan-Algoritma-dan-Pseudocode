Cari nilai KPK dari 3 dan 4
BEGIN
    a = 3
    b = 4
    max_value = max(a, b)
    lcm = max_value

    WHILE True DO
        IF lcm MOD a == 0 AND lcm MOD b == 0 THEN
            PRINT "KPK dari", a, "dan", b, "adalah", lcm
            BREAK
        END IF
        lcm = lcm + 1
    END WHILE
END

Fungsi untuk Menukar Posisi Dua Variabel x dan y

BEGIN
    x = "Manggis"
    y = "Pisang"
    temp = x
    x = y
    y = temp
    PRINT "Piring 1:", x
    PRINT "Piring 2:", y
END

Hitung luas Segitiga
BEGIN
    alas = 25
    tinggi = 30
    luas = 0.5 * alas * tinggi
    PRINT "Luas Segitiga:", luas
END

Hitung luas Jajar Genjang

BEGIN
    panjang = 5
    tinggi = 3
    luas = panjang * tinggi
    PRINT "Luas Jajar Genjang:", luas
END

Hitung luas Tabung

BEGIN
    r = 3
    tinggi = 5
    volume = 3.14 * r^2 * tinggi
    PRINT "Volume Tabung:", volume
END

Hitung luas Kerucut 
BEGIN
    diameter = 5
    r = diameter / 2
    tinggi = 4
    volume = (1/3) * 3.14 * r^2 * tinggi
    PRINT "Volume Kerucut:", volume
END
