class Person
{
  private String nama;
  private char jenisKelamin;
  private int umur;

  public void setNama(String nama)
  {
    this.nama = nama;
  }

  public String getNama()
  {
    return nama;
  }

  public void setJenisKelamin(char jenisKelamin)
  {
    this.jenisKelamin = jenisKelamin;
  }

  public char getJenisKelamin()
  {
    return jenisKelamin;
  }

  public void setUmur(int umur)
  {
    this.umur = umur;
  }

  public int getUmur()
  {
    return umur;
  }

}

public class Main
{

  public static void main (String[]args)
  {
    Person Anton = new Person();
    Anton.setNama("Anton");
    Anton.setJenisKelamin('L');
    Anton.setUmur(19);

    Person Riko = new Person();
    Riko.setNama("Riko");
    Riko.setJenisKelamin('L');
    Riko.setUmur(20);

    System.out.println("Nama : " + Anton.getNama());
    System.out.println("Jenis Kelamin : " + Anton.getJenisKelamin());
    System.out.println("Umur : " + Anton.getUmur());

    System.out.println("Nama : " + Riko.getNama());
    System.out.println("Jenis Kelamin : " + Riko.getJenisKelamin());
    System.out.println("Umur : " + Riko.getUmur());

  }
}
