# make-token
for Twitter  

get `Access Token` & `Access Token Secret` using Consumer key

## Requirement 
- tweepy
- urllib

## Use
### 1. SET your paramator
set your `consumer key` and `consumer secret` at line 4-5  
`CONSUMER_KEY`  
`CONSUMER_SECRET`  

### 2. get authorization url
```
python3.7 maketoken.py
Redirect URL https://api.twitter.com/oauth/authorize?oauth_token=AAAAAAAAAAAAAAA
oauth_token:  AAAAAAAAAAAAAAA
```

### 3. authorize
copy and past `Redirect URL` to browser and access.  
get 6-digit pin code.

### 4. generate token
type your pin-code to console.  
so generated and saved to `auth_info.txt` your `Access Token` & `Access Token Secret`.
```
key:1938298308402193021
secret:30901jdfnewioufbwehfw9ef
```
