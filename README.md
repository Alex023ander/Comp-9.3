# Comp-9.3

public class Novel extends ReadingMaterial{
	public String Gen;
	public int year;
	public Novel (int page, String name, String genre, int releaseYear) {
		 super(page, name);
		 Gen=genre;
		 year = releaseYear;
		 
	 }
	 public void getGenre() {
		 System.out.println(Gen);
	 }
	 public void getYear() {
		 System.out.println(year);
	 }
}
