# AI-HUB-Geekhub
## Data_cleaning
### binary
- host_is_superhost
- host_has_profile_pic 
- host_identity_verified 
- is_location_exact
- is_business_travel_ready
- instant_bookable
- require_guest_profile_picture
- require_guest_phone_verification

### multiplement
- bed_type : 'Real Bed' = 0, 'Couch' = 1, 'Futon' = 2, 'Airbed' = 3, 'Pull-out Sofa' = 4 (解决办法：df.replace('x', 'y'))
- room_type : 'Entire home/apt' = 0, 'Private room' = 1, 'Shared room' = 2
- is_business_travel_ready :'strict_14_with_grace_period' = 0, 'moderate' = 1, 'flexible' = 2


### 遇到的问题
- [如何修改dataframe某一列的问题](https://www.jianshu.com/p/2557a805211f)

### source
[北京地铁经纬度](https://wenku.baidu.com/view/4f997569c4da50e2524de518964bcf84b8d52d17.html?re=view###)
