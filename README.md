public class BoxingUnboxingDemo {
    public static void main(String[] args) {
        // Byte
        byte bytePrimitive = 10;
        Byte byteObject = bytePrimitive; // Boxing
        byte newBytePrimitive = byteObject; // Unboxing
        System.out.println("Byte: " + newBytePrimitive);

        // Short
        short shortPrimitive = 20;
        Short shortObject = shortPrimitive; // Boxing
        short newShortPrimitive = shortObject; // Unboxing
        System.out.println("Short: " + newShortPrimitive);

        // Integer
        int intPrimitive = 30;
        Integer intObject = intPrimitive; // Boxing
        int newIntPrimitive = intObject; // Unboxing
        System.out.println("Integer: " + newIntPrimitive);

        // Long
        long longPrimitive = 40L;
        Long longObject = longPrimitive; // Boxing
        long newLongPrimitive = longObject; // Unboxing
        System.out.println("Long: " + newLongPrimitive);

        // Float
        float floatPrimitive = 50.0f;
        Float floatObject = floatPrimitive; // Boxing
        float newFloatPrimitive = floatObject; // Unboxing
        System.out.println("Float: " + newFloatPrimitive);

        // Double
        double doublePrimitive = 60.0;
        Double doubleObject = doublePrimitive; // Boxing
        double newDoublePrimitive = doubleObject; // Unboxing
        System.out.println("Double: " + newDoublePrimitive);

        // Character
        char charPrimitive = 'A';
        Character charObject = charPrimitive; // Boxing
        char newCharPrimitive = charObject; // Unboxing
        System.out.println("Character: " + newCharPrimitive);

        // Boolean
        boolean booleanPrimitive = true;
        Boolean booleanObject = booleanPrimitive; // Boxing
        boolean newBooleanPrimitive = booleanObject; // Unboxing
        System.out.println("Boolean: " + newBooleanPrimitive);
    }
}

