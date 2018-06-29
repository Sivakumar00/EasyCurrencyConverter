# EasyCurrencyConverter

## Prerequisites

### Add Dependencies to gradle

```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
  
  ```
  dependencies {
	        implementation 'com.github.Sivakumar00:EasyCurrencyConverter:1.2.1'
	}
  ```
  
## Method Call

```
//To get conversion rate: 

double output = EasyCurrency.convertCurrency("inr","USD");


//To get conversion rate of specific value

double output=EasyCurrency.getCurrencyExchange("eur","inr",5);

```

#### Note: Only currency code is available. No country code or country name are allowed.

