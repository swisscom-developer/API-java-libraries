API-java-libraries
==================

API-Java-Libraries


SendSMS -  Methode Details

public java.lang.String sendSms(java.lang.String clientId,
                                java.lang.String from,
                                java.lang.String to,
                                java.lang.String text)
Parameters:
clientId - key from developer.swisscom.com
from - mobile number
to - mobile number
text - message
Returns:
HTTP Response


TokenValidation -  Methode Details

public java.lang.String sendTokenShort(java.lang.String clientId,
                                       java.lang.String to)
Parameters:
clientId -
to - Swisscom mobile phone number
Returns:
HTTP Response


public java.lang.String sendTokenLong(java.lang.String clientId,
                                      java.lang.String to,
                                      java.lang.String text,
                                      java.lang.String tokenType,
                                      int expireTime,
                                      int tokenLength,
                                      java.lang.String traceID)
Parameters:
clientId -
to - Swisscom mobile phone number
text -
tokenType - SHORT_ALPHANUMERIC
expireTime -
tokenLength -
traceID -
Returns:
HTTP Response


public java.lang.String validateToken(java.lang.String clientId,
                                      java.lang.String mobileNr,
                                      java.lang.String token)
Parameters:
clientId -
mobileNr - mobile number, which received the token
token -
Returns:
HTTP Response


NumberValidation - Methode Details

public java.lang.String validateNumber(java.lang.String clientId,
                                       java.lang.String phoneNumber)
Parameters:
clientId -
phoneNumber -
Returns:
HTTP Response
