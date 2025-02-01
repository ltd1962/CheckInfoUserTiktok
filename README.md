# CheckInfoUserTiktok

### 1. How to use - Cách sử dụng

```
# Method GET: "https://ltdsoftware.online/apitiktok/checkinfouser.php?link=" + link_user_tiktok
# Example: "https://ltdsoftware.online/apitiktok/checkinfouser.php?link=https://www.tiktok.com/@tphuongg105"
```

### 2. Result - Kết quả trả về
# Success - Thành công
```
Example - Ví dụ
{
    {"name":"Ph\u01b0\u01a1ng th\u1eed vi\u1ec7c","following":"52","followers":"264200","friend":"0"}
}
```

# Fail - Thất bại
```
Example - Ví dụ
{
    "" hoặc {"name":"","following":"","followers":"","friend":"0"}
}
```
