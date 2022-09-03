```c 
/* jminjares4 GitHub Page */
#include <stdio.h>
#include <stdlib.h>

/* Degree enumeration */
typedef enum { ASEE, BSEE, MSCpE } degree_t;

/* Contact data structure */
typedef struct{
    char email[32];
    char linkedin[64];
    char github[32];
} contact_t;

/* Info data structure */
typedef struct{
    char name[32];
    degree_t degree;
    contact_t contact;
} info_t;

int main(int argc, char **argv)
{
    /* Store data */
    info_t jminjares4 = { .name = "Jesus Minjares",
                          .degree = MSCpE,
                          .contact.email = "jminjares4@miners.utep.edu",
                          .contact.linkedin = "https://www.linkedin.com/in/jesusminjares",
                          .contact.github = "https://github.com/jminjares4"
                        };
    /* Print data */
    printf("Name: %s\n", jminjares4.name);
    printf("Degree: %d\n", jminjares4.degree);
    printf("Email: %s\n", jminjares4.contact.email);
    printf("LinkedIn: %s\n", jminjares4.contact.linkedin);
    printf("GitHub: %s\n", jminjares4.contact.github);

    return EXIT_SUCCESS;
}
```

<!-- <img src="gif/jminjares4.gif"> -->

## ***Jesus Minjares :computer::zap:***
I'm recent graduated with a ***Master of Science in Computer Engineering*** at [**University of Texas at El Paso (UTEP)**](https://www.utep.edu). I love `embedded systems`! The interaction between software and hardware intrigues as you need to understand both to create complex systems! :zap:

## ***Recent Projects***

