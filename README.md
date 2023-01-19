# Comp-9.3

public class Comic extends ReadingMaterial{
	public String col;
	public int year;
	public Comic (int page, String name, String color, int releaseYear) {
		 super(page, name);
		 col=color;
		 year = releaseYear;
		 
	 }
	 public void getColor() {
		 System.out.println(col);
	 }
	 public void getYear() {
		 System.out.println(year);
	 }
}
