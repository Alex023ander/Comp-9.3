# Comp-9.3

public static void main(String[] args) {
        Novel nov1=new Novel(10,"The Hobit", "Adventure", 1937);
        Comic com1=new Comic(40,"Spider-Man", "Color", 1962);
        Magazine mag1=new Magazine(20,"Sports Illustrated", "Sports", 1993);
        
        System.out.println(mag1);
        mag1.getCategory();
        mag1.getYear();
        
        System.out.println(nov1);
        nov1.getGenre();
        nov1.getYear();
        
        System.out.println(com1);
        com1.getColor();
        com1.getYear();
    }
    
}
