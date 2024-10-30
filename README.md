class MyCustomException extends Exception {
    public MyCustomException(String message) {
    
        super(message
        
    }
}

public class CustomExceptionExample {
    public static void main(String[] args) {
    
        try {
            throw new MyCustomException("這是一個自定義異常！");
        } catch (MyCustomException e) {
            System.out.println("捕獲到自定義異常：" + e.getMessage());
        }
        
    }
}