<!--- Previous implementation
[![Custom NFC Card](https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Custom-NFC-Card&theme=react&layout=compact&hide_border=false)](https://github.com/jminjares4/Custom-NFC-Card)<br>
[![Selected Areas in Networks](https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Selected-Areas-in-Networks&theme=react&layout=compact&hide_border=false)](https://github.com/jminjares4/Selected-Areas-in-Networks)<br>
[![Digital System 2](https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Digital-System-2&theme=react&layout=compact&hide_border=false)](https://github.com/jminjares4/Digital-System-2)<br>
--->
<a href="https://github.com/jminjares4/ESP32-Sensor-Data-Logger">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=ESP32-Sensor-Data-Logger&theme=react&layout=compact&hide_border=false" />
</a>
<a href="https://github.com/jminjares4/Graduation-Cap-Spring-2022">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Graduation-Cap-Spring-2022&theme=react&layout=&hide_border=false"/>
</a>
<a href="https://github.com/jminjares4/Selected-Areas-in-Networks">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Selected-Areas-in-Networks&theme=react&layout=compact&hide_border=false" />
</a>
<a href="https://github.com/jminjares4/Custom-NFC-Card">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Custom-NFC-Card&theme=react&layout=compact&hide_border=false" />
</a>

<!-- ## **Microprocessor 2 Lab Template**
[![Microprocessor 2 Lab Template](https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Microprocessor-2-Lab-Template&theme=react&layout=compact&hide_border=false)](https://github.com/jminjares4/Microprocessor-2-Lab-Template)

<!-- ## **Digital System 2 Lab Template**
[![Digital Sytems 2 Lab Template](https://github-readme-stats.vercel.app/api/pin/?username=jminjares4&repo=Digital-System-2-Template&theme=react&layout=compact&hide_border=false)](https://github.com/jminjares4/Digital-System-2-Template) -->


## **Microcontrollers**
<!-- - **Texas Instrument** <br>  -->
![Texas Instruments](https://img.shields.io/static/v1?label=&message=MSP432&labelColor=white&color=black&logoWidth=35&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGwAAAAoCAYAAAAbrx%2B3AAAKYklEQVR42u1aA5B0ORDOzpvV%2FDNr2zv4bfNs27Zt27Zt27Zt2%2Fbd99V2159Lvdm9mdNs1euqrnlJOnlJf0mnu9%2BYgAIK6P%2BkyuLixqVqyjdyuWNIwTATUO7RmLLorNvHpn53eanqyk3N4KQAsDpjqhuKi5tNQLkPWMyYqmtHJT6%2FZUzyx2QkMsoElJuAnZDovH9Caem8tcbUALDPCFgqEhnXXFjYWRWJNKBrMTjPBJQbgJE3aK7dtypi6ieXRmePi8UmNxUWdmnbHWNTv142svedGeWxRU1uUAAYwdijq%2FlcPm%2FeUn%2F4zLLYEq7MkjXlG5j%2FlwLA9upquWTj5rpDY%2FD6LxjR8zLrFqgqX3FUNDqD9VeOjH%2BkskvXlG9o%2Fj8KALsNpo53lDocLLOed5d0KbppTPI7ld%2BgsW4vE9A%2FT3EEwhcM73nF5ctG9L5rA3bOsO7njNCkkpL5WXf1qPhHKIZYN7YsOtOWv3h4zxtRuP3Gn4rAZQMz90ZALuWfN6z7BVF0Wsbp%2BeHSEb3vTy%2BLLbZWY82urDu0p%2B36UbHiSayHx%2FiF22evzuYLfV%2BY711UUBD%2B7S%2FwNxAvcboH1BUtSF0xIv7%2BQKCROwoLew7qab2az%2Bs31e25RkP1Dulk9%2B1svtTndWXhsHdlKBTawvO8NcCrA8BbAc7v4M%2B1Du0b4vdUzzOrBAj5EF1znJR3%2BgPr%2BtGJL3hArhRwp5bHFjlEwBN2nJTmi%2FzMoRunhcOhfQgYgHvFqh4ip6uJvw5rrOfW50vfAqfes19njZGWZIyo9CXnHtHj6w%2BwUxKdD9cXFbXi%2BTc6HdVDTN3VI%2BMfppPfqrXhaDMw%2BQKGk7U46r4D%2F%2Boy5F6FSCFO4S4o%2FyT176NO02RtKH8B%2FhZj74lyufWuvfvGCD0loDtzMXMw%2Fr2Q%2BQH8C%2Fjr%2FPzwC8yHmxykostHznU2bh2b%2FOWSEb1vESCWj4i33co1NWLy2PYV7MC01LbtDcc4YP12WrLzEToi2QJGolJZD2B2oK8DngyFzgtTeTJ%2Fpe8BYk5%2FQDFlgf0rfpdwTw2BFYB%2FxxiznfZR3AD5Ye82PA8FV4Mn4H2ng9c1uUjzVZQucxuAgvn7amQsNoV1K9VXbUkgLkTs5bcrj%2Bxtv0XBOry37QamqlyZLAF7gvV4nOrTLaJi6HeH9H%2BAjq%2FchSc68gRy%2BXA4%2FDbb%2BgDzLrPbsTF27KsPHenzvpZcdkKSbUVFbVZV3inJrgcJyBr1tTvRHIE9OiBrN9bucuuY1E83jU5%2Bt2h15RoK6D8JGBS9GIp1wuNwMtyTWw%2B59%2BSkfQET9iLvQOMQgQUou3EMkf0Zz61zAfVWZr3M5WGaXFSPHpS50VllZYvrKboZATIA%2BkbLAOznqRUlC6jsPw2YwwRwZZ9hZqipg6K39mlPidlsIAAY%2Bxk5TfvbJhOn7mr3fZB9jLkEM8gohOD5WT%2FnYtOWhoMo8G8BRjcfxeFkgLUIeCHjEEDayFLyZ64J87zQ0bwT0XdZMs0hZQsLwx87HmMeTzDl6WxIPChygyuQ5%2F22vA9gv7UUFXW4sv%2F2HebQaMh9D2BPgZKflbFut9zxqHiNn6L9Y2U9kei3pshVOOPmycn9RpyUWWaQUR6yG9e6OUY6AP8yYNN8uk3RQBz9Xobs0zKPBPp8pd6lnL4N4Gy8o3GaEgN4MXmPcG0oX0xP1D28HF%2FmkTKDjBjQlB4bb7%2FDBg1BT9xkT7zsT%2BpTXPhDFi1FvS5A3gs%2BT%2Fh88D18pvMDJV8iyhxvmcetxTT%2BCPO3INzIN2jifN67EuXk9MyPfpvz1NGtxyY6kDGb5YGeZXKEGnhHgNcg04P6K4diydqKdQ%2FtbbuR%2BURx%2F7OlEVDmKRLrgM0i4oKvKHW%2BDAXPB4XuoWWaLp0bFL%2B7JXsafyF7kGsJILfpXLnQMagahrqd%2BAyAbgPfDT4Xc1mO4iZXCBM8WXba15KOCSiHiTttVwImdn4QUgBYBczEqmQfD61T2xzzOR7jbMfcXZ%2BJNQtLfULkfVlSTtN82lYR971KxillYKvtmpoSClOe9WK%2BelROTKUvMYUlfZah08FMSD%2FzHA0u4hzsPvbVorKS8hozwLqHWX2T0N2W0N1e%2BF1f1h3NADBOPnS8fXFLvaaC7pLkaQxcgPKFjFfoUrON6R9xBHpRPoNj0KGg6y1j%2FoLyB5JYfZ4ZDD6zDYO%2FBUfiDoz%2FqLjd32N%2Bm6m3J%2F0%2FJ5CO8peSoHppKhbvfUgzH2kSt1M5Z7JuPMZn7KP9wO%2FLPH%2BAI3K7yCyjMnRMbDWifJhkT7rlk9G30v9n6fOTlL%2FFeDdRz%2BhzKNdJx6hPr%2BGXOCeAvkBGJpFK0onJh8SJ1p13Kr01vbjFhd5c22W3LsndzkyC7hYuUHJ41%2BprQFsx0aoeIfqsYIT4bKWQ6sCTWRYX3qV63STiAZ5mKXYfNzzB%2B%2B6zksae7nSp%2B82JyQr5%2FU4%2BDXVZepGsijXf%2FPAnXC8tjYYR1FXf2kLHqkVA%2B360RKoPx6kZSQ82G8A%2BA39pRfoJFzA9iZJI9QmgxWxYmXXGP66MBdiyVn0V6wSIOM2nAPZUJoBxDXrK3JOUHjDbJLFdSADjiRDZX2mONbmc3wdYnrARwM72SSrnafjBOI9xpZuzzBgwmjg8TucJ00mi3PRnwIzEMmAxi5jYwW6QOQBgxgJsLfmsMQZyV8iCbuaUMgVMYqhvnVNWSAWBH%2BwPMKx%2FY4yxDn7XwzyuYT8bMN5pWOtz9rXhAGYGAIw0UbMtZCQy32W2hjrPHjAQYx7eJWqOsIDLFTDZKTuJzf%2Fd4l9Qv32mgNnMU80NoaYlC8DOo0m27zIJjn%2BmY5AWMLlLuUH5K1eCC1gTmdkZDYl4h2UIGOe5Bu9Kd%2B0CXChjwJwvwD%2FpgAKYTRF6N5jUEXQw1FxwgZkAJpn4UsgebmXKy7MFjH1R%2F4ncIUdzEzDuRH1NBiZxNDjsAxipXUAVvWQGmIow4Yz2fakHO%2FuSNWCafeDJsQALpzm%2BdWqKaCoyBEzvsALWOZtjtOz%2BN33emVBFOoBxLds6DlRjZoAJ%2BQNGivOUZAqYuP8uRXTddOjSAbabD2Cb00b7HOG1eXJUiXRfeXk6C0xSETSjVE6WgBnGJKwTN3cOzZIqRtJoedYiL7C9R6abBDBSsZ4C5gelbiDAajgFYbanuIktwJrBNg3nSU4D2DkuYOKwHUWLhMdaZ7O%2FL3OYaPwQhQJv0MtTvDFP4qev%2FTw%2FIm%2Ft3o3l4vyOpopKE9P5HmMje968%2B2QXvujERm2Wc3CgZbs9AmE5POPAUxnn6UmTeO0L3iVWMBpjpl9ivCrdaIyB8FjiJH5%2F4053Ngj5O44rrJ9X5kBmQz6LZ%2BjSeP5ByAFsCOcoluIO55vaMLFYP3OukHtc3vs53rOJSUPt%2FASvjPJYcJlVHpXONGgGQmKkFG2uZDhGEyDXTDrvGWm1jXXaIk5YMEKi%2FxapK5Ls%2Bma0BHSKaELtDaBjKYiO%2BfbQtqjKyF2Rx3dInR8vypNq9ZlvAL0odThri%2Fv8V6Qb480jie8JfI%2F5DymggAL6A7%2FPpMSyS0OKAAAAAElFTkSuQmCC)
![Texas Instruments](https://img.shields.io/static/v1?label=&message=MSP430&labelColor=white&color=black&logoWidth=35&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGwAAAAoCAYAAAAbrx%2B3AAAKYklEQVR42u1aA5B0ORDOzpvV%2FDNr2zv4bfNs27Zt27Zt27Zt2%2Fbd99V2159Lvdm9mdNs1euqrnlJOnlJf0mnu9%2BYgAIK6P%2BkyuLixqVqyjdyuWNIwTATUO7RmLLorNvHpn53eanqyk3N4KQAsDpjqhuKi5tNQLkPWMyYqmtHJT6%2FZUzyx2QkMsoElJuAnZDovH9Caem8tcbUALDPCFgqEhnXXFjYWRWJNKBrMTjPBJQbgJE3aK7dtypi6ieXRmePi8UmNxUWdmnbHWNTv142svedGeWxRU1uUAAYwdijq%2FlcPm%2FeUn%2F4zLLYEq7MkjXlG5j%2FlwLA9upquWTj5rpDY%2FD6LxjR8zLrFqgqX3FUNDqD9VeOjH%2BkskvXlG9o%2Fj8KALsNpo53lDocLLOed5d0KbppTPI7ld%2BgsW4vE9A%2FT3EEwhcM73nF5ctG9L5rA3bOsO7njNCkkpL5WXf1qPhHKIZYN7YsOtOWv3h4zxtRuP3Gn4rAZQMz90ZALuWfN6z7BVF0Wsbp%2BeHSEb3vTy%2BLLbZWY82urDu0p%2B36UbHiSayHx%2FiF22evzuYLfV%2BY711UUBD%2B7S%2FwNxAvcboH1BUtSF0xIv7%2BQKCROwoLew7qab2az%2Bs31e25RkP1Dulk9%2B1svtTndWXhsHdlKBTawvO8NcCrA8BbAc7v4M%2B1Du0b4vdUzzOrBAj5EF1znJR3%2BgPr%2BtGJL3hArhRwp5bHFjlEwBN2nJTmi%2FzMoRunhcOhfQgYgHvFqh4ip6uJvw5rrOfW50vfAqfes19njZGWZIyo9CXnHtHj6w%2BwUxKdD9cXFbXi%2BTc6HdVDTN3VI%2BMfppPfqrXhaDMw%2BQKGk7U46r4D%2F%2Boy5F6FSCFO4S4o%2FyT176NO02RtKH8B%2FhZj74lyufWuvfvGCD0loDtzMXMw%2Fr2Q%2BQH8C%2Fjr%2FPzwC8yHmxykostHznU2bh2b%2FOWSEb1vESCWj4i33co1NWLy2PYV7MC01LbtDcc4YP12WrLzEToi2QJGolJZD2B2oK8DngyFzgtTeTJ%2Fpe8BYk5%2FQDFlgf0rfpdwTw2BFYB%2FxxiznfZR3AD5Ye82PA8FV4Mn4H2ng9c1uUjzVZQucxuAgvn7amQsNoV1K9VXbUkgLkTs5bcrj%2Bxtv0XBOry37QamqlyZLAF7gvV4nOrTLaJi6HeH9H%2BAjq%2FchSc68gRy%2BXA4%2FDbb%2BgDzLrPbsTF27KsPHenzvpZcdkKSbUVFbVZV3inJrgcJyBr1tTvRHIE9OiBrN9bucuuY1E83jU5%2Bt2h15RoK6D8JGBS9GIp1wuNwMtyTWw%2B59%2BSkfQET9iLvQOMQgQUou3EMkf0Zz61zAfVWZr3M5WGaXFSPHpS50VllZYvrKboZATIA%2BkbLAOznqRUlC6jsPw2YwwRwZZ9hZqipg6K39mlPidlsIAAY%2Bxk5TfvbJhOn7mr3fZB9jLkEM8gohOD5WT%2FnYtOWhoMo8G8BRjcfxeFkgLUIeCHjEEDayFLyZ64J87zQ0bwT0XdZMs0hZQsLwx87HmMeTzDl6WxIPChygyuQ5%2F22vA9gv7UUFXW4sv%2F2HebQaMh9D2BPgZKflbFut9zxqHiNn6L9Y2U9kei3pshVOOPmycn9RpyUWWaQUR6yG9e6OUY6AP8yYNN8uk3RQBz9Xobs0zKPBPp8pd6lnL4N4Gy8o3GaEgN4MXmPcG0oX0xP1D28HF%2FmkTKDjBjQlB4bb7%2FDBg1BT9xkT7zsT%2BpTXPhDFi1FvS5A3gs%2BT%2Fh88D18pvMDJV8iyhxvmcetxTT%2BCPO3INzIN2jifN67EuXk9MyPfpvz1NGtxyY6kDGb5YGeZXKEGnhHgNcg04P6K4diydqKdQ%2FtbbuR%2BURx%2F7OlEVDmKRLrgM0i4oKvKHW%2BDAXPB4XuoWWaLp0bFL%2B7JXsafyF7kGsJILfpXLnQMagahrqd%2BAyAbgPfDT4Xc1mO4iZXCBM8WXba15KOCSiHiTttVwImdn4QUgBYBczEqmQfD61T2xzzOR7jbMfcXZ%2BJNQtLfULkfVlSTtN82lYR971KxillYKvtmpoSClOe9WK%2BelROTKUvMYUlfZah08FMSD%2FzHA0u4hzsPvbVorKS8hozwLqHWX2T0N2W0N1e%2BF1f1h3NADBOPnS8fXFLvaaC7pLkaQxcgPKFjFfoUrON6R9xBHpRPoNj0KGg6y1j%2FoLyB5JYfZ4ZDD6zDYO%2FBUfiDoz%2FqLjd32N%2Bm6m3J%2F0%2FJ5CO8peSoHppKhbvfUgzH2kSt1M5Z7JuPMZn7KP9wO%2FLPH%2BAI3K7yCyjMnRMbDWifJhkT7rlk9G30v9n6fOTlL%2FFeDdRz%2BhzKNdJx6hPr%2BGXOCeAvkBGJpFK0onJh8SJ1p13Kr01vbjFhd5c22W3LsndzkyC7hYuUHJ41%2BprQFsx0aoeIfqsYIT4bKWQ6sCTWRYX3qV63STiAZ5mKXYfNzzB%2B%2B6zksae7nSp%2B82JyQr5%2FU4%2BDXVZepGsijXf%2FPAnXC8tjYYR1FXf2kLHqkVA%2B360RKoPx6kZSQ82G8A%2BA39pRfoJFzA9iZJI9QmgxWxYmXXGP66MBdiyVn0V6wSIOM2nAPZUJoBxDXrK3JOUHjDbJLFdSADjiRDZX2mONbmc3wdYnrARwM72SSrnafjBOI9xpZuzzBgwmjg8TucJ00mi3PRnwIzEMmAxi5jYwW6QOQBgxgJsLfmsMQZyV8iCbuaUMgVMYqhvnVNWSAWBH%2BwPMKx%2FY4yxDn7XwzyuYT8bMN5pWOtz9rXhAGYGAIw0UbMtZCQy32W2hjrPHjAQYx7eJWqOsIDLFTDZKTuJzf%2Fd4l9Qv32mgNnMU80NoaYlC8DOo0m27zIJjn%2BmY5AWMLlLuUH5K1eCC1gTmdkZDYl4h2UIGOe5Bu9Kd%2B0CXChjwJwvwD%2FpgAKYTRF6N5jUEXQw1FxwgZkAJpn4UsgebmXKy7MFjH1R%2F4ncIUdzEzDuRH1NBiZxNDjsAxipXUAVvWQGmIow4Yz2fakHO%2FuSNWCafeDJsQALpzm%2BdWqKaCoyBEzvsALWOZtjtOz%2BN33emVBFOoBxLds6DlRjZoAJ%2BQNGivOUZAqYuP8uRXTddOjSAbabD2Cb00b7HOG1eXJUiXRfeXk6C0xSETSjVE6WgBnGJKwTN3cOzZIqRtJoedYiL7C9R6abBDBSsZ4C5gelbiDAajgFYbanuIktwJrBNg3nSU4D2DkuYOKwHUWLhMdaZ7O%2FL3OYaPwQhQJv0MtTvDFP4qev%2FTw%2FIm%2Ft3o3l4vyOpopKE9P5HmMje968%2B2QXvujERm2Wc3CgZbs9AmE5POPAUxnn6UmTeO0L3iVWMBpjpl9ivCrdaIyB8FjiJH5%2F4053Ngj5O44rrJ9X5kBmQz6LZ%2BjSeP5ByAFsCOcoluIO55vaMLFYP3OukHtc3vs53rOJSUPt%2FASvjPJYcJlVHpXONGgGQmKkFG2uZDhGEyDXTDrvGWm1jXXaIk5YMEKi%2FxapK5Ls%2Bma0BHSKaELtDaBjKYiO%2BfbQtqjKyF2Rx3dInR8vypNq9ZlvAL0odThri%2Fv8V6Qb480jie8JfI%2F5DymggAL6A7%2FPpMSyS0OKAAAAAElFTkSuQmCC)
![Texas Instruments](https://img.shields.io/static/v1?label=&message=TM4C&labelColor=white&color=black&logoWidth=35&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGwAAAAoCAYAAAAbrx%2B3AAAKYklEQVR42u1aA5B0ORDOzpvV%2FDNr2zv4bfNs27Zt27Zt27Zt2%2Fbd99V2159Lvdm9mdNs1euqrnlJOnlJf0mnu9%2BYgAIK6P%2BkyuLixqVqyjdyuWNIwTATUO7RmLLorNvHpn53eanqyk3N4KQAsDpjqhuKi5tNQLkPWMyYqmtHJT6%2FZUzyx2QkMsoElJuAnZDovH9Caem8tcbUALDPCFgqEhnXXFjYWRWJNKBrMTjPBJQbgJE3aK7dtypi6ieXRmePi8UmNxUWdmnbHWNTv142svedGeWxRU1uUAAYwdijq%2FlcPm%2FeUn%2F4zLLYEq7MkjXlG5j%2FlwLA9upquWTj5rpDY%2FD6LxjR8zLrFqgqX3FUNDqD9VeOjH%2BkskvXlG9o%2Fj8KALsNpo53lDocLLOed5d0KbppTPI7ld%2BgsW4vE9A%2FT3EEwhcM73nF5ctG9L5rA3bOsO7njNCkkpL5WXf1qPhHKIZYN7YsOtOWv3h4zxtRuP3Gn4rAZQMz90ZALuWfN6z7BVF0Wsbp%2BeHSEb3vTy%2BLLbZWY82urDu0p%2B36UbHiSayHx%2FiF22evzuYLfV%2BY711UUBD%2B7S%2FwNxAvcboH1BUtSF0xIv7%2BQKCROwoLew7qab2az%2Bs31e25RkP1Dulk9%2B1svtTndWXhsHdlKBTawvO8NcCrA8BbAc7v4M%2B1Du0b4vdUzzOrBAj5EF1znJR3%2BgPr%2BtGJL3hArhRwp5bHFjlEwBN2nJTmi%2FzMoRunhcOhfQgYgHvFqh4ip6uJvw5rrOfW50vfAqfes19njZGWZIyo9CXnHtHj6w%2BwUxKdD9cXFbXi%2BTc6HdVDTN3VI%2BMfppPfqrXhaDMw%2BQKGk7U46r4D%2F%2Boy5F6FSCFO4S4o%2FyT176NO02RtKH8B%2FhZj74lyufWuvfvGCD0loDtzMXMw%2Fr2Q%2BQH8C%2Fjr%2FPzwC8yHmxykostHznU2bh2b%2FOWSEb1vESCWj4i33co1NWLy2PYV7MC01LbtDcc4YP12WrLzEToi2QJGolJZD2B2oK8DngyFzgtTeTJ%2Fpe8BYk5%2FQDFlgf0rfpdwTw2BFYB%2FxxiznfZR3AD5Ye82PA8FV4Mn4H2ng9c1uUjzVZQucxuAgvn7amQsNoV1K9VXbUkgLkTs5bcrj%2Bxtv0XBOry37QamqlyZLAF7gvV4nOrTLaJi6HeH9H%2BAjq%2FchSc68gRy%2BXA4%2FDbb%2BgDzLrPbsTF27KsPHenzvpZcdkKSbUVFbVZV3inJrgcJyBr1tTvRHIE9OiBrN9bucuuY1E83jU5%2Bt2h15RoK6D8JGBS9GIp1wuNwMtyTWw%2B59%2BSkfQET9iLvQOMQgQUou3EMkf0Zz61zAfVWZr3M5WGaXFSPHpS50VllZYvrKboZATIA%2BkbLAOznqRUlC6jsPw2YwwRwZZ9hZqipg6K39mlPidlsIAAY%2Bxk5TfvbJhOn7mr3fZB9jLkEM8gohOD5WT%2FnYtOWhoMo8G8BRjcfxeFkgLUIeCHjEEDayFLyZ64J87zQ0bwT0XdZMs0hZQsLwx87HmMeTzDl6WxIPChygyuQ5%2F22vA9gv7UUFXW4sv%2F2HebQaMh9D2BPgZKflbFut9zxqHiNn6L9Y2U9kei3pshVOOPmycn9RpyUWWaQUR6yG9e6OUY6AP8yYNN8uk3RQBz9Xobs0zKPBPp8pd6lnL4N4Gy8o3GaEgN4MXmPcG0oX0xP1D28HF%2FmkTKDjBjQlB4bb7%2FDBg1BT9xkT7zsT%2BpTXPhDFi1FvS5A3gs%2BT%2Fh88D18pvMDJV8iyhxvmcetxTT%2BCPO3INzIN2jifN67EuXk9MyPfpvz1NGtxyY6kDGb5YGeZXKEGnhHgNcg04P6K4diydqKdQ%2FtbbuR%2BURx%2F7OlEVDmKRLrgM0i4oKvKHW%2BDAXPB4XuoWWaLp0bFL%2B7JXsafyF7kGsJILfpXLnQMagahrqd%2BAyAbgPfDT4Xc1mO4iZXCBM8WXba15KOCSiHiTttVwImdn4QUgBYBczEqmQfD61T2xzzOR7jbMfcXZ%2BJNQtLfULkfVlSTtN82lYR971KxillYKvtmpoSClOe9WK%2BelROTKUvMYUlfZah08FMSD%2FzHA0u4hzsPvbVorKS8hozwLqHWX2T0N2W0N1e%2BF1f1h3NADBOPnS8fXFLvaaC7pLkaQxcgPKFjFfoUrON6R9xBHpRPoNj0KGg6y1j%2FoLyB5JYfZ4ZDD6zDYO%2FBUfiDoz%2FqLjd32N%2Bm6m3J%2F0%2FJ5CO8peSoHppKhbvfUgzH2kSt1M5Z7JuPMZn7KP9wO%2FLPH%2BAI3K7yCyjMnRMbDWifJhkT7rlk9G30v9n6fOTlL%2FFeDdRz%2BhzKNdJx6hPr%2BGXOCeAvkBGJpFK0onJh8SJ1p13Kr01vbjFhd5c22W3LsndzkyC7hYuUHJ41%2BprQFsx0aoeIfqsYIT4bKWQ6sCTWRYX3qV63STiAZ5mKXYfNzzB%2B%2B6zksae7nSp%2B82JyQr5%2FU4%2BDXVZepGsijXf%2FPAnXC8tjYYR1FXf2kLHqkVA%2B360RKoPx6kZSQ82G8A%2BA39pRfoJFzA9iZJI9QmgxWxYmXXGP66MBdiyVn0V6wSIOM2nAPZUJoBxDXrK3JOUHjDbJLFdSADjiRDZX2mONbmc3wdYnrARwM72SSrnafjBOI9xpZuzzBgwmjg8TucJ00mi3PRnwIzEMmAxi5jYwW6QOQBgxgJsLfmsMQZyV8iCbuaUMgVMYqhvnVNWSAWBH%2BwPMKx%2FY4yxDn7XwzyuYT8bMN5pWOtz9rXhAGYGAIw0UbMtZCQy32W2hjrPHjAQYx7eJWqOsIDLFTDZKTuJzf%2Fd4l9Qv32mgNnMU80NoaYlC8DOo0m27zIJjn%2BmY5AWMLlLuUH5K1eCC1gTmdkZDYl4h2UIGOe5Bu9Kd%2B0CXChjwJwvwD%2FpgAKYTRF6N5jUEXQw1FxwgZkAJpn4UsgebmXKy7MFjH1R%2F4ncIUdzEzDuRH1NBiZxNDjsAxipXUAVvWQGmIow4Yz2fakHO%2FuSNWCafeDJsQALpzm%2BdWqKaCoyBEzvsALWOZtjtOz%2BN33emVBFOoBxLds6DlRjZoAJ%2BQNGivOUZAqYuP8uRXTddOjSAbabD2Cb00b7HOG1eXJUiXRfeXk6C0xSETSjVE6WgBnGJKwTN3cOzZIqRtJoedYiL7C9R6abBDBSsZ4C5gelbiDAajgFYbanuIktwJrBNg3nSU4D2DkuYOKwHUWLhMdaZ7O%2FL3OYaPwQhQJv0MtTvDFP4qev%2FTw%2FIm%2Ft3o3l4vyOpopKE9P5HmMje968%2B2QXvujERm2Wc3CgZbs9AmE5POPAUxnn6UmTeO0L3iVWMBpjpl9ivCrdaIyB8FjiJH5%2F4053Ngj5O44rrJ9X5kBmQz6LZ%2BjSeP5ByAFsCOcoluIO55vaMLFYP3OukHtc3vs53rOJSUPt%2FASvjPJYcJlVHpXONGgGQmKkFG2uZDhGEyDXTDrvGWm1jXXaIk5YMEKi%2FxapK5Ls%2Bma0BHSKaELtDaBjKYiO%2BfbQtqjKyF2Rx3dInR8vypNq9ZlvAL0odThri%2Fv8V6Qb480jie8JfI%2F5DymggAL6A7%2FPpMSyS0OKAAAAAElFTkSuQmCC) ![ESP32](https://img.shields.io/static/v1?label=&logo=espressif&message=ESP32&color=000000) ![ESP8266](https://img.shields.io/static/v1?label=&logo=espressif&message=ESP8266&color=000000) ![Rasppery Pi 2040](https://img.shields.io/static/v1?&message=RP2040&color=A22846&logo=Raspberry+Pi&logoColor=FFFFFF&label=) ![STMicroelectronics](https://img.shields.io/static/v1?style=flat&message=STM32F4&color=03234B&logo=STMicroelectronics&logoColor=FFFFFF&label=)

## **Coding Languages**

![C](https://img.shields.io/badge/Code-C-informational?style=flat&logo=C&color=003B57)
![C++](https://img.shields.io/badge/Code-C++-informational?style=flat&logo=Cplusplus&color=61DAFB)
![Python](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=Python&color=3670A0&logoColor=ffdd54)
![Verilog](https://img.shields.io/static/v1?label=Code&message=Verilog&color=blue&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAABGdBTUEAALGPC%2FxhBQAAAAFzUkdCAK7OHOkAAAAgY0hSTQAAeiYAAICEAAD6AAAAgOgAAHUwAADqYAAAOpgAABdwnLpRPAAAAVZQTFRFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA%2F%2F%2F%2FyxSZEQAAAHB0Uk5TACDmwgk%2F%2B5dpllk088FTmnVzaPnPE7MFkpCcQuEewAe4Tt%2FFG2zlqAiD5%2BReJ3eMiGAMNX6NhFAEPn96K2H%2BgQJNvb6nZL8OR7DDxkXZ2AooItfa1tW7b9zd4N5qGkaHexyJbR1cSmu3ErKPm1JyWFVY6tcAAAABYktHRHGvB1ziAAAACXBIWXMAAA7EAAAOxAGVKw4bAAABf0lEQVQ4y92TWVOCUBiGKbG00lJLshCLFrVNrFxTs0NpUma2mEtGubQv5%2F9f9R2QxqkB7%2FsuzjMcHjjD8L4UBTM0bKIB5pFRcmXBFgIrHqO0GZ%2BwEcGOJ8nVFHaogvNHMLumZwBO7GYAs9hDNufUFykz72K9yrs5WnnUCqtvoU9Y5JeWASur%2FgAguBaENeBf39Dub26FhPA2tbMbicbiVCIZSSaoeCwa2kv1hHQGYzhjH2fIGVaAlaI5gHZGGvcErApYFbAmZA8QEg%2B9zFEOcZ68z8EhzuHLezgk2rPk%2FnGBkyTJJCIFCNkANoRMknQiFU7hc9xYZzLFM%2Bz2USVRTyiely9sJQPhcpCQubrGOSOBjPhfBLpiJFQgYjc8X61Wa3W2QcAqaLBsDcA3buFvMs07WRbuUw92QW61y51uS251O%2BV2SxYem4wSiDAkqm4QmMGRGxhaLfZPerGH4tT%2FFue5rzhQvReleq9q9d7I5nuf0Cvvh1bez9%2Fl1an%2FF8E34yTzLFjpmLMAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDItMDdUMTc6MjQ6NDUrMDA6MDDiWEe%2BAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTAyLTA3VDE3OjI0OjQ1KzAwOjAwkwX%2FAgAAAEZ0RVh0c29mdHdhcmUASW1hZ2VNYWdpY2sgNi43LjgtOSAyMDE5LTAyLTAxIFExNiBodHRwOi8vd3d3LmltYWdlbWFnaWNrLm9yZ0F74sgAAAAYdEVYdFRodW1iOjpEb2N1bWVudDo6UGFnZXMAMaf%2Fuy8AAAAYdEVYdFRodW1iOjpJbWFnZTo6aGVpZ2h0ADUxMsDQUFEAAAAXdEVYdFRodW1iOjpJbWFnZTo6V2lkdGgANTEyHHwD3AAAABl0RVh0VGh1bWI6Ok1pbWV0eXBlAGltYWdlL3BuZz%2ByVk4AAAAXdEVYdFRodW1iOjpNVGltZQAxNTgxMDk2Mjg13VzE4wAAABN0RVh0VGh1bWI6OlNpemUANy41M0tCQs3klRUAAABDdEVYdFRodW1iOjpVUkkAZmlsZTovLy4vdXBsb2Fkcy81Ni9zWnp0MUtzLzIxNDgvdmVyaWxvZ19pY29uXzEzMTg5NC5wbmc%2BkF9GAAAAAElFTkSuQmCC)
![Rust](https://img.shields.io/badge/Code-Rust-informational?style=flat&logo=Rust&color=FF0000&logoColor=black)
![Java](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=Java&color=white&logoColor=orange)
</br>

## **Electronic Design Automation**
![KiCad](https://img.shields.io/static/v1?label=&message=KiCad&color=white&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGwAAAAoCAYAAAAbrx%2B3AAAIUklEQVR42u2aA3RkSxPH%2B2lsI7Zt27aTZ9u2bdu2jeDZWNtGnEl%2FXTlnNbl9J7kzmcx%2BO%2F9z6r3dnb49t%2Fs3XV1d1cgttzjJIEFavQTpkFuurSpfVLjwBPQnvhBhsKUnov9qA1EFcsv1lO%2BJMicuQOMAan%2BzXIAmKgJQEWKVWzyhwr9WrAxpdZZ92iboB0BM1tvF%2BwXaCOWB9QghoRuPlWSamLM8I0%2FCzrT%2FTlFhGrCVp8v2tpPpEq9wE7ISmZTLYXKiSl7AMWWvOsXeOiGPCuzjk9JxdOkrU8AUprTbELPcwGAiYyvecoqV1j6GN5wzfZVtOVeOq%2BoeIm3ePGSA8WXepWJZQDuT8XjKKJcABlZQ8xR%2B%2FrhKvOBMX7zwTB%2F80vFluLj2cfjMTmByJY%2BnDuGJdVECgdwX9mjkwhKpwo4xhx%2BLmUymi7%2BaFdizby7Gfy7YSrWbH%2FqDcfKzW96Hz1ntubcW49T6d22B5ALsCJHUr0LtlfucMbh99fSBHzOq96%2F5Ua5Puo7HU4W73ArjywI4A%2Bs4%2BytM0%2BQkxkVdHzFO8EmX9WI2ffT1apxU8w60dSgwkcy7XB%2FY%2FC9lwIym86n4nC%2F3hKPD4cgVJBR6cgaWUvcupmnN%2BkHGyU2uewcvXLoD0%2FTZd2twQtXb0NaRwPgKj%2BxHYVAczSIQexW4CDAPzsDiK9%2BGlcSo%2F5ZsnzaxcZVv4fc%2BX4lp%2BuH3TTi5lrKyuAMTa30rv7QDFgb3iED%2Fz8D%2BXTwd2MMv%2FIdpWrhsB85sfh%2FaORLY4RrfsvfYYJjCegY1vuWfKT2zn1Z5FbxiCGpasP%2FnWr%2BKL2DfO%2BSAXXnXL5imdRuHcHE3w35nJzCpJvZcNlgKY9pdpJli2pxITen6gMY%2FTcHtaxESGxDoUAJ2MgkyxsctmEk7d43hhlM%2Bh3YOBibRmUK7d1EHZzsrIjtKpIlHM9MREFHySVAjVga2iZUB7SKpTzV5Po58JuCCRSA1ZgqVga1gAok5D44fTgHWdNoXeNfgOGbS6JgFH3fRd6ww4kkAMvDrRjxhmWS0C2%2F%2BkRGYzJBwFTXyC6j7xZ6oD85rIqlvpUyfeC24U%2FLD2El3uUcPq32K3xZITRnIpiRapTnzAeKmdzMcN8bVPiXvQMQ6Z8DAza3fNISZZCEPXnjTjzNaQZfc%2BhOm6SIKMENQ8yLawMTK4HZkh%2BSm5Fs4BC%2BTCkPSVYgiWI3ggm31A%2BDmBNiKNbvwgqXbMU23PfrnjF3eqVf0zQqYQKDwYRnwGGxvdu8jYceMcok4hcqgFqazlTGkYyOH%2FhwHjEWQxZjVHnXK5bMDJlL41LC7Q%2Ful8sx9av%2FVYwhqWQyHbI1vxWfGkM4ttO%2FXBzb%2Bi6yk9i56Az5zSWAff7ManptTYGJt1Jm0QWm8Cl9BDhCPp4%2FU%2BdUMiFShx8LeY51U0fiUfkB7Bz5fE7yvH3UoAKe5UQLhcoSk6j2BCPTrNGDQtO2srwDCnAIjL34FbVBKc9bDyAk6SqSNpbpFuX%2FzvuAo8WqWd33QaWE9TSvW7MZZLe%2FPJ7CHHM2Gx1NGTIX0iqAukTLsRJEq5Hiy8o6jvQN4gD0PkyzMV7R25KgQNu%2FAQN%2F9tB7C9blziZrIs2mDUnkWvIDs12EkrK%2FSeJe8B5mS2e41Um30hXs6MoV2bWJqQ%2F59C3yP04ANDo1jCwvNx19ZOGfAhHK%2FetqgtH7VvcgeiUQmSm6SCzAhZf%2BC4Ohnp2c67n%2F2H9byy%2Fk3%2FjAHwNhrRnAo5V6klKrJ%2BW4x9OMYYBId9YflW%2FGV04FBdv5TUi6haWh4HDee9oXDgYEMwa3LaQODLAWnA7M56362JDIJz9%2BE7IdUG3Ox3Jj5oG1gYj3dE1R9Oy%2B5xLSG96Yy8TStWrcbZ7d%2B4HBgckPSTdSzGLhF2B9mp8PJvrKNMrm9MPnW6asZuEQBzSVCpmbekr8Vx36Ct%2B0YxTT1%2FbIBghCHAoPsAcnjjdAHl3ClrcBCqos5HyGREU1JbKD1tSdPyAEYmyewwHfOW3nlxEt78cQEPQh56rWFDgUGkhuTb4SBsJ%2FJZCpkJQin9xxQNSThuqdYQwXGUI2GTP9MgCk9c5%2Bmln%2FMpPxjJYHEI8dpBcxbHvmD9VANk%2B9AYCCBLqD%2BV1sFTMiCK0wZdytM2Y%2Fq%2FGt%2FsnZTYkVIN6w4ku9bz9QH3BMRCvUp0AZY8WWexSRVtWQmwAjsfLb303gWvES%2Bv0eijjhZ7VX0GslhTjjtigDYu5%2BvZAlCJnDz6V86DNge12gIblthT1QHexe4IoDK2jbsmBFKNp0KDMThmMAJGNy%2FYAsmGIBBEPIuXr1uENO0dsMgLuz88IBnTruyH1MEpRd2YCCBwlsfUP%2BHPZOh9i5%2BE8JwKIHYH9bHXIL2E1QXyOrdYG%2B%2FckPKzazAYDXQZLFM4rz2DxmhXXffb5hNUJbJ3i99ddXdv2Ca7nj8LxowawlhQJRAhGrG0M4tkIDdU%2FHlSZQRxN0ttfUcgCWR3jLGvcmUeS%2FDvhkOkeEM%2B2V0t1AoZQX28ntLoe5FtdseY655HXfRt%2FA5q33y7ZqpSzkQPX7Wu4barvfnDTip5m0KMOZMhUwffxlcFqW5L1JB3g5pJ7hlC6dbptKwVBt7EZm4BdMAh3SskxtSb4VDttor71loY206v7oBhBQKNF1iuT7hUqYfhDG4dTUEURAkqcw5TzL1S%2B6h%2FAHHCxe4qm3%2FRVKKhPDLFkgM2QKxOf8oCBwESq%2FZXR8Q648SGRIh6ADXBoGHgy7bmMn7JIPBPow46GAE5hZJvVwGk%2BOXeAmxy1zELp0CpjSl3uImxHAZX%2BNd9CI5UL7lWlb8MgQEyC23Dkb9DyzRPzoBjvqGAAAAAElFTkSuQmCC&logoWidth=40)
![EasyEDA](https://img.shields.io/static/v1?label=&message=EasyEDA&color=5588FF&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGUAAABlCAYAAABUfC3PAAAAAXNSR0IArs4c6QAACJNJREFUeF7tnXlsF0UUx78th60iQoIQlSMmJh54RkKiiMFgjNFoIodQQChEDEEgBQGj4RASFSlHBZWjQKQCrQfRSMSLEDQQjRLBC1ACGkEBD1AwhdIi5tFOftPt7s6b3dnfb7bM%2Ftff782b976febP7252d5g2cc%2FYs3GGVAnkOilU8zgXjoNjHxEGxkImD4qDYqICFMblzioNioQIWhuQqxUGxUAELQ3KV4qBYqICFIblKcVAsVMDCkFylOCgWKmBhSKmvlJfHAB3a8pTd9DVQ%2FiHPNpdWqYTy%2BtT4klXXACNfjO8nCQ%2BpgmIChp%2BIg%2BYmIW10n6mAkhQMWbZj%2FwJjXokupMmWVkNp2QJY%2B4TJdNW%2BbKgaa6HMLQa6dVSLmIRFrsFYCaViInBBK77cNXXA8AXB9h3bAYsf4%2Fsjy1yCsQ5K2WjgsvY8AaMId1EBsGpCcv55nsOtsg6ldUvgtUnxQo8Cw9sjgacBoDpM9KXqw%2Ft9VqDk5wGVU3RDa2pPywYHl8b3I3vgXNllG0ziUDhJc2TesR%2BY8xbHUt9GFePTFcC%2Bw%2Fp%2Bo7ZIDIoqUZ2As%2FHrWxVvNqslESiqBHWAZPNKKCzuF9YDX%2B3TjTyavXEoaQVC8j1TBFzbJVzICcuBI39HE5vbyigUHSCTVwEH%2Fmwa5uyhwNVXZD7P5rRBvXJzGP0ScLyaK7OenTEonGRO1QIjFuoFmG1rTh5yTEkMmqxBSSL4pIDlGowRKKok0gREZwpLqmISh5I2ICR07%2B4A%2FeB9sCfQuQO%2FHk3lGhtKWJWc%2BQ8YMo%2BflM2Wg3sDD90WHuHG7cDqzfGzSBSKqZETP01zHrIxVTsoEXiFgTGxOCMxKFu%2BA5ZsjJBxCpq0KQRWjg8ONO4MkRiUofOBujN2Klw1BVj7CbDhi%2BjxhVWLtVDiBhZdruCWXiHjxJhKKDPWAT8cTEJafZ9JCHh9N2D6IP9Y4sAmj4lNX%2BQ8bnD68jduobpSIusRZcCp0%2Fo9tW8DLB17HkBRibjzJ%2BD5N9UCqvx4PUQZPA%2F0BIb1SSGU4jLgJGMU6oq45yAwc11TQXT9CA%2FDFwI1tWrYskUSU6LwH3v6Ui2EUI3CqEKK6bFFPrBusp6gwloVW5hXq6FQ4Cphg5JXtYsmtbpVHBjkvWoqkBfSTVz%2FsSuFYrvrRmDMveFieAPNBZC4YlGGbQuB8gR%2FOBq5%2BhIoOCKLcwzHVj3e%2BRYmYFBvnMfFJvoyUik6YDhSehMraAWsnshpmbGhneUGG3rF4c7uwOP3q%2Fs3AcRopZxzlgfQLYw4R1hinArTeeQ8bxTQReN5SVhe720HKgzctjcOhRwmeTUUBmX%2FYeCpCv5w4ADmezP7Q9no9CUnESVpVfkP7AUM6OUvlaqtt1WU%2BPx6%2FusEMHaJDj61bWJQqGvdxFXCrhgPXFxoDxR6qkpPV00fiULRvQDYdQCYVRmcoskfbLoDRo4q6WW0WYEiEurUDlikeHmHpgKaEnSnG1WV%2BaHWBTNsAVBbZ7oumvrLKhSdytm2G9i6C3iyv1qEYfOBWksfqKmjtwRKlPNNWHJRqiSKWNlqk5NKoeQWjgYuZ75Gdz4BoVxzBoU6p7e7aNFb1KO5VYjQIadQKIgbugHTAh6rnm8VYg0UEQjdnqHbNKqDdoWg3SGa85HzSvETt7gv0PcmgB6g%2FVMNjF%2Bm%2F2QwzdCshJJmQU3E7qCYUNGwDwfFsKAm3DkoJlQ07MNBMSyoCXcOigkVDfuIDEV1h7WkHDh0zHC0mu6WjwMuuTC8kXxXICgn7p0D0X7J%2B8CWbzWDlcwTg0J9cJOJHn54S9XAkWOc2g%2B49apgf5u%2FAZZ9EPw97cxEv6vEESf32FB%2BPgLUep6%2BVZ8CnmOs%2BU0KhvArQ6E45YNifvYN4GRN%2Faey7e4DwJWdgILWjduELcM1%2BZpFJCjXdAZmDakPWGdE3H0zsGknD8U9twAf7eDZBlnJQqniDLNV%2BfF7TK3qLyyzSFBWl2RGEadzv2lEZymrsBV%2BSlYAh442TstPOPHZ3t%2BAaWv4U503NtrLkva0DBqEOvlxhlkkKKqRI3ccNq%2FTOilaL%2BU33cg%2BxKt6nNFMq%2FFpVb48JY1bCvxxPDoU7%2FQmQ1s5AWhTkJkx%2BvcC1m%2FjSB9sExtKkGsKPEjEyslAfn6mpbcSxIgUW%2BCK7%2BXFfkFXTZyrKdGzny3tvOf3j3uDcqHPhR%2FajFT3lQo%2F%2FRKBcvQEsHV3%2FY4NnJIPguIXsBBHFk98Jr%2BVVdgaeLUkfMT6QeFMq8JG7ApLf6%2BZBLRqmQEkw9Ktm1hQKj8F3vncv0vVFBc28oTH6WuBH38NP3dw%2FKjOe%2FIelzpQRN%2FeNkGfc%2BHEghKWLBfK978As6uChafvyEYc%2FW8HHr6j%2Fi9aDCdeGAoSJqhS5R6n9AN6NPxGUUF5dDFw4mSmMrxTYekooGvD%2BmTaz4z2NdM9cg5FJYKfqJyrHdWgkIVS2YZd2akEV1WpkXMK9zdKWKIzi4DrGrYF9M7rnHme80NNJTQXiuznzFlgSGl9ddJCdjp%2B99m6kM4t9PYwp0qNQAm7xKUOTtcBjzRscS7binthQYLKn9NuQPf1yITrHW3ee1p%2Bo1EVp85VmneK4gCPc17Rnr5Uycqjg%2F6jA13Whh1%2BV16yvd%2F7JvJ5hTP9%2BfUvr5bXyUl%2B35FzTi17F%2Fhsj2qSa%2Fy9cSi03HTRhkwnQ%2FtkLo3p05UfZ26feC8bu14KlI7MtKX7UsU%2B%2Fw1IZ6QGycGplC%2F3AvPebuyB0ze14NoZmb70mJu3nlEEdPc5H5nvKXcetSsld6HW9yxGIO2QRLdfmuORKijl44C2DQ%2BtolxqpgVgqqCIKqFb%2BnRuaq5HqqA0VwjevBwUC0k7KA6KhQpYGJKrFAfFQgUsDMlVioNioQIWhuQqxUGxUAELQ3KV4qBYqICFIblKsRDK%2F0ANm%2Fr7waacAAAAAElFTkSuQmCC&logoHeight-40)
![EagleCAD](https://img.shields.io/static/v1?label=&message=EagleCAD&color=E3D8CD&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADEAAAAxCAYAAABznEEcAAAAAXNSR0IArs4c6QAACUdJREFUaEPtWX1sVtUZ%2F52P%2B75vW6At31hMgbasAxS1DIMTkLEghk0Ss8WvmLGFZUsW56a4qRvsw5DsDzKSZXER4zY0m9PuIxFmRAvWAYM6aKG10oI2tJShFKl2bWnfe%2B95luec21q3xPaUjxDiTd68995z7rnP73l%2Bz3k%2BrsAVcIgrAAM%2BBXG5WNHbEo%2FdUTGtK8zmTxkbbJwyRsyRQkzNz5EFeQFBCgEtHTQlCBASqRQhoBjSROjopf%2B0nJV7PuiLHvnRc2%2FWXygleIHY%2BbNl1HHyBCiMEGZD6DH5qFhUgcZDDXj%2F5Cnk5qYtEKUUlIgRBBopCUjJ4PhHkIgRSEArCZ2ThyB3HHIKx%2BMHr76oKysRjwaYF4ita2ZTYR6ht7sXRISY3OPGRCDSIBhksyFKrpmHWTOLcPj1amgloISCVgSlgICFF4AQAilFCIIUVEpDp9MQOoOyh%2Fd5ycTv93rg6XuKyUQRCvIAYgBEFoyxQARi4jM3xjoPTcwDgE7j9jtWoK5qB9IpibRi6jEwQAsByf%2FWYhKZlMKM9c1ecnlNfuruq4mFGlcwDqmwGzE54xtjHBghYCBAxoEjkogZl4gQG%2BmsFxuUziunTFer0CIBJAElhf0JKVH%2B82NecnlN%2Fu1dVxHLzcotzBNIaZEICyssa9%2BQsSBYdqabA8MgJQx4zIFx82Lc%2BtXVOHvgFSgdWGuwv5Q93uIll9fkrfdMo4icENmYUDxeJ5ZIaEXS8jNkQAnVBulmBR8AxRZjEO46NgI3LlkAdarRWmND8w26srJyxE7uB%2BLeIrJ8F8KaY%2BJYgmZvJSQ0Yo3bS%2Bsjhu%2Fztd0EHPeYbkyp5BKGwRknRmQMFs5MY1vLmNXrKxtfHOlO5QXi2fuKyLAlmPMAppeVQXS8M7gvOq0OWIHBCBh2HMFOz9ZKND9kQ%2BB7zqcYNFsIKJ2a07l089vjLwqIP95XxGErEc7AmBAzJqUthVibFoTdnVjgj6zgzt09Oz7oF04ZrJSIV7FWA9LI4s4%2FdIxYwSOeyFp57mtFxNplDtutFAKlMyYg7jqbUId57%2FwCJgSpFI52it8QqX4tkTEmRhhGORAyHcWxFFIrAxOK2PRFqdyTO46GW6oOtrSN1AID87xAPL9mOhm2RKIx1u6CJZ9H51v77XbLGuUjNITlv27zWttX8KHzvV70569fbS0RJc7KPO7v78Pc6XkJMAdi0ebjXuueDwDviP3Xb0wnIxQ4EMdw26oQBmWTUm7nYR82ET73yxOXL4i%2FrS22iYWjE7l9HkDZBEAoDmaOUgs2XcaW2P7NIopFKnFit9cbQygtCKEzOWwbwEhUncq%2F66Fnap8%2FX5qM9Hkvs2%2F71iyykdbu90wfB2TBdbPQfarVphdu15Loj0T01K6C3C0HD4YjFWa087xAvPTtWezXVvvsExwbBBFuXnkLOg7tdgCSAOF8xlVIfC5sUIuRkoQsNDq6TUsW%2Br3T51JNu1vMM7%2Bvbqq%2BJCB2fKeUXNByeZC1BAgrbl%2BJEzVVNqA5IAmYxNntfR4SnChKmLAflDcBYWYMorAfSqfx9%2Frer2x8oe4vowHiZYlX7y8hzmC57ORUwabi1hJfxJnaXYnWk0BoiedQcA1SOO9mvHHwTWQCtwlwBsx5l1ICgZaobw8fXPtE7eaLDmLnd0vJWcFpO4ltqFj4WXS1NH3s%2FZxGTL1%2BCV7eVgWdl4eAKzwloLWy51yyKq7ytLSlak1rdu39T9Y9fdFBVH%2BvjOIk%2BWO%2FsLkQScyeqoAoGny%2FLpyMfUc6oLSCVDIBwJWbQkopCOWKIAYkud7WCgsf3e%2FFilFH7Ne%2FP9v6hAWQ5E7Mr%2BKxWaggbe9k5i3Hntf%2B4TQNQLL2FYOB07yQUNqdczkaBBLpIJW97uHdvMCoDi%2F0ux%2F6zCCdLJU4hQZQXMC5qcLEG2%2FDKy9VuY4HNwMk00ZBSWOtwgAcGL7PYNL48FxUf9vGmvmjkj55yAvEnnXlJMg59IA%2FZLMRZk5UMFEfGrrGQvF2KhVX2tYaQnHZGSdgnC%2BkA4H9x%2BWaB3%2F3xtbzEX7gWS8Qe9fNIc6VmE5MHf7jUnTmuAinC%2BbivbYWCN5HBbC9Ibp2S1VTw4UQcrg1vED8c91cgnABmINzDIE5i5eh40AVjnVr6CBlY8iqTQ1e6w4n5HDjXi9jS2gVD9bNvHjhxELEH55Ge5xvrcOl6MpfHPJadzghhxv3elnND8sJxEkEl6iu6B8jzoELvbNyvKUR%2B8IXNl7GIOoe4bRDgiMCJ1F9%2FVnkau7mSXTKXKQzaRgjccvj%2F%2FJSznCaHm7c62WHHy0j2xBLcqKr5i9E24G9NnzPW3YrDtfVMpvQ3iX%2FdOemmruHe%2FmFGvcC0fhYCUXc1056St09vXbrtIcAgkmT7f7Pi57LijNLf7p%2F0oUS9JPW8QPx4zKbpkYGCLP96OrjVJtLVNu0wZTZc9Hd%2FQGk9Q1OKThmcLoB8Ewb%2FIRAXxadsZBtnIL19FGvAnryx6rJPGYImWsf2FXuA94LRPNPyshEBrGQmFB%2BPQ7v3ZcAcK%2B07chVX0b70Tp7zYGNt1wWjhvFNhWxbX3Ye5KzWBvVXaufx2UUY8ranV5yeU1u3lBC0tqC0Pxu1u1G1goJo3hMEhZ%2FaTVa36m3FhngGn9kGRCen2FQioElrf0BIO31R1Cxya%2Fd4wXi7Q0zCNAgrdHY2mM7HYxEKAWKIyuQgwjcsGw5es602CzWajkZsxbh3Iq1wbkUg7GZooQig2O1zd4tHy8Qx9YXkxAB6tqzrr%2FPEAYtwUIxAta47fMjzvajYukiaJxLaMUpOE9x1LKWSf55Lf5M1ri%2FEUt%2B1eoll9fk5vUlpCnmAmbwGxMvMACE6%2B2PA0vIpBUWL70GcRgOOrqlFH%2BcHPKxShqgtqYJK564yCDaezM4%2Be7ZhOu8M7m2po3fTJuhX9BY1TYT4XlASDFuWnwT8oNu%2B33LNhWG%2BFR3RxeONJ%2FAqifbvZTrNbllfTG9drTf%2BcFQh%2BZzwTWFzWGTsDFw5gD878FFEWNYuGg%2BCsc532pqaMOzjVS8ZftbXk1lLxAvPzCXjv%2F7fadBpSEMN%2FrdYbiGIOZ40tmwHu78xFmI%2FZi%2FDhkbIMlEyNNAfc%2F4F%2FZ0Tru3urr6o%2Fr2%2FzF%2F4h0vEJ5rX7Lpn4K4ZKoe5kVXhCX%2BC1G0f24AESeRAAAAAElFTkSuQmCC&logoHeight=40)

## **Top Languages**
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jminjares4&layout=compact&hide=CMake,html,Assembly,Batchfile,Makefile,XS,css,JavaScript&theme=react&hide_border=false)](https://github.com/jminjares4/)

## **GitHub Stats** 
[![Jminjares4's github stats](https://github-readme-stats.vercel.app/api?username=jminjares4&theme=react&hide_border=false)](https://github.com/jminjares4)

## ***Contact:***
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white&style=flat)](mailto:jminjares4@miners.utep.edu)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&style=flat)](https://www.linkedin.com/in/jesusminjares) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white&style=flat)](https://github.com/jminjares4) [![Linktree](https://img.shields.io/badge/linktree-39E09B?style=for-the-badge&logo=linktree&logoColor=white&style=flat)](https://linktr.ee/JesusMinjares)
[![Resume Badge](https://img.shields.io/static/v1?label=&message=Resume&color=grey&logo=Github)](https://jminjares4.github.io/resume/)



