# Comp-9.3

public class Magazine extends ReadingMaterial{
	public String cat;
	public int year;
	public Magazine (int page, String name, String category, int releaseYear) {
		 super(page, name);
		 cat=category;
		 year = releaseYear;
		 
	 }
	 public void getCategory() {
		 System.out.println(cat);
	 }
	 public void getYear() {
		 System.out.println(year);
	 }
}
