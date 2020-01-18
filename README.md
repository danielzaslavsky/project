# project
{
package ==== 

import java.util.ArrayList;
import java.util.List; 



import com.api.payments.Amount;
import com.paypal.payments.Authorization; 

lop =5 
========


/++

public class PayPalSDK
  private  static string crunchifyID =  " id client file " 
  private static string crunchifySecrect = " client key " 


private static String execitionMode = "sandbox"; === //sandbox ore exe 

public void crunchifyCapturePayPalAPI()   {

Payer crunchifyPayer = new Payer();
crunchifyPayer.setPaymentMethod("paypal");


// Url redirect 

RedirectUrls crunchifyRedirectUrls = new RedirectUrls(); 
crunchifyRedirectUrls.setCancelUrl(" domain ") 
crunchifyRedirectUrls.setReturnUrl)" domain")

// payment amount .dd   

Amount crunchifyAmount = new Amount(); 
crunchifyAmount.setCurrency("Currency"); 
crunchifyAmount.setTotal(" 5.55")

// 
