# Comp-9.3

public class ReadingMaterial {
	private int pages=0;
    private String names="";
    public ReadingMaterial(int p,String n){
        pages=p;
        names=n;
    }
    public int getPages(){
        return pages;
    }
    public String getName(){
        return names;
    }
    @Override
    public String toString(){
        return names+", "+pages+" pages";
    }
}
