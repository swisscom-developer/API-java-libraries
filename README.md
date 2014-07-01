API-java-libraries
==================

### SendSMS -  Methode Details

```public java.lang.String sendSms(java.lang.String clientId,
                                java.lang.String from,
                                java.lang.String to,
                                java.lang.String text)```
                                
##### Parameters:

clientId - key from developer.swisscom.com

from - mobile number

to - mobile number

text - message

Returns: HTTP Response


### TokenValidation -  Methode Details


```public java.lang.String sendTokenShort(java.lang.String clientId,
                                       java.lang.String to)```
                                       
##### Parameters:

clientId - key from developer.swisscom.com

to - Swisscom mobile phone number

Returns: HTTP Response



```public java.lang.String sendTokenLong(java.lang.String clientId,
                                      java.lang.String to,
                                      java.lang.String text,
                                      java.lang.String tokenType,
                                      int expireTime,
                                      int tokenLength,
                                      java.lang.String traceID)```
                                      
                                      
##### Parameters:

clientId - key from developer.swisscom.com

to - Swisscom mobile phone number

text - Appears as text in the SMS

tokenType - Describes what kind of token should be generated. Is must be one of: SHORT_NUMERIC, SHORT_ALPHANUMERIC, SHORT_SMALL_AND_CAPITAL, LONG_CRYPTIC

expireTime - Expiration time of the token in seconds

tokenLength - The size of the token

traceID - Optional, but helps to track the request through the different systems

Returns: HTTP Response



```public java.lang.String validateToken(java.lang.String clientId,
                                      java.lang.String mobileNr,
                                      java.lang.String token)```
                                      
##### Parameters:

clientId - key from developer.swisscom.com

mobileNr - mobile number, which received the token

token - The token sent to the mobile number that needs verification. The format depends on the tokenType send in the Send SMS Token call

Returns: HTTP Response


### NumberValidation - Methode Details


```public java.lang.String validateNumber(java.lang.String clientId,
                                       java.lang.String phoneNumber)```
                                       
##### Parameters:

clientId - key from developer.swisscom.com

phoneNumber -


Returns: HTTP Response
