class Overloading {
    public static void main(String[] args) {
        Overloading obj = new Overloading();
        obj.print("Hello");
        obj.print(10);
        obj.print(10.5);
    }

    public void print(String str) {
        System.out.println("String : " + str);
    }

    public void print(int num) {
        System.out.println("Integer : " + num);
    }

    public void print(double d) {
        System.out.println("Double : " + d);
    }
}# -TUGAS-POLIMORFISME
 kode program menggunakan sintaks pemrograman JAVA yang menerapkan polimorfisme yaitu overloading dan overriding dengan permasalahan bebas
