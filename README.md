# passfzf
pass + fzf 

Data is copied to the PRIMARY selection (`xsel --help`) — mouse middle click to paste.  
The PRIMARY selection clears itself after 25 seconds (only if the data still matches the copied one)


##### Supports a field with a header (copies only data without a header):

``` 
email: test@gmail.com

```
The PRIMARY selection will only be `test@gmail.com`

## Find file and get any string (also via fzf):  

```bash 
passfzf show
```


## Get OTP Code:  

```bash 
passfzf otp
```
> Yes, the OTP selection is also triggered via fzf, which makes no sense, but I don't give a fuck 😈

# Dependencies

* pass
* fzf  
* find
* awk  
* xsel  
* xclip  



