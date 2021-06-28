public class Main {
    
    public static void main(String[] args) {

        BonusMilesService service = new BonusMilesService();
        int price = 10_000;
        int miles = service.calculate(price);
        System.out.println(miles);

    }
}


public class BonusMilesService {
    
    public int calculate(int cost) {

        int price = 10_000;
        int bonus = 20;
        int miles = price / bonus;

        return miles;
    }
}




