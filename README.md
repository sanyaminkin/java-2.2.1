public class Main {
    
    public static void main(String[] args) {

        BonusMilesService service = new BonusMilesService();
        int miles = service.calculate(10000);
        System.out.println(miles);

    }
}


public class BonusMilesService {
    
    public int calculate(int price) {
        int bonus = 20;
        int miles = price / bonus;

        return miles;
    }
}




