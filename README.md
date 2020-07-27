package pewarisan;


public class BangunDatar {
   float luas(){
        System.out.println("Menghitung laus bangun datar");
        return 0;
    }
    
    float keliling(){
        System.out.println("Menghitung keliling bangun datar");
        return 0;
    }
    
}

public class Persegi extends BangunDatar {
    float sisi;
    
}

public class Lingkaran extends BangunDatar {
    float r;
    
}

public class PersegiPanjang extends BangunDatar {
    float panjang;
    float lebar;
    
}

public class Segitiga extends BangunDatar {
    float alas;
    float tinggi;
    
    
}

public class Main {
    public static void main(String[] args) {
        BangunDatar bangunDatar = new BangunDatar();
        
        
        Persegi persegi = new Persegi();
        persegi.sisi = 2;
        
       
        Lingkaran lingkaran = new Lingkaran();
        lingkaran.r = 22;
        
       
        PersegiPanjang persegiPanjang = new PersegiPanjang();
        persegiPanjang.panjang = 8;
        persegiPanjang.lebar = 4;
        
       
        Segitiga mSegitiga = new Segitiga();
        mSegitiga.alas = 12;
        mSegitiga.tinggi = 8;
        
        
       
        bangunDatar.luas();
        bangunDatar.keliling();
        
        persegi.luas();
        persegi.keliling();
        
        lingkaran.luas();
        lingkaran.keliling();
        
        persegiPanjang.luas();
        persegiPanjang.keliling();
        
        mSegitiga.luas();
        mSegitiga.keliling();
    
    }
    
}
