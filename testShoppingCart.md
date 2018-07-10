# L-serCoder

--java--


Ini untuk Jawaban Case ShoppingCart.md

public class ShoppingCartTest{

    private string productCode;
    private string quantity;
    
   @testaddProduct()
    public void testAddProduct(string productCode, int quantity){
       return productCode;
       return quantity;
    }

   @testremoveProduct()
    public void testRemoveProduct(string productCode){
       return productCode;
    }

   @testshowCart()
    public voif testShowcart(){
    System.print.print{result};
    }
}

ublic class Cart extends ShoppingCartTest{
    private Cart item1;
    private Cart Item2;   

    protected void setUp() {
        item1 = new Cart("Baju Merah Mantap", 1);
        item2= new Cart("Baju Merah Mantap", 1);
    }
}
public void testEquals() {
    Assert.assertTrue(!item1.equals(null));
    Assert.assertEquals(item1, item2);
    Assert.assertEquals(item1, new Cart("Baju Merah Mantap", 1));
    Assert.assertTrue(item1.equals(item2));
}

public void testSimpleAdd() {
    Cart expected= new Cart("Baju Merah Mantap" ,2);
    Cart result= item1.add(item2);
    Assert.assertTrue(expected.equals(result));
}
